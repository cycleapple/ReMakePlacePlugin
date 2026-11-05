# API14 deep review — ReMakePlacePlugin

2026-11-06. Upstream status: `last-api14-before-project-upgrade`.
[Pinned upstream API14 evidence](https://github.com/RemakePlace/plugin/commit/375cf9dc365d10410141d0e5cd09c59aa11d1935)

Build reference: official stable Dalamud 14.0.5.1, distribution commit `6fb2b12018922bddeef009edd26082f068f8c602`.
This branch preserves TC features/resources and selectively ports compatibility changes; it does not claim complete feature parity with a newer upstream release.

The [central review](https://github.com/cycleapple/DalamudPlugins-TW-API14/blob/main/UPSTREAM_REVIEW.md) records source/delegate/layout/schema/SDK resolution/package/native-asset checks and their scope. Source declarations and successful compilation cannot prove scan signatures, IPC semantics, game data or native behavior in the TC client. TC API14 runtime validation remains pending.
