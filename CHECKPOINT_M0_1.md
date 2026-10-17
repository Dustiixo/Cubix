# Cubix — verified M0.1 checkpoint

**Status:** Source recovery and verification completed; full source migration pending.

The authoritative candidate is the Git bundle `OXsukra_Cubic_Systems_Compiler_M0_1.git.bundle` in the owner's ChatGPT Library.

- HEAD: `d2c4c36ad85c9ec75077c302e437d678a3c51658`
- Parent history: `47652f7` → `cb27ab6` → `d2c4c36`
- 22 tracked source paths, including `cubic/core.py`, `cubic/cli.py`, tests, Linux/Windows launchers and MIT license
- Linux Python verification: `python -m unittest discover -s tests -q` — **18 tests passed**, rerun 2026-10-17
- Static credential-pattern review: no obvious secret found; this is not a comprehensive security audit

**Important:** This repository does not yet contain the recovered implementation. Do not interpret this checkpoint document as a release. The original bundle is retained to preserve commit objects and full ancestry during migration. No force-push or replacement source generated.

Next acceptance: import the original Git history, compare HEAD to `d2c4c36...`, rerun 18 tests on the published checkout and record a reproducible release tag.
