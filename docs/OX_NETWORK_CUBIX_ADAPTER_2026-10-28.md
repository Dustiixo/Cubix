# Cubix network capability boundary
**Date:** 2026-10-28 **Status:** publication/source HOLD; future read-only adapter only.

The Cubix compiler's original Git history and exact recovered candidate HEAD are critical provenance. See [existing source reentry plan](OX_COGNITIVE_MESH_CUBIX_REENTRY_2026-10-28.md). Do not reconstruct a synthetic compiler in this repository or introduce network runtime code before the original branch is safely published and validated.

## Intended network role
Cubix may eventually describe typed reusable computational/structural operations and export deterministic *read-only capability descriptors* to OX Gateway. The Gateway requests, but cannot assume, explicit owner acceptance. Any actual compiler execution remains inside source-pinned Foundry/Build Factory boundaries with sandbox and verification.

Proposed manifest fields: `owner_id`, `capability_id`, `version`, `accepted_input_digest`, `output_contract`, `cost_limit`, `source_commit`, `evidence_policy`, `visibility` and `expires_at`. Descriptive metadata is not grant or executable script.

## Gates
1. Inspect original three-commit Git ancestry and license/secret history.
2. Publish original Git objects on an import branch only after review.
3. Prove source HEAD/tree and tests from imported branch.
4. Design a pure, side-effect-free capability manifest.
5. Test invalid inputs, duplicate requests, cancellation, no-network behavior and independent output verification.
6. Only then consider a bounded owner adapter.

**Current Git state:** no compiler/runtime networking implementation, no host acceptance. Only this planning file added.
