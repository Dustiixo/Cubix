# Cubix — return to the OXsukra cognitive mesh without rewriting history
**Date:** 2026-10-28. **Status:** source publication blocked; checkpoint preserved.

The current repository contains a license and \`CHECKPOINT_M0_1.md\`, not the original compiler implementation. The canonical recovered candidate is the Git bundle named \`OXsukra_Cubic_Systems_Compiler_M0_1.git.bundle\`, with HEAD \`d2c4c36ad85c9ec75077c302e437d678a3c51658\`. Foundry CP-001/CP-002 recorded 22 tracked paths and 18 Linux Python tests passing against the recovered source, **not** this GitHub checkout. Original ancestry (three commits) is integral to source authenticity.

## Ordered work
1. Perform source/license/privacy review, verify the original bundle SHA from Foundry CP-002, ensure no uncommitted private data is being published.
2. On a Git-capable authenticated machine, publish **the original commit objects** on a separate import branch. Follow the reviewed Foundry script rather than reconstructing files through GitHub Contents API.
3. Compare original HEAD, tree SHA and commit ancestry against published branch; rerun tests from that branch; capture actual log.
4. Decide whether Cubix exposes pure operations to the cognitive mesh; capabilities are proposals until implementation and tests exist.
5. Add a versioned, read-only adapter first; no write access to global WRAP/Slotline/IXO state.
6. Preserve existing checkpoint document and use independent Release Controller gates.

**October 31 definition:** source review decision plus original-history publication **only if verified**, otherwise HOLD. No synthetic substitute source, fake package release or forced merge.

This PR updates planning documentation only.