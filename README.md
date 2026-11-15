# The ETHRAEON Build Loop

A white paper on recursive, agent-guided system assembly. It documents a controlled experiment in which AI agents consult each other openly while a person holds every handoff, built with the ETHRAEON Agent Kit v1.0.

[Read the paper](https://codepen.io/Jason-Fells/live/xbwZpNP/236670b8e72da6554efbe22b5da4887e)

## The Agent Kit

Thirteen core modules, an identity module and the `SOP-AUD-L1` review protocol, from the KAIROS Systems suite.

| Module | File | What it does |
|---|---|---|
| M0 | `m0-ethraeon_mod.md` | system identity, naming and output format |
| M1 | `m1-intake-framework.md` | intake, identity screening, normalization |
| M2 | `m2-spawning-engine.md` | instance generation with its starting rules |
| M3 | `m3-arbitration-logic.md` | decision review and escalation |
| M4 | `m4-runtime-orchestration.md` | execution routing |
| M5 | `m5-monitoring-kernel.md` | change monitoring and compliance signals |
| M6 | `m6-context-handoff-bridge.md` | context handoff with memory checks |
| M7 | `m7-translation-cultural-harmonization.md` | translation, tone and culture |
| M8 | `m8-feedback-self-evaluation.md` | feedback and learning |
| M9 | `m9-prompt-ops-kernel.md` | prompt routing and fallback |
| M10 | `m10-gtm-sector-logic.md` | go-to-market logic and documents |
| M11 | `m11-role-identity-kernel.md` | roles, user context and sessions |
| M12 | `m12-financial-contracts-kernel.md` | financial operations and contracts |
| M13 | `m13-scoping-output-layer.md` | scoping, rendering and delivery |
| `SOP-AUD-L1` | `sop-aud-l1-arbitration-protocol.md` | the review chain AFI, SOP-AIL, ABG |

The module files are not in this repository; it holds this README and the licence.

How the modules connect: M1, M2, M4 and M13 carry the basic flow. M3, M5 and M8 manage decisions. M11 binds identity to every module. M6 and M7 carry context and language.

## Findings

- Agents consult each other in the open, and each agent keeps its own identity and role.
- A person holds every handoff and can step in at any point.
- Every phase is recorded with a SHA-256 hash, so the record can be checked.
- Consent is asked for and recorded before agents work together.

The paper states its performance targets, among them intake under 50 ms.

## Citation

```
Fells, J. (2025). The ETHRAEON Build Loop: A Forensic Demonstration of
Recursive Agent-Guided System Assembly. Ethraeon Systems Advanced AI Research.
ORCID: https://orcid.org/0009-0008-8254-8411
Available at: https://github.com/jason-fells-research/Ethraeon-Build-A-Loop-Assembly
```

## Standards referenced

ISO/IEC 27001:2022, NIST AI RMF 1.0, ISO/IEC 23053:2022.

## Contact

- Research: jason.fells@pm.me
- Partnerships: info@ethraeon.systems
- ORCID: [0009-0008-8254-8411](https://orcid.org/0009-0008-8254-8411)

## Licence

Creative Commons Attribution 4.0 International. See `LICENSE.md`.

Jason Fells, ETHRAEON Systems. Copyright 2024-2026 ETHRAEON Systems.

Humanitas Ante Machinam.
