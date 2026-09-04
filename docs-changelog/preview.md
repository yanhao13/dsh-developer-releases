# Preview release: v0.1.2-alpha.1

Released: August 28, 2026

## Highlights

**Inspector devtools (CDP):** the new inspector package exposes full Chrome DevTools Protocol surfaces — DOM levels, Network, Runtime, Worker, and event stream replay — with a development mount overlay and demo launcher.

**API transport refactor:** ApiProxy retired; connection now owns RPC transport contracts, exact Fetch routes, and remotes. New api controllers (session, settings, workspace) and client-side migration of Remote namespaces.

**Package & bundle restructuring:** 25 new packages including webhook (github), win32-process, util/crypto, util/workspace-path, session-log-deepseek, inspector, webworker-*, client/ui-*, client/store, and bundle/* (acp-app, sdk-app, sdk-minimal). Many ui-* packages split for clearer ownership.

**PTC mode rename:** 'code' mode value replaced by 'ptc' (PTC mode) across docs (en/zh), tests, CLI reference, tool catalog, and runtime helpers. Session-persistent vocabulary preserved.

**Session export & file handling:** session export now owns the download route; file-reference output kept in-project; settings catalog source anchors hardened; notices SDK payload rows restored post-rebase.

## What's Changed

- refactor(api): retire ApiProxy; connection owns RPC transport and Fetch routes [#3235](https://github.com/deepseek-ai/deepseek-harness/pull/3235)

- feat(inspector): expose Cordis trees through CDP DOM, Network, Runtime, Worker; add dev mount overlay and demo [#3012](https://github.com/deepseek-ai/deepseek-harness/pull/3012)

- rename code-mode to ptc (PTC mode), except session-persistent vocabulary; sync docs/tests [#3074](https://github.com/deepseek-ai/deepseek-harness/pull/3074)

- feat(session-export): own the download route; register exact Fetch routes [#3217](https://github.com/deepseek-ai/deepseek-harness/pull/3217)

- feat(connection): register exact Fetch routes; keep file-reference output in its project; preserve native path behavior

- fix(api): restore migrated remote coverage; align client contracts after ApiProxy removal

- fix(inspector): stabilize client bootstrap, address review findings, preserve event stream order and caller-abort responses

- fix(notices): restore the SDK 0.3.241 platform payload rows after rebase

- perf(infra): map each workspace package to an explicit path alias; flatten tsconfig paths

- docs: refresh module graph; point note references at surviving RPC test homes; re-record pairing hashes post-rebase

- test(snapshot): restore canonical packed fixture layout; re-record cordis-inspect-jsdoc after seq-range projection

**Full Changelog:** https://github.com/deepseek-ai/deepseek-harness/compare/master@{8day}...master@{7day}
