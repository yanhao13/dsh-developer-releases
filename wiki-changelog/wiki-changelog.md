# Wiki Changelog — deepseek-harness (master@{8day}...master@{7day})

**Source repository:** `https://github.com/deepseek-ai/deepseek-harness` (resolved from `git remote get-url origin`)

**Window:** master@{8day} → master@{7day} · 1079 commits in range (794 kept after noise-merge filtering) · grouped daily (within last 7 days).

## 2026-07-17

**1 commits.** 1 feature changes, 0 fixes.

### 🆕 New Features
- feat(spill-local): one-shot startup cleanup for local spill files ([2f430f2](https://github.com/deepseek-ai/deepseek-harness/commit/2f430f2fb))

## 2026-07-20

**3 commits.** 0 feature changes, 2 fixes.

### 🐛 Bug Fixes
- fix(spill-local): make startup cleanup race-safe ([545d177](https://github.com/deepseek-ai/deepseek-harness/commit/545d17791))
- fix(spill-local): exact-shape root/session matching and prune discovered roots ([c6a4de6](https://github.com/deepseek-ai/deepseek-harness/commit/c6a4de620))

### 🔄 Refactoring
- test(spill-local): v8-ignore the two race-only sweep catch branches ([dbb3bcc](https://github.com/deepseek-ai/deepseek-harness/commit/dbb3bcca8))

## 2026-08-04

**1 commits.** 0 feature changes, 0 fixes.

### 🔧 Configuration
- Add global CJK/Latin auto-spacing via text-autospace ([1c80834](https://github.com/deepseek-ai/deepseek-harness/commit/1c808341e))

## 2026-08-09

**2 commits.** 0 feature changes, 1 fixes.

### 🐛 Bug Fixes
- fix(docs): harden subsystem ownership links ([4125dac](https://github.com/deepseek-ai/deepseek-harness/commit/4125dac22))

### 🔄 Refactoring
- test(docs): require package subsystem ownership ([9d37d71](https://github.com/deepseek-ai/deepseek-harness/commit/9d37d7155))

## 2026-08-13

**3 commits.** 0 feature changes, 0 fixes.

### 🔄 Refactoring
- test: make the product translation fixture generic ([36cca40](https://github.com/deepseek-ai/deepseek-harness/commit/36cca4028))
- test: make the Agent Note translation fixture generic ([9d0ef6f](https://github.com/deepseek-ai/deepseek-harness/commit/9d0ef6f5b))
- test: decouple the translation prompt snapshot from live documents ([16d86cf](https://github.com/deepseek-ai/deepseek-harness/commit/16d86cfba))

## 2026-08-14

**4 commits.** 2 feature changes, 1 fixes.

### 🆕 New Features
- feat(team): add experimental Agent Teams Web profile ([806642b](https://github.com/deepseek-ai/deepseek-harness/commit/806642b06))
- feat(team): add experimental Agent Teams CLI profile ([a6c274e](https://github.com/deepseek-ai/deepseek-harness/commit/a6c274e25))

### 🐛 Bug Fixes
- fix(directory-picker-native): stop truncating Win32 UTF-16 paths at U+XX00 ([51c2427](https://github.com/deepseek-ai/deepseek-harness/commit/51c242749))

### 🔄 Refactoring
- test(directory-picker-win32): use a synthetic path in the UTF-16 fixture ([9a2217b](https://github.com/deepseek-ai/deepseek-harness/commit/9a2217b74))

## 2026-08-15

**2 commits.** 1 feature changes, 0 fixes.

### 🆕 New Features
- test(history): add packed transport benchmark ([dec9732](https://github.com/deepseek-ai/deepseek-harness/commit/dec9732d1))

### 🔧 Configuration
- perf(history): carry packed assistant chunks ([f2ca913](https://github.com/deepseek-ai/deepseek-harness/commit/f2ca91375))

## 2026-08-18

**11 commits.** 1 feature changes, 1 fixes.

### 🆕 New Features
- feat(session): add format migration decoder pipeline ([cc9ab20](https://github.com/deepseek-ai/deepseek-harness/commit/cc9ab200c))

### 🐛 Bug Fixes
- fix(history): preserve per-delta replay ([a47e806](https://github.com/deepseek-ai/deepseek-harness/commit/a47e80678))

### 🔄 Refactoring
- test(history): measure complete response parsing ([055c505](https://github.com/deepseek-ai/deepseek-harness/commit/055c505c6))
- test(history): label synthetic timing totals ([86e79b5](https://github.com/deepseek-ai/deepseek-harness/commit/86e79b588))
- test(history): measure end-to-end timing stages ([5171e10](https://github.com/deepseek-ai/deepseek-harness/commit/5171e107e))
- test(web): await completed turn footers ([3511796](https://github.com/deepseek-ai/deepseek-harness/commit/3511796fa))
- test(history): measure packed heap usage ([ea282f5](https://github.com/deepseek-ai/deepseek-harness/commit/ea282f571))
- test(web): hold application batch during boot theme check ([9ee9a32](https://github.com/deepseek-ai/deepseek-harness/commit/9ee9a3270))
- refactor(session-persistence): share stored read machinery ([d4ff836](https://github.com/deepseek-ai/deepseek-harness/commit/d4ff836dc))

### 📝 Documentation
- docs(config): refresh persistence source link ([f73f2d9](https://github.com/deepseek-ai/deepseek-harness/commit/f73f2d9b6))

### 🔧 Configuration
- perf(client-modules): batch startup plugin scripts ([5bbaf16](https://github.com/deepseek-ai/deepseek-harness/commit/5bbaf168d))

## 2026-08-19

**34 commits.** 1 feature changes, 17 fixes.

### 🆕 New Features
- feat(session-projection-cache): store one projection_cache.json per session ([cdb4cc3](https://github.com/deepseek-ai/deepseek-harness/commit/cdb4cc3c6))

### 🐛 Bug Fixes
- fix(team): isolate browser remote adapter ([36588ad](https://github.com/deepseek-ai/deepseek-harness/commit/36588ade2))
- fix(profile): isolate bundle module fallbacks ([fd53e47](https://github.com/deepseek-ai/deepseek-harness/commit/fd53e479b))
- fix(fs): tolerate null editor placeholders ([5c98d5e](https://github.com/deepseek-ai/deepseek-harness/commit/5c98d5ece))
- fix(client-modules): tolerate incomplete source maps ([445de0a](https://github.com/deepseek-ai/deepseek-harness/commit/445de0ab3))
- fix(bundle): mount the projection cache in the base overlay ([a9a51f8](https://github.com/deepseek-ai/deepseek-harness/commit/a9a51f809))
- fix(session-projection-cache): address review — atomic-write reuse, sqlite no-path, ordering and drain ([3f4c5f0](https://github.com/deepseek-ai/deepseek-harness/commit/3f4c5f056))
- fix(session-persistence-jsonl): drop crash-unsafe cross-process log lock ([270a06b](https://github.com/deepseek-ai/deepseek-harness/commit/270a06b38))
- fix(session): scope format registry completeness to per-session decode ([e8f4315](https://github.com/deepseek-ai/deepseek-harness/commit/e8f4315ce))
- fix(session): load legacy compact events ([44feade](https://github.com/deepseek-ai/deepseek-harness/commit/44feadea0))
- fix(session): address format migration review ([c4b3f48](https://github.com/deepseek-ai/deepseek-harness/commit/c4b3f48e6))
- fix(sandbox): preserve all drain failures ([a163f40](https://github.com/deepseek-ai/deepseek-harness/commit/a163f4019))
- fix(sandbox): cancel sibling drain after child termination ([03186fe](https://github.com/deepseek-ai/deepseek-harness/commit/03186fe93))
- fix(sandbox): cancel sibling drain on termination failure ([60587b4](https://github.com/deepseek-ai/deepseek-harness/commit/60587b490))
- fix(sandbox): terminate on first drain failure ([33e90e9](https://github.com/deepseek-ai/deepseek-harness/commit/33e90e991))
- fix(sandbox): contain drain failure settlement ([5375142](https://github.com/deepseek-ai/deepseek-harness/commit/537514282))
- fix(win32-process): close PR1 review gaps ([4a722de](https://github.com/deepseek-ai/deepseek-harness/commit/4a722de4f))
- fix(sandbox): memoize inherited settlement promise ([f1fd304](https://github.com/deepseek-ai/deepseek-harness/commit/f1fd304df))

### 🔄 Refactoring
- refactor: let Team own browser remotes ([61dea35](https://github.com/deepseek-ai/deepseek-harness/commit/61dea35bd))
- refactor(llm): rename CallId to ToolCallId ([a789637](https://github.com/deepseek-ai/deepseek-harness/commit/a789637db))
- test: adapt consumers to the cache's own root tree ([32ed3e2](https://github.com/deepseek-ai/deepseek-harness/commit/32ed3e2bc))
- refactor(session-projection-cache): own the cache tree under a config root ([8932148](https://github.com/deepseek-ai/deepseek-harness/commit/89321489d))
- test(sandbox): remove duplicate failure assertion ([8505d61](https://github.com/deepseek-ai/deepseek-harness/commit/8505d61f6))
- test(sandbox): preserve rejection evidence ([9241ac2](https://github.com/deepseek-ai/deepseek-harness/commit/9241ac22a))
- test(sandbox): keep aggregate failure assertion typed ([f9a264c](https://github.com/deepseek-ai/deepseek-harness/commit/f9a264c76))
- refactor(win32-process): remove redundant suspension ([4f381b8](https://github.com/deepseek-ai/deepseek-harness/commit/4f381b83c))
- refactor(win32-process): narrow PR1 native surface ([ab494bf](https://github.com/deepseek-ai/deepseek-harness/commit/ab494bfdc))
- refactor(win32-process): share native process primitives ([668da7f](https://github.com/deepseek-ai/deepseek-harness/commit/668da7f50))

### 📝 Documentation
- docs: remove implementation narration from prose ([6b3e971](https://github.com/deepseek-ai/deepseek-harness/commit/6b3e97180))
- docs(notes): rename CallId to ToolCallId in agent notes ([aa5bc53](https://github.com/deepseek-ai/deepseek-harness/commit/aa5bc532d))
- docs(session-projection): sync persist removal, cache root, and catalogs ([f62986c](https://github.com/deepseek-ai/deepseek-harness/commit/f62986c01))

### 🔧 Configuration
- ci(windows): exercise ABI probes on failover standby ([4605124](https://github.com/deepseek-ai/deepseek-harness/commit/460512473))
- ci(windows): run ABI probes with MSVC ([5490a5e](https://github.com/deepseek-ai/deepseek-harness/commit/5490a5e07))
- chore(sandbox): align inherited wait lint ([e18564d](https://github.com/deepseek-ai/deepseek-harness/commit/e18564de0))

## 2026-08-20

**48 commits.** 12 feature changes, 15 fixes.

### 🆕 New Features
- fix(ui-workspace): keep blank new sessions outside the fold quota ([9d25fbf](https://github.com/deepseek-ai/deepseek-harness/commit/9d25fbf21))
- ci: add build-preview workflow ([3a47674](https://github.com/deepseek-ai/deepseek-harness/commit/3a4767479))
- feat(web): single-build preview page and its acceptance e2e ([50bfb00](https://github.com/deepseek-ai/deepseek-harness/commit/50bfb0098))
- feat(web): unify served and preview startup behind a boot-ready seam ([fd3112a](https://github.com/deepseek-ai/deepseek-harness/commit/fd3112a23))
- feat(webworker): model-executed shell over nested worker processes ([4779ec9](https://github.com/deepseek-ai/deepseek-harness/commit/4779ec9af))
- feat(webworker): browser worker host runtime and the vfs image packer ([f47b1ec](https://github.com/deepseek-ai/deepseek-harness/commit/f47b1ecac))
- feat(ui-conversation): lexical composer replaces the textarea stack ([b519cb8](https://github.com/deepseek-ai/deepseek-harness/commit/b519cb87b))
- feat(ui-conversation): lexical chip node, projections, span map ([4776151](https://github.com/deepseek-ai/deepseek-harness/commit/477615162))
- chore(ui-conversation): add lexical dependencies and jsdom spike ([2279fd1](https://github.com/deepseek-ai/deepseek-harness/commit/2279fd19b))
- feat(storage-json): one-time migration of a legacy whole-unit file to per-record ([08e546e](https://github.com/deepseek-ai/deepseek-harness/commit/08e546eff))
- feat(session-projection-cache): seed cold reads from the cache and write back ([84db39c](https://github.com/deepseek-ai/deepseek-harness/commit/84db39cec))
- feat(storage): add the per-record layout to the json backend ([501f387](https://github.com/deepseek-ai/deepseek-harness/commit/501f387b4))

### 🐛 Bug Fixes
- fix(team): address Agent Teams Web review ([80e033e](https://github.com/deepseek-ai/deepseek-harness/commit/80e033efe))
- fix(agent-team): isolate generated Remote browser entry ([c6cab2a](https://github.com/deepseek-ai/deepseek-harness/commit/c6cab2aad))
- fix(profile): address Agent Teams CLI review ([2c16c20](https://github.com/deepseek-ai/deepseek-harness/commit/2c16c20d2))
- fix(boot): stabilize profile module fallbacks ([6e4fabd](https://github.com/deepseek-ai/deepseek-harness/commit/6e4fabdc1))
- fix(web): switch running drafts to Send ([e06625d](https://github.com/deepseek-ai/deepseek-harness/commit/e06625d20))
- fix(jsonl): warn when repairing torn tails ([d97e398](https://github.com/deepseek-ai/deepseek-harness/commit/d97e39838))
- fix(cli): derive the shipped agent-preset root per composition ([9820b6a](https://github.com/deepseek-ai/deepseek-harness/commit/9820b6a1e))
- fix(ui-conversation): step across chips without a keyboard-selected state ([c8b4ec7](https://github.com/deepseek-ai/deepseek-harness/commit/c8b4ec73a))
- fix(ui-conversation): address composer review findings ([315fc9b](https://github.com/deepseek-ai/deepseek-harness/commit/315fc9b16))
- fix(session-projection-cache): checkpoint at session creation ([b67761a](https://github.com/deepseek-ai/deepseek-harness/commit/b67761a8a))
- fix(win32-process): close PR1 validation gaps ([7ef1c45](https://github.com/deepseek-ai/deepseek-harness/commit/7ef1c458f))
- fix(session-persistence): repair persistence CI gates ([50ad2ab](https://github.com/deepseek-ai/deepseek-harness/commit/50ad2aba1))
- fix(bundle): promote the storage stack and the projection cache to base ([3a4232a](https://github.com/deepseek-ai/deepseek-harness/commit/3a4232a8f))
- fix(bundle): mount the projection cache in the web-app overlay ([e01c1a4](https://github.com/deepseek-ai/deepseek-harness/commit/e01c1a4b4))
- fix(session-projection-cache): store checkpoints on a per-record storage domain ([1201ecc](https://github.com/deepseek-ai/deepseek-harness/commit/1201ecc82))

### 🔄 Refactoring
- test(ui-conversation): drop an unnecessary type assertion in the chip DOM spec ([8905b0a](https://github.com/deepseek-ai/deepseek-harness/commit/8905b0a19))
- test(sandbox): remove stale export assertion ([85b8484](https://github.com/deepseek-ai/deepseek-harness/commit/85b8484a9))
- test(web): settle the remaining e2e drive gaps ([9b64106](https://github.com/deepseek-ai/deepseek-harness/commit/9b64106e9))
- test(web): null-tolerant textContent length in the perf lane ([504a1c6](https://github.com/deepseek-ai/deepseek-harness/commit/504a1c6f4))
- test(web): finish the e2e migration to the composer surface ([4f80877](https://github.com/deepseek-ai/deepseek-harness/commit/4f808771c))
- test(web): drive the built-graph snapshot lanes through the editor surface ([e920185](https://github.com/deepseek-ai/deepseek-harness/commit/e92018570))
- test(ui-conversation): align suites with the editor composer ([7222b06](https://github.com/deepseek-ai/deepseek-harness/commit/7222b066d))
- refactor(session-projection-cache): restore the base method order ([eb1f167](https://github.com/deepseek-ai/deepseek-harness/commit/eb1f167fa))
- test(win32-process): type handle-order assertions ([1925670](https://github.com/deepseek-ai/deepseek-harness/commit/19256704c))
- refactor(win32-process): restore mechanical extraction ([5b47da0](https://github.com/deepseek-ai/deepseek-harness/commit/5b47da02a))
- test(session-projection-cache): rewrite for the per-record domain medium ([9226d9b](https://github.com/deepseek-ai/deepseek-harness/commit/9226d9bbf))

### 📝 Documentation
- docs: localize a cross-note link in the composer edit-range note ([304b4b8](https://github.com/deepseek-ai/deepseek-harness/commit/304b4b842))
- docs: zh-locale links for the composer note after the master merge ([f908cf4](https://github.com/deepseek-ai/deepseek-harness/commit/f908cf434))
- docs(win32-process): keep localized header link valid ([a536868](https://github.com/deepseek-ai/deepseek-harness/commit/a5368680a))
- docs(win32-process): narrow ABI verification claims ([458ba49](https://github.com/deepseek-ai/deepseek-harness/commit/458ba4981))
- docs(win32-process): point ABI verification to its owner ([ff7a5a0](https://github.com/deepseek-ai/deepseek-harness/commit/ff7a5a042))
- docs+build(ui-conversation): lexical composer collateral ([f6fb66a](https://github.com/deepseek-ai/deepseek-harness/commit/f6fb66a31))
- docs(session-projection-cache): sync catalogs, type-equiv, and event consumers after master merge ([f6080c3](https://github.com/deepseek-ai/deepseek-harness/commit/f6080c375))
- docs(session-projection-cache): sync the per-record domain medium across docs ([07cf16d](https://github.com/deepseek-ai/deepseek-harness/commit/07cf16d57))

### 🔧 Configuration
- chore(gates): regenerate catalogs and keep repository gates green ([3cc9095](https://github.com/deepseek-ai/deepseek-harness/commit/3cc90952c))
- chore(storage-json): exempt the shared unit lifecycle from the duplication gate ([cdb918c](https://github.com/deepseek-ai/deepseek-harness/commit/cdb918c4b))

## 2026-08-21

**85 commits.** 13 feature changes, 31 fixes, including breaking changes.

### ⚠️ Breaking Changes
- test(web): migrate the retry-exhaustion composer wait off the textarea locator ([df0fbbb](https://github.com/deepseek-ai/deepseek-harness/commit/df0fbbb09))

### 🆕 New Features
- feat(ui): adaptive content width and font-size control ([6d6f8f0](https://github.com/deepseek-ai/deepseek-harness/commit/6d6f8f044))
- feat(headless): stream reasoning progress to stderr ([937d2b3](https://github.com/deepseek-ai/deepseek-harness/commit/937d2b351))
- feat(subagent): carry model routing through DSH SDK ([1044db2](https://github.com/deepseek-ai/deepseek-harness/commit/1044db218))
- feat(subagent): configure Codex provider models ([fe8a961](https://github.com/deepseek-ai/deepseek-harness/commit/fe8a96134))
- feat(subagent): configure Claude Code provider models ([a043395](https://github.com/deepseek-ai/deepseek-harness/commit/a043395c2))
- feat: label local build banner ([17bde3f](https://github.com/deepseek-ai/deepseek-harness/commit/17bde3f5b))
- feat(client): show build version in local banner ([65a8d6b](https://github.com/deepseek-ai/deepseek-harness/commit/65a8d6be1))
- feat(attachment): expose model-readable image paths ([bd4e417](https://github.com/deepseek-ai/deepseek-harness/commit/bd4e4173e))
- fix(release): align new package versions with the 0.1.1-rc.2 root ([311aaed](https://github.com/deepseek-ai/deepseek-harness/commit/311aaed2e))
- test: follow the uuid mint to its new entropy seam ([f910e4f](https://github.com/deepseek-ai/deepseek-harness/commit/f910e4f84))
- feat(util): mint UUIDs without crypto.randomUUID in every context ([0bee546](https://github.com/deepseek-ai/deepseek-harness/commit/0bee54617))
- feat(webworker): name packed modules and client bundles for the debugger ([99db143](https://github.com/deepseek-ai/deepseek-harness/commit/99db143e3))
- docs: add documentation website link ([6ef68c3](https://github.com/deepseek-ai/deepseek-harness/commit/6ef68c3b9))

### 🐛 Bug Fixes
- fix(headless): make stream chunk handling exhaustive ([3a9820c](https://github.com/deepseek-ai/deepseek-harness/commit/3a9820c8c))
- fix(headless): preserve reasoning block continuity ([2813ef2](https://github.com/deepseek-ai/deepseek-harness/commit/2813ef2a9))
- fix(sdk): gate prompts on route initialization ([9a6c94c](https://github.com/deepseek-ai/deepseek-harness/commit/9a6c94cb2))
- fix(subagent): narrow provider route defaults ([57eba43](https://github.com/deepseek-ai/deepseek-harness/commit/57eba4341))
- fix(subagent): bind preflight to provider route defaults ([096ae14](https://github.com/deepseek-ai/deepseek-harness/commit/096ae14db))
- fix(subagent): resolve DSH defaults before preflight ([3c79979](https://github.com/deepseek-ai/deepseek-harness/commit/3c79979d1))
- review fix: align Codex policy evidence ([d495089](https://github.com/deepseek-ai/deepseek-harness/commit/d495089ff))
- review fix: tighten Codex failure ownership ([e2315e3](https://github.com/deepseek-ai/deepseek-harness/commit/e2315e3b1))
- review fix: simplify Claude diagnostic evidence ([7d30a39](https://github.com/deepseek-ai/deepseek-harness/commit/7d30a3961))
- fix: sample dev web metadata at startup ([749c4ef](https://github.com/deepseek-ai/deepseek-harness/commit/749c4ef93))
- fix(session): remove unreachable listing branch ([95ed302](https://github.com/deepseek-ai/deepseek-harness/commit/95ed302c9))
- fix(util): mint the pinned uuid bytes without dead fallback branches ([4e69370](https://github.com/deepseek-ai/deepseek-harness/commit/4e6937064))
- fix(lint): clear contracts-ready findings in the mode-model batch ([86357f5](https://github.com/deepseek-ai/deepseek-harness/commit/86357f5f0))
- fix(webworker): store and honour VFS permission bits ([c2a30af](https://github.com/deepseek-ai/deepseek-harness/commit/c2a30af92))
- fix: loopback ([8081620](https://github.com/deepseek-ai/deepseek-harness/commit/8081620a3))
- fix(session): address migration review feedback ([7e3d533](https://github.com/deepseek-ai/deepseek-harness/commit/7e3d5332d))
- fix(tests): complete ToolCallId rename ([82c3446](https://github.com/deepseek-ai/deepseek-harness/commit/82c34463f))
- fix(ui-conversation): restore the folder glyph on composer folder references ([73792a8](https://github.com/deepseek-ai/deepseek-harness/commit/73792a81b))
- fix(web): project sent user text inline and fold wire references in queue rows ([339a120](https://github.com/deepseek-ai/deepseek-harness/commit/339a12030))
- docs: revert spurious BRAND-GUIDELINES.md change from master merge ([a693e07](https://github.com/deepseek-ai/deepseek-harness/commit/a693e0764))
- fix(cic): narrow workflow.on before Object.keys in python-release assertion ([ae193bf](https://github.com/deepseek-ai/deepseek-harness/commit/ae193bfc0))
- fix(cic): re-record development pair and tighten python-release spec assertion ([374f3cd](https://github.com/deepseek-ai/deepseek-harness/commit/374f3cdb0))
- fix(docs): correct zh locale link in composer-edit-range note ([cb5b762](https://github.com/deepseek-ai/deepseek-harness/commit/cb5b76292))
- fix(sdk): validate closed turn cancellation facts ([ba0d7df](https://github.com/deepseek-ai/deepseek-harness/commit/ba0d7dfdc))
- fix(subagent): keep ACP failure observation cancellable ([2a060ad](https://github.com/deepseek-ai/deepseek-harness/commit/2a060adfa))
- fix(subagent): close DSH SDK diagnostic review gaps ([bbf1c6e](https://github.com/deepseek-ai/deepseek-harness/commit/bbf1c6e84))
- fix(subagent): align ACP diagnostic lifecycle facts ([67e038a](https://github.com/deepseek-ai/deepseek-harness/commit/67e038ab3))
- fix(subagent): align DSH SDK diagnostics with reachable facts ([659749d](https://github.com/deepseek-ai/deepseek-harness/commit/659749dc0))
- fix(subagent): preserve actionable DSH SDK failure facts ([b88a35d](https://github.com/deepseek-ai/deepseek-harness/commit/b88a35d50))
- fix(subagent): close ACP diagnostic review gaps ([dfb3608](https://github.com/deepseek-ai/deepseek-harness/commit/dfb36080d))
- fix(subagent): preserve actionable ACP failure facts ([5c27df5](https://github.com/deepseek-ai/deepseek-harness/commit/5c27df5ed))

### 🔄 Refactoring
- test: simplify DSH SDK route evidence ([54e908d](https://github.com/deepseek-ai/deepseek-harness/commit/54e908df5))
- test(snapshot): stabilize DSH SDK route usage ([40f6205](https://github.com/deepseek-ai/deepseek-harness/commit/40f6205cd))
- test(subagent): cover Claude limit subtypes ([f76cce2](https://github.com/deepseek-ai/deepseek-harness/commit/f76cce2fc))
- test: update client build fixtures ([b636b01](https://github.com/deepseek-ai/deepseek-harness/commit/b636b0109))
- test(webworker): narrow the stat shape in the mode round-trip spec ([6811e44](https://github.com/deepseek-ai/deepseek-harness/commit/6811e4430))
- refactor(session-persistence): make format migrations one-to-one ([2da0004](https://github.com/deepseek-ai/deepseek-harness/commit/2da00047f))
- refactor(preset): bundle the shipped presets inside dsh-agent-presets ([f94495e](https://github.com/deepseek-ai/deepseek-harness/commit/f94495e52))
- ci(windows): raise native coverage test timeout to 60s ([a633c19](https://github.com/deepseek-ai/deepseek-harness/commit/a633c19b0))
- refactor(python): drop now-always-true build.if ([7214d0d](https://github.com/deepseek-ai/deepseek-harness/commit/7214d0d95))
- refactor(apiproxy): restore the single-line listProjectionsFor signature ([bb3105d](https://github.com/deepseek-ai/deepseek-harness/commit/bb3105d7b))
- test(storage-json): reach the unreadable-record branch on every platform ([87c01d9](https://github.com/deepseek-ai/deepseek-harness/commit/87c01d996))
- test(storage): harden windows-native teardown and chmod probe ([8baa987](https://github.com/deepseek-ai/deepseek-harness/commit/8baa98738))
- test(web): seed cold subagent fixtures through the per-record cache ([1134c2a](https://github.com/deepseek-ai/deepseek-harness/commit/1134c2a98))
- refactor(subagent): observe ACP direct process outcome ([8dc7852](https://github.com/deepseek-ai/deepseek-harness/commit/8dc785288))
- refactor(subagent): drop unused ACP cancel classification ([0dcb514](https://github.com/deepseek-ai/deepseek-harness/commit/0dcb514fc))
- test(subagent): type blocked SDK outcomes precisely ([1c5305c](https://github.com/deepseek-ai/deepseek-harness/commit/1c5305ca2))
- refactor(subagent): keep ACP permission diagnostics minimal ([5e1494f](https://github.com/deepseek-ai/deepseek-harness/commit/5e1494ff1))
- test(subagent): stabilize DSH SDK background snapshot ([ee50ee0](https://github.com/deepseek-ai/deepseek-harness/commit/ee50ee088))
- test(subagent): align ACP permission snapshot ([d6de6bb](https://github.com/deepseek-ai/deepseek-harness/commit/d6de6bb0c))

### 📝 Documentation
- docs(team): link deferred Web preset work ([8852161](https://github.com/deepseek-ai/deepseek-harness/commit/885216166))
- docs(subagent): include product policy diagnostics ([97e3a17](https://github.com/deepseek-ai/deepseek-harness/commit/97e3a175f))
- docs(subagent): align Codex permission evidence ([bd65770](https://github.com/deepseek-ai/deepseek-harness/commit/bd6577072))
- docs(subagent): describe Host-only stderr flow ([7c62fa1](https://github.com/deepseek-ai/deepseek-harness/commit/7c62fa127))
- ci: put the preview-comment marker on its own line ([54b05a8](https://github.com/deepseek-ai/deepseek-harness/commit/54b05a8dc))
- docs(cli): sync the derived preset-root layer into launcher docs ([25058f2](https://github.com/deepseek-ai/deepseek-harness/commit/25058f265))
- docs(session-projection): apply master's locale link fixes after merge ([4760c40](https://github.com/deepseek-ai/deepseek-harness/commit/4760c40e8))
- docs(subagent): clarify diagnostic-bearing results ([b9cbcf8](https://github.com/deepseek-ai/deepseek-harness/commit/b9cbcf8e2))
- docs(subagent): name SDK quiescence precisely ([aaa85cc](https://github.com/deepseek-ai/deepseek-harness/commit/aaa85cce0))
- docs(subagent): name ACP quiescence precisely ([9a6f5cf](https://github.com/deepseek-ai/deepseek-harness/commit/9a6f5cf7f))
- docs(subagent): distinguish cancelled SDK cleanup ([30cd11e](https://github.com/deepseek-ai/deepseek-harness/commit/30cd11e69))
- docs(subagent): distinguish cancelled cleanup failure ([3900de2](https://github.com/deepseek-ai/deepseek-harness/commit/3900de296))
- docs(subagent): qualify ACP cleanup failure ([d90003b](https://github.com/deepseek-ai/deepseek-harness/commit/d90003b4e))
- docs(config): refresh ACP process grace catalog ([075108d](https://github.com/deepseek-ai/deepseek-harness/commit/075108dc0))
- docs(subagent): qualify startup cleanup outcomes ([75b8eb0](https://github.com/deepseek-ai/deepseek-harness/commit/75b8eb08b))
- docs: refresh DSH SDK config catalog pair ([569bf3e](https://github.com/deepseek-ai/deepseek-harness/commit/569bf3e5e))

### 🔧 Configuration
- perf(session-projection): index contiguous restore tails ([265f02f](https://github.com/deepseek-ai/deepseek-harness/commit/265f02fbf))
- perf(session-projection): avoid restore tail copies ([a216756](https://github.com/deepseek-ai/deepseek-harness/commit/a21675622))
- chore(rescope): realign two manifest anchors, allowlist the preset-id spec ([c365daa](https://github.com/deepseek-ai/deepseek-harness/commit/c365daa53))
- chore(constraints): register the preset-root files policy ([d858832](https://github.com/deepseek-ai/deepseek-harness/commit/d858832bb))
- ci(python): drop PR labeled trigger for python-release dry-run ([499c126](https://github.com/deepseek-ai/deepseek-harness/commit/499c1262a))

## 2026-08-22

**53 commits.** 9 feature changes, 5 fixes, including breaking changes.

### ⚠️ Breaking Changes
- refactor(client): migrate consumers and remove Runtime ([be53168](https://github.com/deepseek-ai/deepseek-harness/commit/be531688f))

### 🆕 New Features
- refactor(ui): add Session and Workspace React adapters ([d231c87](https://github.com/deepseek-ai/deepseek-harness/commit/d231c8777))
- feat(api-gateway): unify Remote streams and events ([3d6d595](https://github.com/deepseek-ai/deepseek-harness/commit/3d6d595d7))
- feat(webhook): create workspace sessions from GitHub events ([5f60e50](https://github.com/deepseek-ai/deepseek-harness/commit/5f60e50d7))
- feat(deepseek): apply session upload review feedback ([1c7af99](https://github.com/deepseek-ai/deepseek-harness/commit/1c7af99c8))
- feat(deepseek): upload incremental session logs ([fe72ab4](https://github.com/deepseek-ai/deepseek-harness/commit/fe72ab42d))
- docs(todo): add the owning subsystem reference ([851eab7](https://github.com/deepseek-ai/deepseek-harness/commit/851eab756))
- feat(acp): complete standard v1 automation controls ([f39af7b](https://github.com/deepseek-ai/deepseek-harness/commit/f39af7bae), [5111816](https://github.com/deepseek-ai/deepseek-harness/commit/511181684))
- feat(deepseek): upload plugin package metadata ([ea6f61f](https://github.com/deepseek-ai/deepseek-harness/commit/ea6f61f14))

### 🐛 Bug Fixes
- fix(api-session): bind history pages to follow cursor ([e8ede58](https://github.com/deepseek-ai/deepseek-harness/commit/e8ede5860))
- fix(todo): validate announced session histories ([b7dca9e](https://github.com/deepseek-ai/deepseek-harness/commit/b7dca9eb7))
- fix(test): publish lint probes atomically ([35f2669](https://github.com/deepseek-ai/deepseek-harness/commit/35f26699b))
- fix(ci): harden optimized Windows gate fixtures ([811788e](https://github.com/deepseek-ai/deepseek-harness/commit/811788e57))
- fix(acp): address lifecycle review findings ([52bd3e1](https://github.com/deepseek-ai/deepseek-harness/commit/52bd3e180))

### 🔄 Refactoring
- refactor(interaction): move Approval and Question into UI owners ([049170c](https://github.com/deepseek-ai/deepseek-harness/commit/049170c6d))
- refactor(conversation): separate Conversation, Chat, and Trajectory owners ([c7d8e32](https://github.com/deepseek-ai/deepseek-harness/commit/c7d8e32ae))
- refactor(client): extract Store and renderer Slot infrastructure ([1b535f6](https://github.com/deepseek-ai/deepseek-harness/commit/1b535f611))
- refactor(workspace): move Client ownership into Workspace Controller ([0ea9a45](https://github.com/deepseek-ai/deepseek-harness/commit/0ea9a456c))
- refactor(session): move Client ownership into Session Controller ([956730a](https://github.com/deepseek-ai/deepseek-harness/commit/956730a5f))
- refactor(client): replace legacy Host event carriers ([dcddaa1](https://github.com/deepseek-ai/deepseek-harness/commit/dcddaa1a6))
- refactor(workspace): move APIs into Workspace Controller ([ae25df3](https://github.com/deepseek-ai/deepseek-harness/commit/ae25df3ac))
- refactor(session): move APIs into Session Controller ([d26acfa](https://github.com/deepseek-ai/deepseek-harness/commit/d26acfa2e))
- refactor(session): name delivery acceptance event ([3c0da7b](https://github.com/deepseek-ai/deepseek-harness/commit/3c0da7bef))
- refactor(todo): own todo event vocabulary ([a2b4150](https://github.com/deepseek-ai/deepseek-harness/commit/a2b415096))
- perf(test): widen transform corpus sharding ([d39b6c6](https://github.com/deepseek-ai/deepseek-harness/commit/d39b6c638))
- perf(test): shard the transform corpus checker ([d27a5f2](https://github.com/deepseek-ai/deepseek-harness/commit/d27a5f296))
- test(acp): align assembled automation coverage ([e37985f](https://github.com/deepseek-ai/deepseek-harness/commit/e37985f5d))
- test(ci): apply review feedback ([1d6f84f](https://github.com/deepseek-ai/deepseek-harness/commit/1d6f84ff4))
- test(ci): stabilize cross-platform gate baselines ([b9869d1](https://github.com/deepseek-ai/deepseek-harness/commit/b9869d1e9))

### 📝 Documentation
- docs(client): document split ownership ([f13fb4d](https://github.com/deepseek-ai/deepseek-harness/commit/f13fb4dae))
- docs: document controller Remote transport ([9b1069c](https://github.com/deepseek-ai/deepseek-harness/commit/9b1069c23))
- docs(deepseek): merge todo event graph updates ([e0a8050](https://github.com/deepseek-ai/deepseek-harness/commit/e0a8050ae))
- docs(deepseek): specify session log wire format ([8ac8245](https://github.com/deepseek-ai/deepseek-harness/commit/8ac8245d3))
- docs(session): refresh persistence pairing record ([65295d5](https://github.com/deepseek-ai/deepseek-harness/commit/65295d5b6))
- docs(todo): record event ownership ([59e4945](https://github.com/deepseek-ai/deepseek-harness/commit/59e49458e))
- docs: remove rebase residue and hedge parser-swap regression ([f964f40](https://github.com/deepseek-ai/deepseek-harness/commit/f964f4078))
- docs: address CoT review findings ([750c7f7](https://github.com/deepseek-ai/deepseek-harness/commit/750c7f753))
- docs: trim CoT leakage from post-purge prose ([17f85bd](https://github.com/deepseek-ai/deepseek-harness/commit/17f85bdbc))
- docs(acp): explain empty-session durability ([e0a700b](https://github.com/deepseek-ai/deepseek-harness/commit/e0a700baf))
- docs: synchronize module graph pair ([696ec48](https://github.com/deepseek-ai/deepseek-harness/commit/696ec4880))
- docs: refresh ACP module graph ([28c93d8](https://github.com/deepseek-ai/deepseek-harness/commit/28c93d822))
- docs(notes): archive low-value records ([198c6c5](https://github.com/deepseek-ai/deepseek-harness/commit/198c6c595))
- docs: address leakage audit review ([7f93f65](https://github.com/deepseek-ai/deepseek-harness/commit/7f93f65ca))
- docs: harden chain-of-thought leakage audits ([d72ff1f](https://github.com/deepseek-ai/deepseek-harness/commit/d72ff1f49))
- docs: purge residual chain-of-thought leakage ([9349767](https://github.com/deepseek-ai/deepseek-harness/commit/934976732))

### 🔧 Configuration
- chore(client): align split package graph ([3a23185](https://github.com/deepseek-ai/deepseek-harness/commit/3a23185ed))
- chore(api): align controller assembly and package graph ([54d739c](https://github.com/deepseek-ai/deepseek-harness/commit/54d739cf5))
- ci: require native Windows aggregate verdict ([c92c864](https://github.com/deepseek-ai/deepseek-harness/commit/c92c86492))
- perf(ci): raise isolated Windows coverage fan-out ([c8cecd6](https://github.com/deepseek-ai/deepseek-harness/commit/c8cecd607))
- perf(ci): phase native Windows coverage work ([12ad38b](https://github.com/deepseek-ai/deepseek-harness/commit/12ad38b23))
- perf(ci): isolate the transform corpus from coverage ([4edf640](https://github.com/deepseek-ai/deepseek-harness/commit/4edf6400f))
- ci: raise host TypeScript heap budget ([3d660d2](https://github.com/deepseek-ai/deepseek-harness/commit/3d660d2db))

## 2026-08-23

**124 commits.** 12 feature changes, 42 fixes.

### 🆕 New Features
- feat(locale): allow external language registration ([bbe00b0](https://github.com/deepseek-ai/deepseek-harness/commit/bbe00b0db))
- feat(python-example): select the persistent shell by platform ([2844233](https://github.com/deepseek-ai/deepseek-harness/commit/28442337c))
- feat(python-runtime): package the Windows x64 dsh executable ([ca0b216](https://github.com/deepseek-ai/deepseek-harness/commit/ca0b21661))
- feat(python-sdk): launch dsh profiles from explicit homes ([56e038b](https://github.com/deepseek-ai/deepseek-harness/commit/56e038b2e))
- feat(python-runtime): package the dsh CLI and profile assets ([be7b064](https://github.com/deepseek-ai/deepseek-harness/commit/be7b06450))
- feat(webworker): add selectable preview fixtures ([e883dc2](https://github.com/deepseek-ai/deepseek-harness/commit/e883dc235))
- feat(webworker): support fs watches and confinement ([8fe9af8](https://github.com/deepseek-ai/deepseek-harness/commit/8fe9af8db))
- feat(util): add workspace path helpers ([64bb042](https://github.com/deepseek-ai/deepseek-harness/commit/64bb0427f))
- feat(sdk): launch TypeScript clients through dsh profiles ([3368ddc](https://github.com/deepseek-ai/deepseek-harness/commit/3368ddc0a))
- feat(profiles): add the ACP application bundle ([47a46e4](https://github.com/deepseek-ai/deepseek-harness/commit/47a46e4cc))
- feat(profiles): add the SDK application bundle ([a168229](https://github.com/deepseek-ai/deepseek-harness/commit/a16822944))
- feat(cli): make profile patch reload policy explicit ([2c9da6e](https://github.com/deepseek-ai/deepseek-harness/commit/2c9da6eb5))

### 🐛 Bug Fixes
- fix(locale): validate contributed language tags ([45b9f2d](https://github.com/deepseek-ai/deepseek-harness/commit/45b9f2db4))
- fix(python): make Windows release paths native ([8101a0d](https://github.com/deepseek-ai/deepseek-harness/commit/8101a0d09))
- fix(python-sdk): resolve packaged proxies from real module entries ([d801f26](https://github.com/deepseek-ai/deepseek-harness/commit/d801f262d))
- fix(python-sdk): harden profile runtime startup ([9edf1b9](https://github.com/deepseek-ai/deepseek-harness/commit/9edf1b9f1))
- fix(app-boot): preserve profile modules inside pkg executables ([809a4c5](https://github.com/deepseek-ai/deepseek-harness/commit/809a4c5ba))
- fix(webworker): preserve preview loading sequence ([4f80422](https://github.com/deepseek-ai/deepseek-harness/commit/4f8042259))
- fix(webworker): match preview chooser styling ([14bd300](https://github.com/deepseek-ai/deepseek-harness/commit/14bd30088))
- fix(client): validate exact external specifiers ([b19752f](https://github.com/deepseek-ai/deepseek-harness/commit/b19752fda))
- fix(client): gate the inspect catalog ([a050b3d](https://github.com/deepseek-ai/deepseek-harness/commit/a050b3d4f))
- fix(ci): preserve cross-platform lint suppressions ([2a72de6](https://github.com/deepseek-ai/deepseek-harness/commit/2a72de67d))
- fix(client): address localization review findings ([ac4ade3](https://github.com/deepseek-ai/deepseek-harness/commit/ac4ade3aa))
- fix(client): satisfy UI localization CI gates ([e1a5942](https://github.com/deepseek-ai/deepseek-harness/commit/e1a5942c9))
- fix(terminal-bash): handle terminal protocol replies ([4f3a47d](https://github.com/deepseek-ai/deepseek-harness/commit/4f3a47d79))
- fix(client): route UI copy through locale ([3c10f5d](https://github.com/deepseek-ai/deepseek-harness/commit/3c10f5d2d))
- fix(client): settle interactions during plugin teardown ([7402ce3](https://github.com/deepseek-ai/deepseek-harness/commit/7402ce3fc))
- fix(client): keep conversation updates incremental ([6896444](https://github.com/deepseek-ai/deepseek-harness/commit/689644463))
- fix(client): preserve scoped UI lifecycles ([a40f30a](https://github.com/deepseek-ai/deepseek-harness/commit/a40f30a4a))
- fix(client): restore injected workspace dependencies ([956a72f](https://github.com/deepseek-ai/deepseek-harness/commit/956a72ffe))
- fix(client): remove unused workspace dev dependencies ([7ddccac](https://github.com/deepseek-ai/deepseek-harness/commit/7ddccac0d))
- fix(client): avoid cyclic UI service type imports ([828cd3f](https://github.com/deepseek-ai/deepseek-harness/commit/828cd3f7b))
- fix(client): align domain split with repository gates ([dc92793](https://github.com/deepseek-ai/deepseek-harness/commit/dc92793f1))
- fix(api-session): preserve presenter fast path ([4326dd4](https://github.com/deepseek-ai/deepseek-harness/commit/4326dd4bc))
- fix: skip get proxy ([d34be03](https://github.com/deepseek-ai/deepseek-harness/commit/d34be03f7))
- fix(api): preserve migrated transport semantics ([24a610d](https://github.com/deepseek-ai/deepseek-harness/commit/24a610db7))
- fix(client): materialize Agent scopes before list baseline ([18cf84d](https://github.com/deepseek-ai/deepseek-harness/commit/18cf84d13))
- fix(client): satisfy stream lifecycle contracts ([e38982a](https://github.com/deepseek-ai/deepseek-harness/commit/e38982adc))
- fix(user-questions): bridge scoped request events ([9eb3747](https://github.com/deepseek-ai/deepseek-harness/commit/9eb3747ff))
- fix(interaction): type Agent-scoped request events ([016be7d](https://github.com/deepseek-ai/deepseek-harness/commit/016be7d53))
- fix(client-runtime): close journals with session scopes ([9ff067d](https://github.com/deepseek-ai/deepseek-harness/commit/9ff067dfb))
- fix(client-connection): release stream ownership on unload ([2b2a45f](https://github.com/deepseek-ai/deepseek-harness/commit/2b2a45f30))
- fix(api-gateway): retry journal pages after reconnect ([5d17b67](https://github.com/deepseek-ai/deepseek-harness/commit/5d17b6798))
- fix(user-questions): normalize in-flight aborts ([7f908c1](https://github.com/deepseek-ai/deepseek-harness/commit/7f908c1bb))
- docs(agent-notes): record the Win32 UTF-16 NUL-scan fix ([56f0297](https://github.com/deepseek-ai/deepseek-harness/commit/56f029732))
- test(webhook): resolve the real CLI rule from examples ([65509a2](https://github.com/deepseek-ai/deepseek-harness/commit/65509a225))
- docs(app-boot): clarify patch path anchoring ([76a4505](https://github.com/deepseek-ai/deepseek-harness/commit/76a450529))
- fix(webhook-github): export provider event types ([2f56345](https://github.com/deepseek-ai/deepseek-harness/commit/2f5634543))
- fix(webhook): quiet expected disposal cancellation ([bf23f59](https://github.com/deepseek-ai/deepseek-harness/commit/bf23f5997))
- fix(webhook): preserve the initial model selection ([ea3d0ff](https://github.com/deepseek-ai/deepseek-harness/commit/ea3d0ffce))
- fix(ci): give Wine Host compiler sufficient heap ([d06f544](https://github.com/deepseek-ai/deepseek-harness/commit/d06f544d8))
- fix(build): raise host compiler heap ceiling ([9cd3830](https://github.com/deepseek-ai/deepseek-harness/commit/9cd383059))
- fix(webhook): retain checked invariant installer ([01258a6](https://github.com/deepseek-ai/deepseek-harness/commit/01258a6bc))
- fix(webhook): align patch-relative fixtures and invariants ([a1455ed](https://github.com/deepseek-ai/deepseek-harness/commit/a1455edeb))

### 🔄 Refactoring
- test(python): prove installed dsh profile customization ([01da043](https://github.com/deepseek-ai/deepseek-harness/commit/01da04373))
- refactor(python): remove the private direct-config carrier ([1d4dcf3](https://github.com/deepseek-ai/deepseek-harness/commit/1d4dcf3b5))
- refactor(client): derive deliverables from mutation calls ([a99516c](https://github.com/deepseek-ai/deepseek-harness/commit/a99516c33))
- refactor(client): derive tool cards from raw events ([a4c296f](https://github.com/deepseek-ai/deepseek-harness/commit/a4c296f9f))
- refactor(session): stream raw tool events ([a42c0b5](https://github.com/deepseek-ai/deepseek-harness/commit/a42c0b523))
- test(pwsh): allow Windows shell restart latency ([2a597be](https://github.com/deepseek-ai/deepseek-harness/commit/2a597bea8))
- test(ci): include inspect catalog in gate order ([cad09db](https://github.com/deepseek-ai/deepseek-harness/commit/cad09dbcb))
- test(client): update bundle purity expectation ([efda53c](https://github.com/deepseek-ai/deepseek-harness/commit/efda53c18))
- test(cordis): refresh inspect catalog snapshot ([177142a](https://github.com/deepseek-ai/deepseek-harness/commit/177142aa4))
- refactor(util): remove unreachable path fallback ([3e9c5d1](https://github.com/deepseek-ai/deepseek-harness/commit/3e9c5d1bc))
- test(client): cover malformed browse errors ([e791147](https://github.com/deepseek-ai/deepseek-harness/commit/e79114720))
- refactor(session): localize token delta detection ([e47c897](https://github.com/deepseek-ai/deepseek-harness/commit/e47c897f5))
- refactor(client): remove compatibility imports ([997ad27](https://github.com/deepseek-ai/deepseek-harness/commit/997ad27a6))
- refactor(client): keep feature helpers with consumers ([3d1c0af](https://github.com/deepseek-ai/deepseek-harness/commit/3d1c0af60))
- refactor(client): localize conversation projections ([9f2f498](https://github.com/deepseek-ai/deepseek-harness/commit/9f2f498e7))
- refactor(client): move shared primitives to static packages ([85427ae](https://github.com/deepseek-ai/deepseek-harness/commit/85427aea9))
- test(sandbox): derive packed workspace closure ([b6b08be](https://github.com/deepseek-ai/deepseek-harness/commit/b6b08beb0))
- test(python): gate installed runtime wheels across release targets ([3c1c6a8](https://github.com/deepseek-ai/deepseek-harness/commit/3c1c6a89b))
- fixup! refactor(interaction): move Approval and Question into UI owners ([0b6269b](https://github.com/deepseek-ai/deepseek-harness/commit/0b6269b50), [55dd632](https://github.com/deepseek-ai/deepseek-harness/commit/55dd6320d))
- test(web): tolerate responsive transcript reflow ([291a438](https://github.com/deepseek-ai/deepseek-harness/commit/291a43819))
- test: ignore defensive Remote branches ([8f919cb](https://github.com/deepseek-ai/deepseek-harness/commit/8f919cb9a))
- test(web): avoid unstable subagent hover ([4ebd9fa](https://github.com/deepseek-ai/deepseek-harness/commit/4ebd9fad7))
- test(client): cover reconnect and question scope paths ([3728c0b](https://github.com/deepseek-ai/deepseek-harness/commit/3728c0b13))
- test(api): close stream transport coverage gaps ([ddcab34](https://github.com/deepseek-ai/deepseek-harness/commit/ddcab34c0))
- refactor(client): move pending interactions out of Session state ([f494cac](https://github.com/deepseek-ai/deepseek-harness/commit/f494caca4))
- test(api-session): bind history probes to follow cursors ([30f43b9](https://github.com/deepseek-ai/deepseek-harness/commit/30f43b987))
- test(api-gateway): cover clientless Remote event replay ([7d21611](https://github.com/deepseek-ai/deepseek-harness/commit/7d2161139))
- refactor(client-runtime): remove Session interaction consumers ([1e0e827](https://github.com/deepseek-ai/deepseek-harness/commit/1e0e82742))
- refactor(api-session): remove interaction transport ([639dcef](https://github.com/deepseek-ai/deepseek-harness/commit/639dcef5d))
- test(docs): use a block cleanup callback ([1d46946](https://github.com/deepseek-ai/deepseek-harness/commit/1d4694696))
- test(docs): avoid duplicate fixture cleanup ([9793858](https://github.com/deepseek-ai/deepseek-harness/commit/97938582e))
- refactor(profiles): make module HMR opt-in ([fd81458](https://github.com/deepseek-ai/deepseek-harness/commit/fd814589f))
- test: refresh profile migration catalogs and built smokes ([fdac6cf](https://github.com/deepseek-ai/deepseek-harness/commit/fdac6cffc))
- refactor(sdk): name the private Python runtime carrier explicitly ([a6447db](https://github.com/deepseek-ai/deepseek-harness/commit/a6447db01))
- test(sdk): refresh dsh-profile SDK transcripts ([189e7b8](https://github.com/deepseek-ai/deepseek-harness/commit/189e7b84e))
- refactor(sdk): relocate JSON-RPC example and runtime without edits ([f3402ef](https://github.com/deepseek-ai/deepseek-harness/commit/f3402eff5))
- test(acp): refresh profile-launched application transcripts ([d52f290](https://github.com/deepseek-ai/deepseek-harness/commit/d52f2900d))
- refactor(acp): launch automation through the dsh acp profile ([d8dbb82](https://github.com/deepseek-ai/deepseek-harness/commit/d8dbb8235))
- refactor(acp): relocate control-surface fixtures without edits ([713b41a](https://github.com/deepseek-ai/deepseek-harness/commit/713b41a94))
- test(webhook): preserve real e2e environment ([c5311d6](https://github.com/deepseek-ai/deepseek-harness/commit/c5311d665))
- test(webhook): exercise the real CLI and model flow ([3bf5edb](https://github.com/deepseek-ai/deepseek-harness/commit/3bf5edb5d))
- test(webhook-github): verify chunked overflow response ([2b2a8e8](https://github.com/deepseek-ai/deepseek-harness/commit/2b2a8e824))
- refactor(session): send canonical events directly ([9c7e142](https://github.com/deepseek-ai/deepseek-harness/commit/9c7e142f7))

### 📝 Documentation
- docs(locale): define extensible language fallbacks ([9d61ab6](https://github.com/deepseek-ai/deepseek-harness/commit/9d61ab675))
- docs(python): define the Windows x64 runtime contract ([d4a63ab](https://github.com/deepseek-ai/deepseek-harness/commit/d4a63abe8))
- docs(python): make the dsh profile runtime current ([f0f9b29](https://github.com/deepseek-ai/deepseek-harness/commit/f0f9b294d))
- docs(webworker): define the preview example seed ([181a0e1](https://github.com/deepseek-ai/deepseek-harness/commit/181a0e18e))
- docs: define client-derived tool presentation ([64c9e4a](https://github.com/deepseek-ai/deepseek-harness/commit/64c9e4a22))
- docs(client): restore boundary rationale ([d7db423](https://github.com/deepseek-ai/deepseek-harness/commit/d7db423d5))
- docs: refresh module dependency graph ([39ebc86](https://github.com/deepseek-ai/deepseek-harness/commit/39ebc860d))
- docs(client): align split ownership contracts ([61ee176](https://github.com/deepseek-ai/deepseek-harness/commit/61ee17697))
- fixup! docs(client): document split ownership ([f5767ba](https://github.com/deepseek-ai/deepseek-harness/commit/f5767ba15))
- docs(typert): sync Gateway type excerpt ([c5efa5c](https://github.com/deepseek-ai/deepseek-harness/commit/c5efa5ce9))
- docs(typert): refresh Remote output contract ([d020f60](https://github.com/deepseek-ai/deepseek-harness/commit/d020f6091))
- docs: refresh module graph after rebase ([d319a07](https://github.com/deepseek-ai/deepseek-harness/commit/d319a0773))
- docs: refresh generated client metadata ([6a3f35e](https://github.com/deepseek-ai/deepseek-harness/commit/6a3f35e24))
- docs: refresh module graph ([003fc02](https://github.com/deepseek-ai/deepseek-harness/commit/003fc024c))
- docs: synchronize controller transport documentation ([a49b265](https://github.com/deepseek-ai/deepseek-harness/commit/a49b265f8))
- docs: define dsh as the sole Node application launcher ([3fa19b3](https://github.com/deepseek-ai/deepseek-harness/commit/3fa19b3b3))

### 🔧 Configuration
- ci(python): gate the Windows x64 installed wheel ([026a37f](https://github.com/deepseek-ai/deepseek-harness/commit/026a37fc0))
- chore(client): enforce value dependency policy ([d80419f](https://github.com/deepseek-ai/deepseek-harness/commit/d80419f4e))
- chore(client): remove feature module externals ([81c922c](https://github.com/deepseek-ai/deepseek-harness/commit/81c922c7b))
- chore(client): mark mirrored interaction lifecycle ([e4fb885](https://github.com/deepseek-ai/deepseek-harness/commit/e4fb885f3))
- perf(api-gateway): skip Remote output decoding ([2d974b1](https://github.com/deepseek-ai/deepseek-harness/commit/2d974b187))
- perf(api-session): reuse live tool call arguments ([08d6a21](https://github.com/deepseek-ai/deepseek-harness/commit/08d6a215c))
- chore: remove OpenAI skill metadata ([8c420de](https://github.com/deepseek-ai/deepseek-harness/commit/8c420de30))
- ci: bound profile e2e subprocess fan-out ([2eea02d](https://github.com/deepseek-ai/deepseek-harness/commit/2eea02dae))
- chore(repo): wire profile apps and the renamed runtime through builds ([32c3293](https://github.com/deepseek-ai/deepseek-harness/commit/32c32932f))
- chore(repo): enforce dsh as the only Node application launcher ([3b33ca0](https://github.com/deepseek-ai/deepseek-harness/commit/3b33ca058))

## 2026-08-24

**117 commits.** 7 feature changes, 46 fixes.

### 🆕 New Features
- feat(subagent): authorize selectable child models ([aefc083](https://github.com/deepseek-ai/deepseek-harness/commit/aefc083be))
- feat(client): use bounded plugin combo URLs ([83463aa](https://github.com/deepseek-ai/deepseek-harness/commit/83463aa89))
- feat(llm): 在 compaction 中按路由为图片请求压力计价 ([4216450](https://github.com/deepseek-ai/deepseek-harness/commit/42164508c))
- feat(web): 在 Trajectory 中展示图片附件 ([c27de59](https://github.com/deepseek-ai/deepseek-harness/commit/c27de594f))
- feat(bundle): ship the standalone sdk-minimal profile ([8dc3b03](https://github.com/deepseek-ai/deepseek-harness/commit/8dc3b0380))
- feat(web): settle folder references on pick and move descent to a drill verb ([dad39c8](https://github.com/deepseek-ai/deepseek-harness/commit/dad39c8c1))
- feat(web): require one-shot fetch approval ([9fbcea0](https://github.com/deepseek-ai/deepseek-harness/commit/9fbcea099))

### 🐛 Bug Fixes
- fix(web): move subagent model switch to Plugins ([f887a8f](https://github.com/deepseek-ai/deepseek-harness/commit/f887a8f90))
- fix(e2e): decode packed history records ([4f02717](https://github.com/deepseek-ai/deepseek-harness/commit/4f02717eb))
- fix(history): adapt packed pages to session journal ([04c0758](https://github.com/deepseek-ai/deepseek-harness/commit/04c0758fe))
- fix(webworker): inline combo source maps ([78184a6](https://github.com/deepseek-ai/deepseek-harness/commit/78184a6ee))
- fix(client): preserve combo source identities ([075a46c](https://github.com/deepseek-ai/deepseek-harness/commit/075a46cde))
- fix(webworker): retain third-party runtime sources ([b3081bb](https://github.com/deepseek-ai/deepseek-harness/commit/b3081bb4b))
- fix(ci): serialize native Windows coverage after build ([97f9e2e](https://github.com/deepseek-ai/deepseek-harness/commit/97f9e2e40))
- fix(repo): close examples migration review gaps ([e73c8a9](https://github.com/deepseek-ai/deepseek-harness/commit/e73c8a9fc))
- fix(test): declare Loader fixture dependencies ([3b090c3](https://github.com/deepseek-ai/deepseek-harness/commit/3b090c3c1))
- fix(test): refresh inherited session pins ([59b156c](https://github.com/deepseek-ai/deepseek-harness/commit/59b156cb6))
- fix(web): enforce approval before DNS resolution ([709e5ed](https://github.com/deepseek-ai/deepseek-harness/commit/709e5edab))
- fix(test): align snapshots with merged tool routing ([1232e61](https://github.com/deepseek-ai/deepseek-harness/commit/1232e6113))
- fix(test): reconcile snapshot corpus with merged parent ([6a74eec](https://github.com/deepseek-ai/deepseek-harness/commit/6a74eec7a))
- fix(test): refresh Goal UI from complete build ([920fe95](https://github.com/deepseek-ai/deepseek-harness/commit/920fe95be))
- fix(test): align snapshots with latest base ([8e23adc](https://github.com/deepseek-ai/deepseek-harness/commit/8e23adcd2))
- fix(test): make Goal replay host-independent ([84d172d](https://github.com/deepseek-ai/deepseek-harness/commit/84d172de3))
- fix(test): stabilize rebased web fixtures ([61cfe86](https://github.com/deepseek-ai/deepseek-harness/commit/61cfe86f6))
- fix(test): harden snapshot corpus invariants ([6ea8a52](https://github.com/deepseek-ai/deepseek-harness/commit/6ea8a52e2))
- fix(test): make session replay portable in CI ([d1e8f46](https://github.com/deepseek-ai/deepseek-harness/commit/d1e8f4672))
- fix(test): use expected-output naming ([caf386f](https://github.com/deepseek-ai/deepseek-harness/commit/caf386f59))
- fix(client-modules,webserver,webworker-runtime): preserve batched boot across transports ([47bf44a](https://github.com/deepseek-ai/deepseek-harness/commit/47bf44a5b))
- fix(compaction): 摘要收缩改按路由价并补齐定价访问路径 ([5183bc2](https://github.com/deepseek-ai/deepseek-harness/commit/5183bc2b6))
- fix(python): budget cold profile initialization ([dff3e18](https://github.com/deepseek-ai/deepseek-harness/commit/dff3e18af))
- fix(web): 处理评审发现的图片记录边界情况 ([d420292](https://github.com/deepseek-ai/deepseek-harness/commit/d42029240))
- fix(sdk-minimal): make the SDK model argument authoritative ([e2920f0](https://github.com/deepseek-ai/deepseek-harness/commit/e2920f010))
- fix(python-sdk): make the minimal profile an explicit allowlist ([c2ad693](https://github.com/deepseek-ai/deepseek-harness/commit/c2ad69344))
- fix(attachment): budget master pixels and share the encoding ladder ([30704dc](https://github.com/deepseek-ai/deepseek-harness/commit/30704dc1d))
- fix(file-reference): teach the @-mention guidance directories and the workspace root ([70d6e7a](https://github.com/deepseek-ai/deepseek-harness/commit/70d6e7abd))
- fix(spill-local): harden startup cleanup ([a268aad](https://github.com/deepseek-ai/deepseek-harness/commit/a268aada8))
- fix(ci): restore acp snapshot transcripts and windows coverage gate ordering ([5fe36b5](https://github.com/deepseek-ai/deepseek-harness/commit/5fe36b513))
- fix(attachment): route image encoding by alpha over shared quality ladders ([4863890](https://github.com/deepseek-ai/deepseek-harness/commit/486389053))
- fix(client): restore branded running copy ([d61ba08](https://github.com/deepseek-ai/deepseek-harness/commit/d61ba0868))
- fix(attachment): 修正 Windows 只读发布顺序 ([5c799a9](https://github.com/deepseek-ai/deepseek-harness/commit/5c799a952))
- fix(client): localize local build banner ([720c5c2](https://github.com/deepseek-ai/deepseek-harness/commit/720c5c247))
- fix(web): preserve preview fetch composition ([470af0a](https://github.com/deepseek-ai/deepseek-harness/commit/470af0a40))
- fix(system-prompt): preserve downstream section order ([25428f8](https://github.com/deepseek-ai/deepseek-harness/commit/25428f8e0))
- fix(system-prompt): stabilize workflow section order ([fdf6030](https://github.com/deepseek-ai/deepseek-harness/commit/fdf60301f))
- fix(web): block non-public fetch destinations ([b2219bb](https://github.com/deepseek-ai/deepseek-harness/commit/b2219bba6))
- fix(webworker): close Node compatibility gaps ([92cac5d](https://github.com/deepseek-ai/deepseek-harness/commit/92cac5d29))
- fix(client): preload injected module factories ([5549b9a](https://github.com/deepseek-ai/deepseek-harness/commit/5549b9add))
- fix(webworker): support package inventory resolution ([91b545d](https://github.com/deepseek-ai/deepseek-harness/commit/91b545daf))
- fix(webworker): scope Linux-only CI checks ([be852d4](https://github.com/deepseek-ai/deepseek-harness/commit/be852d4e9))
- fix(webworker): align filesystem semantics with Node ([5ad9b12](https://github.com/deepseek-ai/deepseek-harness/commit/5ad9b128f))
- fix(preview): point the config-tree declaration at the plugin-bundled presets ([34a3097](https://github.com/deepseek-ai/deepseek-harness/commit/34a309731))
- fix(client): localize terminal send presentation ([1dd6bf1](https://github.com/deepseek-ai/deepseek-harness/commit/1dd6bf197))
- fix(client): preserve editor running diffs ([d9a0713](https://github.com/deepseek-ai/deepseek-harness/commit/d9a071340))

### 🔄 Refactoring
- refactor(prompt): remove unused complete-persona config ([43f0f07](https://github.com/deepseek-ai/deepseek-harness/commit/43f0f07f9))
- refactor(sdk): remove unused root tool filter ([d35459e](https://github.com/deepseek-ai/deepseek-harness/commit/d35459e3c))
- test(webworker): keep bundle transport on host face ([6008968](https://github.com/deepseek-ai/deepseek-harness/commit/60089680f))
- refactor(webserver): minimize HTTP gzip integration ([08ed5a5](https://github.com/deepseek-ai/deepseek-harness/commit/08ed5a54a))
- test(sqlite): decouple retry pacing from setup time ([10ba26d](https://github.com/deepseek-ai/deepseek-harness/commit/10ba26dcf))
- refactor(repo): retire top-level examples ([4125514](https://github.com/deepseek-ai/deepseek-harness/commit/4125514a0))
- test(snapshot): cover Windows workspace symlinks ([e25463b](https://github.com/deepseek-ai/deepseek-harness/commit/e25463bc0))
- test(web): register snapshot network fixture ([2ac9072](https://github.com/deepseek-ai/deepseek-harness/commit/2ac907299))
- test(subagent): align DSH SDK route evidence with profiles ([0aafe0f](https://github.com/deepseek-ai/deepseek-harness/commit/0aafe0f8f))
- refactor(test): reserve snapshots for session recordings ([1cfe0f9](https://github.com/deepseek-ai/deepseek-harness/commit/1cfe0f994))
- test(snapshot): verify final workspace state ([d4e81b6](https://github.com/deepseek-ai/deepseek-harness/commit/d4e81b6af))
- refactor(test): drive sessions through owning profiles ([6ca6827](https://github.com/deepseek-ai/deepseek-harness/commit/6ca682733))
- test(snapshot): drive ordinary turns through headless dsh ([4790f23](https://github.com/deepseek-ai/deepseek-harness/commit/4790f23fe))
- test(web): separate session snapshots from goldens ([6189e4a](https://github.com/deepseek-ai/deepseek-harness/commit/6189e4a37))
- test(snapshot): separate headless sessions from goldens ([33faf7f](https://github.com/deepseek-ai/deepseek-harness/commit/33faf7f35))
- test(snapshot): centralize SDK session corpus ([da1cb2c](https://github.com/deepseek-ai/deepseek-harness/commit/da1cb2c06))
- test(snapshot): declare recorded session ownership ([84d6482](https://github.com/deepseek-ai/deepseek-harness/commit/84d6482a9))
- test(snapshot): centralize ACP session corpus ([5c67cf8](https://github.com/deepseek-ai/deepseek-harness/commit/5c67cf898))
- refactor(test): make session snapshots transport neutral ([30762b6](https://github.com/deepseek-ai/deepseek-harness/commit/30762b63c))
- test(spill-local): exclude POSIX identity branches on Windows ([d6f9931](https://github.com/deepseek-ai/deepseek-harness/commit/d6f9931c4))
- test(spill-local): cover platform-specific cleanup paths ([97693bb](https://github.com/deepseek-ai/deepseek-harness/commit/97693bbc8))
- test(spill-local): normalize Windows realpaths consistently ([9f9cc13](https://github.com/deepseek-ai/deepseek-harness/commit/9f9cc130e))
- test(python): exercise the shipped SDK profile directly ([4719bef](https://github.com/deepseek-ai/deepseek-harness/commit/4719bef93))
- test(sdk-app): cover default profile configuration ([104fe9b](https://github.com/deepseek-ai/deepseek-harness/commit/104fe9b9e))
- refactor(python): launch the minimal example through sdk-minimal ([79a8f66](https://github.com/deepseek-ai/deepseek-harness/commit/79a8f667f))
- test(attachment): pin the assembled image re-encoding path in a keyless snapshot ([cfacca1](https://github.com/deepseek-ai/deepseek-harness/commit/cfacca1b0))
- test(web): create reference fixtures before the workspace connects ([4036db4](https://github.com/deepseek-ai/deepseek-harness/commit/4036db445))
- test(llm): 覆盖执行环境图片路径解析 ([7bad882](https://github.com/deepseek-ai/deepseek-harness/commit/7bad88206))
- test(web): wait for stable preview onboarding ([15ddb2e](https://github.com/deepseek-ai/deepseek-harness/commit/15ddb2edc))
- refactor(attachment): 分离宿主位置与模型访问路径 ([558f087](https://github.com/deepseek-ai/deepseek-harness/commit/558f08780))
- test(web): permit loopback spill fixture ([2fbe199](https://github.com/deepseek-ai/deepseek-harness/commit/2fbe199a1))
- test(web): finish the textarea-locator sweep after the architecture merge ([6f17d10](https://github.com/deepseek-ai/deepseek-harness/commit/6f17d1010))
- test(web): permit loopback integration fixture ([c406560](https://github.com/deepseek-ai/deepseek-harness/commit/c40656045))
- test(web): snapshot blocked loopback fetch ([9d5fa7a](https://github.com/deepseek-ai/deepseek-harness/commit/9d5fa7a59))
- test(client): close the merged-architecture coverage and jsdom gaps ([04caa12](https://github.com/deepseek-ai/deepseek-harness/commit/04caa1248))
- test(web): await subagent history before snapshot ([8aa222a](https://github.com/deepseek-ai/deepseek-harness/commit/8aa222a40))
- test(llm): pin includeShippedRoot off in the inventory roster ([05daf25](https://github.com/deepseek-ai/deepseek-harness/commit/05daf25e1))
- test(llm): cover pi-ai upgrade compatibility ([c4f1057](https://github.com/deepseek-ai/deepseek-harness/commit/c4f10577b))
- test(web): refresh pi-ai provider catalog snapshots ([114846b](https://github.com/deepseek-ai/deepseek-harness/commit/114846b4c))
- refactor(client): remove directory error re-export ([e5395b3](https://github.com/deepseek-ai/deepseek-harness/commit/e5395b36a))

### 📝 Documentation
- docs(ci): align Windows coverage capacity model ([aec6e43](https://github.com/deepseek-ai/deepseek-harness/commit/aec6e4371))
- docs: refresh module dependency graph ([e4a3918](https://github.com/deepseek-ai/deepseek-harness/commit/e4a3918e8))
- docs(client-modules,client-hmr): align bootstrap and rebuild semantics ([838006d](https://github.com/deepseek-ai/deepseek-harness/commit/838006d96))
- docs: 同步模块依赖关系图 ([15d53e2](https://github.com/deepseek-ai/deepseek-harness/commit/15d53e228))
- docs(subagent): refresh Claude runtime notices ([56067f9](https://github.com/deepseek-ai/deepseek-harness/commit/56067f997))
- docs(python): define the standalone minimal profile ([7a11f5f](https://github.com/deepseek-ai/deepseek-harness/commit/7a11f5fde))
- docs(token-meter): distinguish projection and measurement folds ([4db19c3](https://github.com/deepseek-ai/deepseek-harness/commit/4db19c352))
- docs(web): document shipped fetch policy ([14e4d3f](https://github.com/deepseek-ai/deepseek-harness/commit/14e4d3f07))
- docs(client): sync injected module graph contract ([ce1247d](https://github.com/deepseek-ai/deepseek-harness/commit/ce1247d95))
- docs(session): record cold projection composition rule ([8fbd165](https://github.com/deepseek-ai/deepseek-harness/commit/8fbd1650a))
- docs(tools): link terminal presentation markers ([bfc145c](https://github.com/deepseek-ai/deepseek-harness/commit/bfc145cc7))
- docs(client): document web architecture ([3e942e5](https://github.com/deepseek-ai/deepseek-harness/commit/3e942e5e2))
- docs(client): preserve opaque context fallback ([78b8cc7](https://github.com/deepseek-ai/deepseek-harness/commit/78b8cc731))

### 🔧 Configuration
- perf(client-modules): defer per-plugin revision hashing ([9c3a089](https://github.com/deepseek-ai/deepseek-harness/commit/9c3a0893f))
- chore(subagent): refresh Codex runtime ([55a8c2e](https://github.com/deepseek-ai/deepseek-harness/commit/55a8c2e9f))
- chore(subagent): refresh Claude Code runtime ([6a02e2c](https://github.com/deepseek-ai/deepseek-harness/commit/6a02e2c4a))
- perf(app-boot): avoid fallback locks for complete profiles ([ab4e65b](https://github.com/deepseek-ai/deepseek-harness/commit/ab4e65ba8))
- perf(token-meter): commit the surface fold in place through a plan/commit pair ([58a0e45](https://github.com/deepseek-ai/deepseek-harness/commit/58a0e450b))
- style(client): stack local build metadata ([1a36d5c](https://github.com/deepseek-ai/deepseek-harness/commit/1a36d5c6f))
- Revert "perf(ci): shorten native Windows coverage critical path" ([cd6941d](https://github.com/deepseek-ai/deepseek-harness/commit/cd6941d5d))
- 修正图片路径访问与只读存储 ([7f4cf99](https://github.com/deepseek-ai/deepseek-harness/commit/7f4cf99ee))
- chore(attachment): start issue-2885 image codec work ([6434b89](https://github.com/deepseek-ai/deepseek-harness/commit/6434b894c))
- perf(webworker): index VFS hard links ([ab0f793](https://github.com/deepseek-ai/deepseek-harness/commit/ab0f7937c))
- chore(llm): bump pi-ai to 0.84.2 ([44bd918](https://github.com/deepseek-ai/deepseek-harness/commit/44bd9182f))

## 2026-08-25

**122 commits.** 9 feature changes, 33 fixes.

### 🆕 New Features
- feat(ui): extend the content font-size axis to flow chrome ([9ecd18e](https://github.com/deepseek-ai/deepseek-harness/commit/9ecd18e98))
- feat(gateway): support ranged journal entries ([20d55b2](https://github.com/deepseek-ai/deepseek-harness/commit/20d55b2c4))
- feat(web): show exact per-turn token usage ([b565df3](https://github.com/deepseek-ai/deepseek-harness/commit/b565df344))
- feat(web): navigate loaded Chat Turns from a compact rail ([d38ff54](https://github.com/deepseek-ai/deepseek-harness/commit/d38ff5415))
- feat(client): highlight streaming fences incrementally ([1825cb4](https://github.com/deepseek-ai/deepseek-harness/commit/1825cb465))
- feat(bundle): default session telemetry to feedback-gated sharing ([106e5ce](https://github.com/deepseek-ai/deepseek-harness/commit/106e5ce0b))
- feat(session): persist model selection and share its catalog ([822d735](https://github.com/deepseek-ai/deepseek-harness/commit/822d73535))
- feat(session-query): add shared projected observations ([7fb2ca0](https://github.com/deepseek-ai/deepseek-harness/commit/7fb2ca07e))
- refactor(session-persistence): add borrowable prepared sessions ([7f4cdc8](https://github.com/deepseek-ai/deepseek-harness/commit/7f4cdc809))

### 🐛 Bug Fixes
- fix: address subagent model selection review ([3a14606](https://github.com/deepseek-ai/deepseek-harness/commit/3a146064a))
- fix(snapshot): stabilize workflow prompt order ([f2bb5ce](https://github.com/deepseek-ai/deepseek-harness/commit/f2bb5cef0))
- fix(web): close model switch review gaps ([1ea7233](https://github.com/deepseek-ai/deepseek-harness/commit/1ea72339f))
- fix(subagent): gate model selection with explicit allowlist ([7c626fb](https://github.com/deepseek-ai/deepseek-harness/commit/7c626fb5d))
- fix(team): authenticate browser panel snapshot ([194faca](https://github.com/deepseek-ai/deepseek-harness/commit/194facabd))
- fix(team): preserve current Client architecture after rebase ([eadd5df](https://github.com/deepseek-ai/deepseek-harness/commit/eadd5df82))
- fix(profile): deduplicate fallback manifest traversal ([42378a9](https://github.com/deepseek-ai/deepseek-harness/commit/42378a987))
- fix(profile): preserve current fallback architecture after rebase ([1477d5b](https://github.com/deepseek-ai/deepseek-harness/commit/1477d5b9e))
- fix(web): hide model selector descriptions ([b6c5aa7](https://github.com/deepseek-ai/deepseek-harness/commit/b6c5aa751))
- fix(web): expand persistent Bash result cards ([9b6729d](https://github.com/deepseek-ai/deepseek-harness/commit/9b6729d50))
- fix(storage-json): preserve legacy cache after bootstrap ([3803344](https://github.com/deepseek-ai/deepseek-harness/commit/380334436))
- fix(chat): exclude packed deltas from token fold ([27b8d6f](https://github.com/deepseek-ai/deepseek-harness/commit/27b8d6fe9))
- fix(conversation): restore merge-map lint scope ([d3efd9c](https://github.com/deepseek-ai/deepseek-harness/commit/d3efd9c35))
- fix(snapshot): project headless reasoning stderr ([7c7e4aa](https://github.com/deepseek-ai/deepseek-harness/commit/7c7e4aada))
- fix(subagent-acp): correct it.skipIf call arity ([c26a335](https://github.com/deepseek-ai/deepseek-harness/commit/c26a3351c))
- fix(subagent-acp): use supported skipIf signature ([637e029](https://github.com/deepseek-ai/deepseek-harness/commit/637e02936))
- fix(snapshot): canonicalize cache-split chunk runs ([96db1c8](https://github.com/deepseek-ai/deepseek-harness/commit/96db1c8c8))
- fix(web): show system prompts in chat ([61b65d3](https://github.com/deepseek-ai/deepseek-harness/commit/61b65d314))
- fix(bundle): enable projection cache in base-backed profiles ([2c17b30](https://github.com/deepseek-ai/deepseek-harness/commit/2c17b3048))
- fix(web): keep browser authentication synchronous ([9c96484](https://github.com/deepseek-ai/deepseek-harness/commit/9c964848c))
- fix(web): retain launch token across reloads ([3b3b493](https://github.com/deepseek-ai/deepseek-harness/commit/3b3b493a9))
- fix(web): cover authenticated host runtimes ([ce031dd](https://github.com/deepseek-ai/deepseek-harness/commit/ce031ddd1))
- fix(web): authenticate the browser Host API ([3e24087](https://github.com/deepseek-ai/deepseek-harness/commit/3e24087bf))
- fix(snapshot): honor ACP-local sidecar sources ([4309dab](https://github.com/deepseek-ai/deepseek-harness/commit/4309dab24))
- fix(pty): detect emulated kernel syscall ABI ([2338f4a](https://github.com/deepseek-ai/deepseek-harness/commit/2338f4ad1))
- fix(pty): identify waiting thread terminals ([5467685](https://github.com/deepseek-ai/deepseek-harness/commit/5467685bc))
- fix(pty): distinguish pipeline reads from terminal input ([9a12505](https://github.com/deepseek-ai/deepseek-harness/commit/9a12505f8))
- test(python): share advanced runtime profile patch ([aa801a4](https://github.com/deepseek-ai/deepseek-harness/commit/aa801a418))
- fix(ci): keep the base projection cache out of listing-less profiles ([ce65310](https://github.com/deepseek-ai/deepseek-harness/commit/ce6531018))
- fix: 修正轨迹图片测试归属 ([9c931ef](https://github.com/deepseek-ai/deepseek-harness/commit/9c931ef5a))
- fix(system-prompt): centralize sparse section orders ([43ac97b](https://github.com/deepseek-ai/deepseek-harness/commit/43ac97b55))
- fix: c i ([059598d](https://github.com/deepseek-ai/deepseek-harness/commit/059598de5))
- fix(agent-presets): project selection and refresh client catalogs ([b8dfa8b](https://github.com/deepseek-ai/deepseek-harness/commit/b8dfa8b89))

### 🔄 Refactoring
- test(sdk): expect model discovery off by default ([9fae988](https://github.com/deepseek-ai/deepseek-harness/commit/9fae98869))
- test(web): configure subagent model allowlist ([ebe8d4d](https://github.com/deepseek-ai/deepseek-harness/commit/ebe8d4db1))
- test(webworker-runtime): restore the transform semantic spec ([2d89a76](https://github.com/deepseek-ai/deepseek-harness/commit/2d89a76b9))
- test(webworker-runtime): keep the corpus gate as a Node import sweep ([8793cd4](https://github.com/deepseek-ai/deepseek-harness/commit/8793cd477))
- test(webworker-runtime): drop coverage requirement and compile transform suites ([6d9cc6a](https://github.com/deepseek-ai/deepseek-harness/commit/6d9cc6ab9))
- test(subagent-acp): exempt Windows-inaccessible branches ([d97868b](https://github.com/deepseek-ai/deepseek-harness/commit/d97868b94))
- test: widen windows-hosted subprocess budgets in two web-stack specs ([a404edf](https://github.com/deepseek-ai/deepseek-harness/commit/a404edf3b))
- test(pwsh-local): accept graceful SIGTERM exit as service-disposal death ([553b8c3](https://github.com/deepseek-ai/deepseek-harness/commit/553b8c35d))
- test(web): stabilize minimal Bash card snapshot ([a91fa3d](https://github.com/deepseek-ai/deepseek-harness/commit/a91fa3ddb))
- refactor(apiproxy): delete the goal unary domain ([243f662](https://github.com/deepseek-ai/deepseek-harness/commit/243f6629e))
- test(history): cover packed record branches ([adddc4d](https://github.com/deepseek-ai/deepseek-harness/commit/adddc4dea))
- test(web): drive the streaming-fence prompt through the composer surface ([effbffb](https://github.com/deepseek-ai/deepseek-harness/commit/effbffbff))
- test(snapshot): refresh DSH SDK route schemas ([4d54bfd](https://github.com/deepseek-ai/deepseek-harness/commit/4d54bfdff))
- test(ci): stabilize cross-platform consumer gates ([08aed20](https://github.com/deepseek-ai/deepseek-harness/commit/08aed2013))
- test(cli): allow Windows help smoke startup budget ([847c13a](https://github.com/deepseek-ai/deepseek-harness/commit/847c13a11))
- test: refresh dynamic route prompts after master ([b274f5e](https://github.com/deepseek-ai/deepseek-harness/commit/b274f5e60))
- test(snapshot): refresh DSH diagnostic prompt ([09fcf48](https://github.com/deepseek-ai/deepseek-harness/commit/09fcf48ad))
- test: declare loader fixture skill dependency ([b9cd0d0](https://github.com/deepseek-ai/deepseek-harness/commit/b9cd0d0c9))
- test(ci): stabilize required snapshot and Windows lanes ([7e234bb](https://github.com/deepseek-ai/deepseek-harness/commit/7e234bb5b))
- test: stabilize post-merge integration fixtures ([c97f985](https://github.com/deepseek-ai/deepseek-harness/commit/c97f985ca))
- ci(windows): serialize native test files ([560729b](https://github.com/deepseek-ai/deepseek-harness/commit/560729be7))
- test(web): authenticate folding snapshot ([b68f36a](https://github.com/deepseek-ai/deepseek-harness/commit/b68f36a1c))
- test(web): authenticate folding snapshot page ([1ca0818](https://github.com/deepseek-ai/deepseek-harness/commit/1ca08183a))
- test(subagent-acp): skip half-close cases on Windows ([f858caa](https://github.com/deepseek-ai/deepseek-harness/commit/f858caa9c))
- test(subagent): exercise proxy EOF on Windows ([89b50d3](https://github.com/deepseek-ai/deepseek-harness/commit/89b50d3f1))
- test(subagent): close ACP protocol portably ([903d973](https://github.com/deepseek-ai/deepseek-harness/commit/903d9732a))
- test(subagent-acp): skip stdout half-close tests on Windows ([eea3c13](https://github.com/deepseek-ai/deepseek-harness/commit/eea3c132f))
- test(subagent): make ACP coverage platform-independent ([4dca535](https://github.com/deepseek-ai/deepseek-harness/commit/4dca5359a))
- test(subagent-acp): double the per-test timeout relative to default ([5e7c567](https://github.com/deepseek-ai/deepseek-harness/commit/5e7c567dc))
- test(snapshot): sync web search trust prompt ([6199f47](https://github.com/deepseek-ai/deepseek-harness/commit/6199f477d))
- test(snapshot): refresh image request header ([1f288ed](https://github.com/deepseek-ai/deepseek-harness/commit/1f288ede7))
- ci(windows): raise coverage test timeout to 60s ([3073107](https://github.com/deepseek-ai/deepseek-harness/commit/3073107ec))
- test(subagent): stabilize ACP process coverage ([68be3e2](https://github.com/deepseek-ai/deepseek-harness/commit/68be3e227))
- test(web): record the Turn rail in every affected aria golden ([ba84299](https://github.com/deepseek-ai/deepseek-harness/commit/ba84299c9))
- refactor(web): remove fetch approval policy ([797c711](https://github.com/deepseek-ai/deepseek-harness/commit/797c711e1))
- test(web): authenticate streaming fence scaffold ([4de11c0](https://github.com/deepseek-ai/deepseek-harness/commit/4de11c022))
- test(web): keep credential fixtures package-local ([b43d093](https://github.com/deepseek-ai/deepseek-harness/commit/b43d0934f))
- test(pty): cover restricted proc syscall access ([a3f6713](https://github.com/deepseek-ai/deepseek-harness/commit/a3f67137b))
- test(credentials-local): seed fixtures atomically to close a boot-read race ([ee2ee39](https://github.com/deepseek-ai/deepseek-harness/commit/ee2ee398c))
- test(pty): report proc state on readiness failure ([133ed2d](https://github.com/deepseek-ai/deepseek-harness/commit/133ed2d0f))
- test(windows): split native job into build/coverage/native-tests/observational ([58cc29b](https://github.com/deepseek-ai/deepseek-harness/commit/58cc29b4f))
- refactor(cli): keep config dumps out of runtime healing ([7e6193a](https://github.com/deepseek-ai/deepseek-harness/commit/7e6193acc))
- refactor(python): keep launch override on client ([8146557](https://github.com/deepseek-ai/deepseek-harness/commit/8146557ef))
- test(sdk): leave model surface to packaged snapshot ([d0e8f5f](https://github.com/deepseek-ai/deepseek-harness/commit/d0e8f5f9c))
- test(windows): try 4 coverage partitions instead of 8 ([55ef5aa](https://github.com/deepseek-ai/deepseek-harness/commit/55ef5aad0))
- test(web): share the per-key composer draft helper ([07319c0](https://github.com/deepseek-ai/deepseek-harness/commit/07319c011))
- test(web): refresh fetch and trust snapshots ([04e946e](https://github.com/deepseek-ai/deepseek-harness/commit/04e946ed8))
- test(snapshot): refresh web prompt pins ([0f7b28a](https://github.com/deepseek-ai/deepseek-harness/commit/0f7b28ad3))
- test(web): align system-prompt pins with the reference guidance ([4d859cc](https://github.com/deepseek-ai/deepseek-harness/commit/4d859cc06))
- test(snapshot): refresh prompt order pins ([5b3bfbe](https://github.com/deepseek-ai/deepseek-harness/commit/5b3bfbed4))
- test(web): refresh fetch tool schema snapshots ([433aab2](https://github.com/deepseek-ai/deepseek-harness/commit/433aab272))
- test(web): refresh external content prompt snapshots ([1af9802](https://github.com/deepseek-ai/deepseek-harness/commit/1af98028f))
- test(web): write folder queries with per-key gestures ([e71688c](https://github.com/deepseek-ai/deepseek-harness/commit/e71688c1f))
- fixup! refactor(session): open journal streams from snapshots ([d2904a6](https://github.com/deepseek-ai/deepseek-harness/commit/d2904a6c0))
- refactor(subagent): consume shared session observations ([f5f0448](https://github.com/deepseek-ai/deepseek-harness/commit/f5f0448be))
- refactor(session): open journal streams from snapshots ([e7952d8](https://github.com/deepseek-ai/deepseek-harness/commit/e7952d82e))
- test(web): exercise fetch snapshot across build faces ([77e0b12](https://github.com/deepseek-ai/deepseek-harness/commit/77e0b121d))

### 📝 Documentation
- docs: rebuild the documentation skill and standards ([0b5eba0](https://github.com/deepseek-ai/deepseek-harness/commit/0b5eba0c8))
- docs(web): state authentication contracts directly ([5595d59](https://github.com/deepseek-ai/deepseek-harness/commit/5595d593d))
- docs(i18n): re-record translation pairing sidecars after partition update ([bea14f9](https://github.com/deepseek-ai/deepseek-harness/commit/bea14f9fc))
- docs(windows): sync native CI note to 4 coverage partitions ([16dbf73](https://github.com/deepseek-ai/deepseek-harness/commit/16dbf7334))
- docs(coverage): update Agent Note for Windows 4-partition alignment ([a813b48](https://github.com/deepseek-ai/deepseek-harness/commit/a813b487a))
- docs(system-prompt): sync first-party order references ([8020f63](https://github.com/deepseek-ai/deepseek-harness/commit/8020f6386))
- docs: refresh module graph ([55eeaf6](https://github.com/deepseek-ai/deepseek-harness/commit/55eeaf656))
- docs(session): record observation and projection ownership ([2b60227](https://github.com/deepseek-ai/deepseek-harness/commit/2b60227d0))
- docs(session): refresh architecture and generated contracts ([1229292](https://github.com/deepseek-ai/deepseek-harness/commit/122929249))

### 🔧 Configuration
- rename code-mode to ptc (PTC mode), except session-persistent vocabulary ([3ca9c7d](https://github.com/deepseek-ai/deepseek-harness/commit/3ca9c7d48))
- perf(typert): skip re-verified diagnostics and share analyzer caches in the tsdown plugin ([54ef0f3](https://github.com/deepseek-ai/deepseek-harness/commit/54ef0f315))
- perf(ci) ([75428c7](https://github.com/deepseek-ai/deepseek-harness/commit/75428c7f4))
- perf(ci): move the transform corpus out of coverage partitions ([9bf6f4b](https://github.com/deepseek-ai/deepseek-harness/commit/9bf6f4b43))
- chore(tool-cordis): regenerate the Cordis catalog after the goal unary deletion ([9740587](https://github.com/deepseek-ai/deepseek-harness/commit/97405878c))
- build(apiproxy): drop the now-unused goal dependency ([f04e2fe](https://github.com/deepseek-ai/deepseek-harness/commit/f04e2fe44))
- perf(storage-json): load record files concurrently ([83459fa](https://github.com/deepseek-ai/deepseek-harness/commit/83459fa47))
- polish(ui): trim the width handle and describe the font-size scope ([5720917](https://github.com/deepseek-ai/deepseek-harness/commit/5720917ea))
- perf(conversation): fold packed assistant history ([f37bb35](https://github.com/deepseek-ai/deepseek-harness/commit/f37bb35a9))
- perf(history): retain packed records in client ([1ec75c9](https://github.com/deepseek-ai/deepseek-harness/commit/1ec75c908))
- ci(windows): make windows-coverage temporarily non-blocking ([ac2f000](https://github.com/deepseek-ai/deepseek-harness/commit/ac2f00070))
- Revert "Merge pull request #2698 from deepseek-harness/xtr/session-format-migration" ([211e693](https://github.com/deepseek-ai/deepseek-harness/commit/211e6939e))
- perf(web): accumulate the Turn rail instead of scanning the loaded window ([1272c7d](https://github.com/deepseek-ai/deepseek-harness/commit/1272c7d0d))
- perf(session-controller): serve cache-first session state ([69fad4b](https://github.com/deepseek-ai/deepseek-harness/commit/69fad4b8d))

## 2026-08-26

**93 commits.** 8 feature changes, 29 fixes, including breaking changes.

### ⚠️ Breaking Changes
- test(subagent): migrate model selection fixtures ([bf7020a](https://github.com/deepseek-ai/deepseek-harness/commit/bf7020ade))
- feat(subagent): migrate browser control to Remote ([377f3b4](https://github.com/deepseek-ai/deepseek-harness/commit/377f3b4f1))

### 🆕 New Features
- test: derive the plugin add/remove budget and note the exe build ([d77b64e](https://github.com/deepseek-ai/deepseek-harness/commit/d77b64e7c))
- feat(web): polish the input trigger menu presentation ([0114dc1](https://github.com/deepseek-ai/deepseek-harness/commit/0114dc1f8))
- feat(ui): unify the flow-row secondary font tier and scale tables ([a77e23a](https://github.com/deepseek-ai/deepseek-harness/commit/a77e23a97))
- feat(session): reduce persistence storage size ([df76bc6](https://github.com/deepseek-ai/deepseek-harness/commit/df76bc695))
- feat(ui-settings-models): open provider-card and footer extension slots ([855461c](https://github.com/deepseek-ai/deepseek-harness/commit/855461c2e))
- feat(web): 提交回显在 Chat 流尾即时渲染 ([cf47b7e](https://github.com/deepseek-ai/deepseek-harness/commit/cf47b7e05))
- feat(ui-conversation): 默认发送改为乐观提交并接入提交回显 ([390dad6](https://github.com/deepseek-ai/deepseek-harness/commit/390dad613))
- feat(session-controller): 客户端本地提交回显与 rpcId 关联 ([98da332](https://github.com/deepseek-ai/deepseek-harness/commit/98da33226))

### 🐛 Bug Fixes
- fix: point the rename note at the fail-closed session-event vocabulary note ([70af4ed](https://github.com/deepseek-ai/deepseek-harness/commit/70af4edf3))
- fix: rename the remaining code mode-value prose found in review ([215e90d](https://github.com/deepseek-ai/deepseek-harness/commit/215e90dfb))
- fix: repair merged README remnants and note links after the master rebase ([409f9ee](https://github.com/deepseek-ai/deepseek-harness/commit/409f9ee30))
- fix: align mode-value prose and stale persistent mentions with the split ([45c514a](https://github.com/deepseek-ai/deepseek-harness/commit/45c514a42))
- fix(api-gateway): keep idle websocket alive ([af562d3](https://github.com/deepseek-ai/deepseek-harness/commit/af562d364))
- fix(ui-settings-plugins): preserve model selection drafts ([aad90d5](https://github.com/deepseek-ai/deepseek-harness/commit/aad90d5cf))
- fix(ui-settings-plugins): place Subagent after Agent loop ([cbaccec](https://github.com/deepseek-ai/deepseek-harness/commit/cbacceca4))
- fix(ui-settings-plugins): relax Subagent card layout ([4cc1f5e](https://github.com/deepseek-ai/deepseek-harness/commit/4cc1f5e0f))
- fix(subagent): omit undefined scoped fixture options ([a7614f9](https://github.com/deepseek-ai/deepseek-harness/commit/a7614f971))
- fix(notices): resolve current installed dependency versions ([a5cc8a2](https://github.com/deepseek-ai/deepseek-harness/commit/a5cc8a218))
- fix(ui-settings-plugins): align Subagent configuration card ([0b2f476](https://github.com/deepseek-ai/deepseek-harness/commit/0b2f47607))
- fix(review): correct the secondary-tier floor claim and pin engine-resolved sizes ([9e33469](https://github.com/deepseek-ai/deepseek-harness/commit/9e3346991))
- fix(ui-settings-models): address review — derived key fact, required render seat, spec sync ([bf0db65](https://github.com/deepseek-ai/deepseek-harness/commit/bf0db65bb))
- fix(llm-pi-ai): store the JSON image of a grant payload ([b5c3cc8](https://github.com/deepseek-ai/deepseek-harness/commit/b5c3cc897))
- fix(webworker): scope createRequire dependency discovery ([b72f587](https://github.com/deepseek-ai/deepseek-harness/commit/b72f5879c))
- fix(webworker): expose Node process identity ([8f88a6f](https://github.com/deepseek-ai/deepseek-harness/commit/8f88a6f20))
- fix(webworker): retain createRequire dependencies ([d54c279](https://github.com/deepseek-ai/deepseek-harness/commit/d54c2795c))
- fix(web): address question draft review feedback ([605e33a](https://github.com/deepseek-ai/deepseek-harness/commit/605e33a2f))
- fix(agent-presets): answer health from the walk alone, and keep the reason reachable ([56d3e8f](https://github.com/deepseek-ai/deepseek-harness/commit/56d3e8f82))
- fix(docs): harden build output cleanup ([1d09a4c](https://github.com/deepseek-ai/deepseek-harness/commit/1d09a4c87))
- fix(ci): bound Windows process contention ([4e1c87b](https://github.com/deepseek-ai/deepseek-harness/commit/4e1c87b1a))
- fix(ui-agent-preset): read a refusal's cause by its detail, not its code ([002af9f](https://github.com/deepseek-ai/deepseek-harness/commit/002af9f20))
- fix(agent-presets): make a preset's failures legible where they happen ([f7890f5](https://github.com/deepseek-ai/deepseek-harness/commit/f7890f591))
- fix(docs): make site builds idempotent ([3275365](https://github.com/deepseek-ai/deepseek-harness/commit/327536548))
- fix(web): preserve question drafts across Session switches ([2c90710](https://github.com/deepseek-ai/deepseek-harness/commit/2c9071038))
- fix(notices): restore the SDK 0.3.241 platform payload rows ([f20f016](https://github.com/deepseek-ai/deepseek-harness/commit/f20f0161a))
- fix(notices): restore the SDK version the lockfile installs ([87ac9f5](https://github.com/deepseek-ai/deepseek-harness/commit/87ac9f5be))
- fix(web): adopt authenticated scaffold URL and post-merge golden in feedback-release lane ([66f2938](https://github.com/deepseek-ai/deepseek-harness/commit/66f2938b6))
- fix(feedback): address review — accurate release wording, current-state notes, default-mode snapshot lane ([ac4a2f9](https://github.com/deepseek-ai/deepseek-harness/commit/ac4a2f979))

### 🔄 Refactoring
- test(snapshot): restore canonical packed fixture layout ([c3904fa](https://github.com/deepseek-ai/deepseek-harness/commit/c3904faee))
- test(snapshot): re-record cordis-inspect-jsdoc after the seq-range projection ([ee42efb](https://github.com/deepseek-ai/deepseek-harness/commit/ee42efbcc))
- test(web): expect plugin cards to collapse after save ([d5787b1](https://github.com/deepseek-ai/deepseek-harness/commit/d5787b184))
- test(subagent): keep scoped fixture config explicit ([1c0e468](https://github.com/deepseek-ai/deepseek-harness/commit/1c0e46870))
- test(ui-settings-plugins): cover provider model grouping ([5a5e1b7](https://github.com/deepseek-ai/deepseek-harness/commit/5a5e1b737))
- test(subagent): type provider route defaults fixture ([a130273](https://github.com/deepseek-ai/deepseek-harness/commit/a13027343))
- test(ui-input-trigger): cover the onHover slot wiring; restore master's notices ([36dd657](https://github.com/deepseek-ai/deepseek-harness/commit/36dd657c7))
- test: give the dual-call built-bin cases a 150s outer budget ([075cfc3](https://github.com/deepseek-ai/deepseek-harness/commit/075cfc3b4))
- test: give the multi-call built-bin cases a 210s outer budget ([6cbd3dd](https://github.com/deepseek-ai/deepseek-harness/commit/6cbd3dda2))
- test: unify the last Windows spawn budgets to the 90s pattern ([b648ed7](https://github.com/deepseek-ai/deepseek-harness/commit/b648ed75c))
- test: raise the contended Windows spawn budgets to 90s ([8469204](https://github.com/deepseek-ai/deepseek-harness/commit/84692044a))
- test: align built-bin spawn budget with its outer case budgets ([c20cfe7](https://github.com/deepseek-ai/deepseek-harness/commit/c20cfe77c))
- test: widen oxlint contract and built-bin spawn budgets ([e9cb003](https://github.com/deepseek-ai/deepseek-harness/commit/e9cb003e9))
- test(web): derive the editable gate from the gesture target ([21e5ee9](https://github.com/deepseek-ai/deepseek-harness/commit/21e5ee907))
- test(web): drain trajectory scroll timer before teardown ([ac36c6b](https://github.com/deepseek-ai/deepseek-harness/commit/ac36c6b97))
- test(webworker): keep dependency coverage generic ([f2cc573](https://github.com/deepseek-ai/deepseek-harness/commit/f2cc573eb))
- test(web): drive preset slash catalog with gestures ([00c37f4](https://github.com/deepseek-ai/deepseek-harness/commit/00c37f4ea))
- test(session-projection-cache): drive interval deterministically ([459919d](https://github.com/deepseek-ai/deepseek-harness/commit/459919d21))
- test(web): wait for editable permission composer ([b8360ca](https://github.com/deepseek-ai/deepseek-harness/commit/b8360cac5))
- test(subagent): cover Remote control migration ([91fea67](https://github.com/deepseek-ai/deepseek-harness/commit/91fea6774))
- refactor(api-session-controller): route subagent calls through Remote ([cbe5d76](https://github.com/deepseek-ai/deepseek-harness/commit/cbe5d76e5))
- test(web): target the editable command composer ([f95cbca](https://github.com/deepseek-ai/deepseek-harness/commit/f95cbca9c))
- test(web): await editable composer between turns ([2831054](https://github.com/deepseek-ai/deepseek-harness/commit/2831054b9))
- test(client): cover instant image echo branches ([2dd59b2](https://github.com/deepseek-ai/deepseek-harness/commit/2dd59b2ca))
- test(web): gate composer gestures on the editable attribute ([94e3bfd](https://github.com/deepseek-ai/deepseek-harness/commit/94e3bfd5d))
- test(workflow-worker-thread): budget startup waits for the contended Windows pool ([2a1a260](https://github.com/deepseek-ai/deepseek-harness/commit/2a1a2605d))
- test: exactOptionalPropertyTypes 下的 onRetire 捕获类型 ([c01cf6e](https://github.com/deepseek-ai/deepseek-harness/commit/c01cf6e54))
- test(web): 提交回显的组装路径 e2e 与不可见标记 ([f1606e3](https://github.com/deepseek-ai/deepseek-harness/commit/f1606e31d))
- test+docs: 回显生命周期、去重与预览移交的覆盖，README 与 Agent Note ([1da466a](https://github.com/deepseek-ai/deepseek-harness/commit/1da466a0a))
- test: 修复回显契约扩散到的类型化 fake 与断言 ([5657066](https://github.com/deepseek-ai/deepseek-harness/commit/5657066b1))
- test(agent-presets): cover the Remote migration ([c5be998](https://github.com/deepseek-ai/deepseek-harness/commit/c5be99838))
- refactor(ui-agent-preset): consume the preset Remote ([ef1c812](https://github.com/deepseek-ai/deepseek-harness/commit/ef1c812d9))
- refactor(agent-presets): expose browser operations through Remote ([306419c](https://github.com/deepseek-ai/deepseek-harness/commit/306419cc8))
- test(persistence): retain primitive log-only coverage ([e7522ad](https://github.com/deepseek-ai/deepseek-harness/commit/e7522ad39))
- refactor(session): require known event types on read ([42dc2a4](https://github.com/deepseek-ai/deepseek-harness/commit/42dc2a46c))

### 📝 Documentation
- docs(webworker): define createRequire reachability limits ([437ab3c](https://github.com/deepseek-ai/deepseek-harness/commit/437ab3cef))
- docs(web): clarify worker globals and HMR polling ([ba54d72](https://github.com/deepseek-ai/deepseek-harness/commit/ba54d722a))
- docs(webworker): define createRequire reachability ([b588cdc](https://github.com/deepseek-ai/deepseek-harness/commit/b588cdc47))
- docs(subagent): regenerate Remote references ([64575de](https://github.com/deepseek-ai/deepseek-harness/commit/64575de65))
- docs: refresh Claude SDK notices ([7817ed3](https://github.com/deepseek-ai/deepseek-harness/commit/7817ed3d8))
- docs(agent-presets): refresh @Remote migration references ([5752b1d](https://github.com/deepseek-ai/deepseek-harness/commit/5752b1dc3))
- docs(team): adopt package README standard ([d0eb02c](https://github.com/deepseek-ai/deepseek-harness/commit/d0eb02c20))
- docs(session): align SQLite schema evidence ([0d551b9](https://github.com/deepseek-ai/deepseek-harness/commit/0d551b9f5))
- docs(agent-team-profile): adopt package README standard ([a28f543](https://github.com/deepseek-ai/deepseek-harness/commit/a28f543ae))

### 🔧 Configuration
- ci: isolate non-Windows pnpm setup per run attempt ([2413eab](https://github.com/deepseek-ai/deepseek-harness/commit/2413eab84))
- ci(build-exe): drop pull_request label trigger to avoid skipped checks ([91379e8](https://github.com/deepseek-ai/deepseek-harness/commit/91379e8de))
- ci: drop the stale pnpm setup cleanup steps ([43b5b47](https://github.com/deepseek-ai/deepseek-harness/commit/43b5b473b))
- ci: isolate the Windows pnpm setup destination per job ([e87a476](https://github.com/deepseek-ai/deepseek-harness/commit/e87a47692))
- perf(hmr): poll client bundles only ([1429737](https://github.com/deepseek-ai/deepseek-harness/commit/1429737a5))
- ci(windows): restore complete coverage sharding ([dc82511](https://github.com/deepseek-ai/deepseek-harness/commit/dc8251149))
- chore(release): drop the unused synchronous runner ([b342b09](https://github.com/deepseek-ai/deepseek-harness/commit/b342b0940))
- ci(release): pack rehearsal tarballs concurrently ([f18ab42](https://github.com/deepseek-ai/deepseek-harness/commit/f18ab429e))
- ci(windows): clear stale pnpm setup state before install ([e1c49da](https://github.com/deepseek-ai/deepseek-harness/commit/e1c49dab5))
- chore: regenerate third-party notices for claude-agent-sdk 0.3.241 ([e8c2423](https://github.com/deepseek-ai/deepseek-harness/commit/e8c2423f5))

## 2026-08-27

**88 commits.** 12 feature changes, 34 fixes.

### 🆕 New Features
- feat(session-export): own the download route ([17c03bb](https://github.com/deepseek-ai/deepseek-harness/commit/17c03bbbc))
- feat(connection): register exact Fetch routes ([e5e4b02](https://github.com/deepseek-ai/deepseek-harness/commit/e5e4b0274))
- feat(ui-conversation): fold turn process before final answer ([8b09a0b](https://github.com/deepseek-ai/deepseek-harness/commit/8b09a0be5))
- feat(inspector): add the development mount overlay and demo script ([15572dd](https://github.com/deepseek-ai/deepseek-harness/commit/15572ddb2))
- feat(inspector): expose Cordis trees through CDP DOM ([28cc3e9](https://github.com/deepseek-ai/deepseek-harness/commit/28cc3e930))
- feat(inspector): project Host fetches through CDP Network ([7ecd700](https://github.com/deepseek-ai/deepseek-harness/commit/7ecd7004e))
- feat(inspector): serve Runtime through a CDP Worker ([bcee99e](https://github.com/deepseek-ai/deepseek-harness/commit/bcee99e39))
- feat(inspector): connect Host and Client producers ([19f0076](https://github.com/deepseek-ai/deepseek-harness/commit/19f007666))
- feat(inspector): define shared protocol foundation ([189fb34](https://github.com/deepseek-ai/deepseek-harness/commit/189fb3479))
- feat(web): trim @ mention rows and cut their discovery cost ([97e0299](https://github.com/deepseek-ai/deepseek-harness/commit/97e0299f7))
- feat(api): serve settings through Remote controllers ([dd70c0c](https://github.com/deepseek-ai/deepseek-harness/commit/dd70c0c88))
- feat(workspace-controller): expose directory picking through Remote ([76dedd4](https://github.com/deepseek-ai/deepseek-harness/commit/76dedd486))

### 🐛 Bug Fixes
- fix(notices): restore the SDK 0.3.241 platform payload rows ([558b6d9](https://github.com/deepseek-ai/deepseek-harness/commit/558b6d919))
- fix(api): keep file-reference output in its project ([9fa8780](https://github.com/deepseek-ai/deepseek-harness/commit/9fa87800a))
- fix: build ([b0c44e5](https://github.com/deepseek-ai/deepseek-harness/commit/b0c44e54b))
- fix(file-reference): remove unused zod dependency ([2ff3a0c](https://github.com/deepseek-ai/deepseek-harness/commit/2ff3a0c09))
- fix(api): preserve native path opening behavior ([18ae39a](https://github.com/deepseek-ai/deepseek-harness/commit/18ae39a66))
- fix(settings): preserve config catalog source anchor ([72cf4fa](https://github.com/deepseek-ai/deepseek-harness/commit/72cf4fae8))
- fix(api): restore migrated remote coverage ([8125560](https://github.com/deepseek-ai/deepseek-harness/commit/812556040))
- fix(build): correct workspace dependency declarations ([6743017](https://github.com/deepseek-ai/deepseek-harness/commit/674301721))
- fix(inspector): address bootstrap review findings ([dc1be13](https://github.com/deepseek-ai/deepseek-harness/commit/dc1be1334))
- fix(infra): assert alias coverage and harden the generator entry guard ([c4c3c32](https://github.com/deepseek-ai/deepseek-harness/commit/c4c3c3293))
- fix(inspector): stabilize client bootstrap identity ([ac13b16](https://github.com/deepseek-ai/deepseek-harness/commit/ac13b16c0))
- fix: ci ([90cae21](https://github.com/deepseek-ai/deepseek-harness/commit/90cae21de))
- fix(inspector): classify the demo launcher and refresh the module graph ([1c1c0ad](https://github.com/deepseek-ai/deepseek-harness/commit/1c1c0adf6))
- fix(inspector): serve Cordis DOM levels on demand ([ef712e3](https://github.com/deepseek-ai/deepseek-harness/commit/ef712e300))
- fix(inspector): preserve responses after caller abort ([a031b95](https://github.com/deepseek-ai/deepseek-harness/commit/a031b95fd))
- fix(inspector): print the startup URL ([777489d](https://github.com/deepseek-ai/deepseek-harness/commit/777489dfc))
- fix(inspector): update Cordis DOM incrementally ([d6245fc](https://github.com/deepseek-ai/deepseek-harness/commit/d6245fc25))
- fix(inspector): preserve event stream replay order ([c5f34e8](https://github.com/deepseek-ai/deepseek-harness/commit/c5f34e8ad))
- fix(inspector): address protocol review findings ([5a5d5de](https://github.com/deepseek-ai/deepseek-harness/commit/5a5d5de94))
- fix(inspector): render captured event streams ([0954bad](https://github.com/deepseek-ai/deepseek-harness/commit/0954bad2b))
- fix(inspector): satisfy CI checks ([b1748f0](https://github.com/deepseek-ai/deepseek-harness/commit/b1748f0c5))
- fix(inspector): restore client console and response bodies ([daf3858](https://github.com/deepseek-ai/deepseek-harness/commit/daf385875))
- fix(tools): scope bash SDK example to its schema ([520bc3c](https://github.com/deepseek-ai/deepseek-harness/commit/520bc3ce7))
- fix(tools): keep PTC SDK calls inside run_code ([f9770e3](https://github.com/deepseek-ai/deepseek-harness/commit/f9770e34a))
- fix(subprocess): fence each signal against current process state ([9757224](https://github.com/deepseek-ai/deepseek-harness/commit/975722434))
- fix(web): preserve mixed ask-user results ([94d06e2](https://github.com/deepseek-ai/deepseek-harness/commit/94d06e23d))
- fix(subagent): tolerate policy-only preset states ([2722c20](https://github.com/deepseek-ai/deepseek-harness/commit/2722c202a))
- fix(web): keep question card props data-only ([49753b3](https://github.com/deepseek-ai/deepseek-harness/commit/49753b33f))
- fix(client): stop rebuilding the turn rail on every chat render ([c873fc9](https://github.com/deepseek-ai/deepseek-harness/commit/c873fc9d2))
- fix(subprocess): read the process table once per terminal poll ([32ddfcd](https://github.com/deepseek-ai/deepseek-harness/commit/32ddfcd89))
- fix: align model selection with current settings remotes ([e49e720](https://github.com/deepseek-ai/deepseek-harness/commit/e49e7202c))
- fix(web): date @ session rows by last activity, not creation ([c8e8f82](https://github.com/deepseek-ai/deepseek-harness/commit/c8e8f8249))
- fix(web): render readable ask-user transcripts ([94db8e8](https://github.com/deepseek-ai/deepseek-harness/commit/94db8e881))
- fix(web): reuse the preview Remote helper ([9fdbec0](https://github.com/deepseek-ai/deepseek-harness/commit/9fdbec00e))

### 🔄 Refactoring
- docs: point note references at the surviving RPC test homes ([84dd244](https://github.com/deepseek-ai/deepseek-harness/commit/84dd2447f))
- test(connection): allow  non-Error rejection fixture ([26f1eda](https://github.com/deepseek-ai/deepseek-harness/commit/26f1eda42))
- refactor(api): remove ApiProxy package ([4f00a8b](https://github.com/deepseek-ai/deepseek-harness/commit/4f00a8b82))
- refactor(connection): own RPC transport contracts ([e14d354](https://github.com/deepseek-ai/deepseek-harness/commit/e14d354e8))
- test(session-export): assign Host compiler face ([3b40a14](https://github.com/deepseek-ai/deepseek-harness/commit/3b40a1455))
- refactor(client): replace host description consumers ([40929d6](https://github.com/deepseek-ai/deepseek-harness/commit/40929d6e1))
- refactor(connection): carry Host facts with generations ([e036aae](https://github.com/deepseek-ai/deepseek-harness/commit/e036aae7c))
- test(api): align migrated client contracts ([89ee54e](https://github.com/deepseek-ai/deepseek-harness/commit/89ee54ebb))
- test(client): update remote session fixtures ([5f6293e](https://github.com/deepseek-ai/deepseek-harness/commit/5f6293e67))
- test(api): complete migrated Remote coverage ([88f2f0a](https://github.com/deepseek-ai/deepseek-harness/commit/88f2f0aae))
- test(api): refresh Remote migration artifacts ([160706b](https://github.com/deepseek-ai/deepseek-harness/commit/160706be6))
- refactor(apiproxy): retire migrated unary routes ([ce3391e](https://github.com/deepseek-ai/deepseek-harness/commit/ce3391e28))
- refactor(client): consume migrated Remote namespaces ([5b2f679](https://github.com/deepseek-ai/deepseek-harness/commit/5b2f679e4))
- refactor(api): expose remaining domain remotes ([2d4393d](https://github.com/deepseek-ai/deepseek-harness/commit/2d4393d84))
- test(file-reference-local): pin the unreadable-subtree test to POSIX non-root ([6ac1b82](https://github.com/deepseek-ai/deepseek-harness/commit/6ac1b8293))
- test(client-modules): type loader resolver stubs ([b46953f](https://github.com/deepseek-ai/deepseek-harness/commit/b46953f3c))
- refactor(infra): share one workspace walk between the alias collectors ([71b3c50](https://github.com/deepseek-ai/deepseek-harness/commit/71b3c5026))
- test(inspector): enforce execution-plane boundaries ([6822ad3](https://github.com/deepseek-ai/deepseek-harness/commit/6822ad3af))
- refactor(session-reference): label discovery from projections alone ([8e9da9d](https://github.com/deepseek-ai/deepseek-harness/commit/8e9da9deb))
- test(host): drain Include write queue in picker composition spec ([397fb92](https://github.com/deepseek-ai/deepseek-harness/commit/397fb929d))
- test(web): scope the aria age normalizer to the region that needs it ([db14361](https://github.com/deepseek-ai/deepseek-harness/commit/db1436137))
- test(web): refresh feedback release golden ([6107e10](https://github.com/deepseek-ai/deepseek-harness/commit/6107e10c2))
- test(api): type heterogeneous provider calls ([08176e6](https://github.com/deepseek-ai/deepseek-harness/commit/08176e662))
- test(api): avoid mixed Remote result inference ([fcba3bb](https://github.com/deepseek-ai/deepseek-harness/commit/fcba3bbac))
- refactor(apiproxy)!: remove settings and credentials RPCs ([fd7f206](https://github.com/deepseek-ai/deepseek-harness/commit/fd7f2065b))
- refactor(client): use settings Remote namespaces ([5918dd2](https://github.com/deepseek-ai/deepseek-harness/commit/5918dd205))
- refactor(apiproxy)!: remove directory-picker RPCs ([6e40876](https://github.com/deepseek-ai/deepseek-harness/commit/6e4087626))
- refactor(client): use directory-picker Remote ([011d538](https://github.com/deepseek-ai/deepseek-harness/commit/011d53862))
- refactor(directory-picker): expose client-safe listing types ([3007864](https://github.com/deepseek-ai/deepseek-harness/commit/3007864cf))

### 📝 Documentation
- docs: re-record pairing hashes after the master rebase merge ([cf12723](https://github.com/deepseek-ai/deepseek-harness/commit/cf12723ba))
- docs(api): describe Connection-owned transport ([e57e7c3](https://github.com/deepseek-ai/deepseek-harness/commit/e57e7c3f2))
- docs: refresh module graph ([ea07f46](https://github.com/deepseek-ai/deepseek-harness/commit/ea07f465a))
- docs(client-modules): align resolver contract ([827acd0](https://github.com/deepseek-ai/deepseek-harness/commit/827acd07b))
- docs: link Cordis paper on arXiv ([35ac64c](https://github.com/deepseek-ai/deepseek-harness/commit/35ac64c20))
- docs: align the module graph translation pair ([3f4a6a2](https://github.com/deepseek-ai/deepseek-harness/commit/3f4a6a269))
- docs(inspector): record cross-realm architecture ([008ae0c](https://github.com/deepseek-ai/deepseek-harness/commit/008ae0c01))
- docs: refresh module dependency graph ([a7b054b](https://github.com/deepseek-ai/deepseek-harness/commit/a7b054b8f))
- docs(api): refresh configuration type records ([f3e16c9](https://github.com/deepseek-ai/deepseek-harness/commit/f3e16c9bc))
- docs(api): record settings Remote migration ([0a9a9ee](https://github.com/deepseek-ai/deepseek-harness/commit/0a9a9ee68))
- docs(directory-picker): record the Remote transport ([54d77ef](https://github.com/deepseek-ai/deepseek-harness/commit/54d77eff0))

### 🔧 Configuration
- style(apiproxy): remove stale spacing ([f19c251](https://github.com/deepseek-ai/deepseek-harness/commit/f19c25123))

### 📦 Dependencies
- perf(infra): map each workspace package to an explicit path alias ([12c161e](https://github.com/deepseek-ai/deepseek-harness/commit/12c161e1a))

## 2026-08-28

**3 commits.** 0 feature changes, 0 fixes.

### 📝 Documentation
- docs: sync remaining code mode-value prose to ptc in notes and spill README ([188d77e](https://github.com/deepseek-ai/deepseek-harness/commit/188d77ed4))
- docs(zh): sync remaining code mode-value prose to ptc ([b7c71d8](https://github.com/deepseek-ai/deepseek-harness/commit/b7c71d805))

### 🔧 Configuration
- release(dsh): 0.1.2-alpha.1 ([6c705be](https://github.com/deepseek-ai/deepseek-harness/commit/6c705be1c))
