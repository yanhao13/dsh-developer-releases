Harness Agent using [grok build](https://x.ai/build) 0.1 + high thinking.

# Code-Change Tracking — 5 Tools Applied to `master@{8day}...master@{7day}`

**Window resolved:** GitHub's `master@{8day}` = commit `b150a551` (2026-08-21T12:03:37Z, the dsh-0.1.1-rc.2 release merge); `master@{7day}` = `cd5ef814` (2026-08-28T00:57:43+08:00, the dsh-0.1.2-alpha.1 release merge).
**Verified counts:** 1,079 commits · 6,421 changed files — matches the stated "Commits 1,079, Files changed 5,000+" (actual 6,421).
**Source data:** blobless clone `dsh-upstream/` (current master history after force-push; blobs fetched on demand for diff).

## Applied matrix

| Tool | Input Source (this run) | Primary Function Applied | Ideal Lifecycle Step | Artifact |
|------|-------------------------|--------------------------|----------------------|----------|
| `pr-reference` | Local git history: `b150a551..cd5ef814` | Generated `<commit_history>` XML with 1,079 commits and the full unified diff of 6,421 files; companion file table + chunk index | Development — preparing a submission | [`pr-reference/pr-reference.xml`](pr-reference/pr-reference.xml) (see stats below) |
| `change` | Workspace delta: 6,823 committed paths (no-renames) → 254 changed `@deepseek-ai/dsh-*` packages | Classified each changed package `minor`/`patch`/`none` and emitted beachball-schema change files + repo-native `change-scope.json` | Commit — categorizing semantic per-package changes | [`change/`](change/) (254 JSON change files + report) |
| `wiki-changelog` | Historical git log lines: 1,079 commits (794 kept after noise-merge filtering) | Grouped by day into the 7 emoji categories with linked commit hashes | Tracking — monitoring development updates | [`wiki-changelog/wiki-changelog.md`](wiki-changelog/wiki-changelog.md) |
| `write-changelog` | First-parent PR chain of the window (126 fp commits → 126 deduped PR/direct entries) | Aggregated into Changes (123) / Fixes (0) / Thank You (0 — all internal) / Skip (3) draft for `## 0.1.2-alpha.1` | Release — building early release draft outlines | [`write-changelog/CHANGELOG.draft.md`](write-changelog/CHANGELOG.draft.md) |
| `docs-changelog` | Automated release strings: `v0.1.2-alpha.1` + processed What's Changed body | Path B.2 (preview non-.0): 5 stripped bold highlights, `preview.md`, `index.md` announcement with PR links, Full Changelog = this compare URL | Deployment — publishing public announcements | [`docs-changelog/preview.md`](docs-changelog/preview.md), [`docs-changelog/index.md`](docs-changelog/index.md) |

## Artifact inventory

| Artifact | Contents |
|----------|----------|
| `pr-reference/pr-reference.xml` | `<commit_history>` XML: 1,079 `<commit>` elements (subject+body CDATA), `<full_diff>` of the 6,421-file window |
| `pr-reference/list-changed-files.md` | Markdown table of all 6,421 files with change type (`added`/`modified`/`deleted`/`renamed`), sorted |
| `pr-reference/chunk-info.txt` | Base/head SHAs + commit/file counts |
| `change/change-scope.json` | Repo-native `ChangeScopeReport` schema: base/head/mergeBase + 6,823 committed paths |
| `change/*.json` (254) | Beachball-schema change files `{type, comment, packageName, email, dependentChangeType}` — 155 minor / 97 patch / 2 none |
| `change/CHANGE-REPORT.md` | Per-package classification evidence + new packages (25) + non-workspace areas |
| `wiki-changelog/wiki-changelog.md` | Daily sections with category bullets, merged duplicates, linked commit hashes, per-day overview line |
| `write-changelog/CHANGELOG.draft.md` | `## 0.1.2-alpha.1` entry in the skill's exact format (Changes / Fixes / Thank You / Skip) |
| `docs-changelog/preview.md` | `# Preview release: v0.1.2-alpha.1`, 5 bold-titled highlights (no PR numbers/authors), What's Changed with `[#N](url)` links, Full Changelog |
| `docs-changelog/index.md` | Announcement entry with PR links + Full Changelog link |

## Tool-to-tool handoffs (lifecycle pipeline)

```
pr-reference ──(6,823 paths)──▶ change ──(1,079 commits)──▶ wiki-changelog
                                   │
                                   └──(PR buckets)──▶ write-changelog ──(v0.1.2-alpha.1 + body)──▶ docs-changelog
```

## Adaptation notes (verified against each skill's SKILL.md)

- **pr-reference** (hve-core): output path in `pr-reference/`. The `list-changed-files` and chunk info companions were applied.
- **change** (fluentui): no beachball in this repo; used repo-native change-scope + beachball-schema JSONs. `major` never assigned. 25 new packages classified as `minor`. 2 packages marked `none` (remote, remote-model — docs/tests-only impact).
- **wiki-changelog** (microsoft/skills deep-wiki): `REPO_URL` from remote; noise merges dropped; duplicates merged.
- **write-changelog** (vscode-pull-request-github): milestone replaced by first-parent chain over the window. All PRs internal → Thank You empty (omitted). Skip for release bumps, docs, tests, CI.
- **docs-changelog** (gemini-cli): alpha release → Path B.2 preview; highlights strip PR/author/"New Contributors"; What's Changed keeps links; Full Changelog uses the `{8day}...{7day}` compare URL.

## Notes on this run

- GitHub force-pushed master between historical views and this run; the resolved `{8day}...{7day}` window (b150a551..cd5ef814) is the authoritative pair matching the user's stated 1,079 / 6,421 numbers.
- 25 new packages landed in this window (webhook, win32-process, inspector, multiple ui-*/client-*/bundle-*/llm-*/session-* splits).
- PTC mode rename ("code" → "ptc") and large API transport refactor (ApiProxy removal) dominate the tail of the window.
