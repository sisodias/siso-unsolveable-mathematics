# SISO Unsolveable Mathematics

Open-problem attack programme. Split out of the Great Library of SISO on
2026-08-07 with full commit history preserved; the Great Library remains a
catalog rather than a monorepo, and this is working research material.

## What is here

- `docs/unsolveable-mathematics-program.html` — the programme constitution.
- `docs/erdos-10-agent-master-prompt.md` — the ten-agent campaign master prompt.
- `docs/erdos-41-flagship-campaign-dossier.md` — the Erdős 41 flagship dossier.
- `docs/erdos-campaign-source-synthesis-2026-08-07.md` — campaign source synthesis.
- `docs/campaigns/erdos-10-2026-08-07/agents/09-23/` — agent 09's Erdős 23 workspace.

## Current manager lanes

The durable Erdős manager currently admits four lanes. These focused public
repositories contain the lane scope and evidence guardrails; this repository
remains the umbrella and historical programme record.

- [Erdős 742](https://github.com/sisodias/erdos-742) — proof-logging SAT and structural graph theory.
- [Erdős 647](https://github.com/sisodias/erdos-647) — arithmetic certificates and the modular frontier.
- [Erdős 23](https://github.com/sisodias/erdos-23) — structural proof and bounded order-43 verification.
- [Erdős 848](https://github.com/sisodias/erdos-848) — verification-only Lean replay and statement fidelity.

The manager is in a verification wave. No new target or broad compute should be
started until that wave converges; finite evidence and candidate arguments must
not be presented as general solutions.

## Standing of the Erdős 23 result

A **new candidate partial result**, not a solution. Conditional on a frozen
exact upstream certificate, the exact floor target holds for 147 orders through
200, including every order through 42; the first order not closed is 43.

There is no kernel-verified full proof, no counterexample, and no
novelty-verified resolution. The strongest unresolved objection is recorded in
`verdict.md`: the integral step to `beta(G) <= N^2/25` remains open in the odd-`K5`
obstruction class. Read `verdict.md` before citing anything here.

## Provenance

Cut from branch `agent/erdos-09-23` of `sisodias/great-library-of-siso`, which
was proven by `git merge-base --is-ancestor` to contain the other eleven Erdős
campaign refs. Registered as a Work in the Great Library with a
`source_repository` locator.
