# Cubix source recovery and first publish gate

- Source artifact: `OXsukra_Cubic_Systems_Compiler_M0_1.git.bundle`,
  retained by the owner.
- Canonical original HEAD:
  `d2c4c36ad85c9ec75077c302e437d678a3c51658`.
- Parents: `47652f7` → `cb27ab6` → `d2c4c36`.
- Independent 2026-11-20 local check: 18 unit tests passed on Linux.
- Existing public `main` only has a checkpoint/LICENSE; **not** the
  source described by the bundle.

## Required

1. Use authenticated Git transport to restore the original commit objects
   to an isolated branch **without squashing, rebasing or rewriting** them.
2. Verify exact original HEAD, parents and source checksums against the bundle.
3. Review licensing, third-party assets and secret/personal-data patterns.
4. Rerun tests from the GitHub checkout, not a separately downloaded archive.
5. Open a source-review PR using an intentional history strategy for the
   existing checkpoint branch. Do not force-push or erase it.
6. Add first native Windows acceptance and distinguish unit-test pass from
   runtime/IDE integration.

Until all of that is true, report **source recovered; publication pending**.
