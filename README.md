# Cubix — cubic systems compiler research

**Status: original source recovered and locally tested; GitHub source import
is still pending.** This repository must preserve the original Cubix identity
and commit history. It is not the IXO runtime, the DOOR renderer or a finished
general-purpose compiler.

## What exists

The owner-retained `OXsukra_Cubic_Systems_Compiler_M0_1.git.bundle` contains
a **three-commit** original source history:

| Revision | Role |
| --- | --- |
| `47652f7` | Original Cubic M0 baseline |
| `cb27ab6` | Hardened runner, CLI, tests and package metadata |
| `d2c4c36` | Release verification and platform-limitation record |

The bundle contains 22 tracked paths (including `cubic/core.py`,
`cubic/cli.py`, tests and Windows/Linux launchers). On **2026-11-20**,
its original HEAD `d2c4c36` passed **18 Python unittest methods**
in an isolated Linux workspace.

That source is **not** the current public repository tree. This README does
not claim the repository can be cloned and executed as Cubix yet. Consult
[the original checkpoint](CHECKPOINT_M0_1.md) and
[the source import gate](docs/SOURCE_RECOVERY.md).

## Intended boundary

Cubix explores cubic representation, parsing and build transformations with
explicit source/provenance checks. Any proposed language and music/spatial
representations need their **own** bounded tests; they are not compiler
features merely because they share OXsukra vocabulary.

After original history is imported, the basic test is:

```bash
python -m unittest discover -s tests -q
```

There is no published IDE plugin, native DAW adapter, GPU runtime, IXO
authority bridge or cross-platform production release evidenced here.
