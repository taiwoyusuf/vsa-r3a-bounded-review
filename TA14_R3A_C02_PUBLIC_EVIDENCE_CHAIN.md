# TA-14 / VSA R3A-C02 — Public Evidence Chain

Purpose: expose a bounded, inspectable chronology for R3A/C02 without publishing the complete frozen evidence estate or implementation-sensitive material.

Publication rule: this record does not reconstruct, rerun, normalize, rewrite, or replace any frozen R3A evidence. It records identities, chronology, dispositions, and claim ceilings only.

## 1. Frozen R3A identity

The R3A master evidence estate was sealed before external review.

- R3A master-evidence-manifest SHA-256: 39c79046c5631e20d20867c9370c7ecb84ba63b7ee5649ca74b7e67ca8d5bc87
- Master seal UTC: 2026-08-29T16:58:25Z
- Frozen reviewer-package root: ffa6fc7d6ba755f01b3b287bbd8883e794562f787fbc1a55cbe2bff05f544213
- Reviewer-package seal UTC: 2026-08-29T17:05:53Z

These roots were already published in this repository before the later C02 inspection.

## 2. Public bounded review surface

The bounded R3A review surface was published to GitHub in commit:

2e6b4e147a0538d40c7aabd298e2081b9373bda0

Git commit time:

2026-08-29T18:32:27Z

The frozen submission intentionally stated that the complete physical/adversarial evidence estate was preserved separately and that external TA-14 determination was still pending.

That historical state is not rewritten by this later chronology.

## 3. Initial external disposition

TA-14's first external review of the public bounded surface treated the documentary surface as bounded and internally consistent, but did not treat the published evidence roots or narrative as independent proof of the underlying physical events.

The physical proposition therefore remained:

HOLD — INDEPENDENT PHYSICAL-EVIDENCE INSPECTION NOT YET ESTABLISHED

C02 was identified as the Independent Evidence Availability Boundary.

No adverse inference was drawn from evidence that had not yet been admitted for inspection.

## 4. C02 constituent-evidence exposure

A separate inspection surface was prepared as an exposure of the already-frozen R3A evidence, not as a new execution or reconstruction.

Identity anchors retained for that surface:

- C02 byte-identical transport-manifest root: 34f24b1cf2401069a631e9b7c7ba521a2f841b1c32916ce375448017d7b3ce57
- Sealed C02 archive SHA-256: f068d0ea0e9e81e66d011e70bafa2aec848f70bf7c728ef8ab03f2e2255fb2cf
- Immutable release tag: r3a-c02-inspection-v1
- Archive name: R3A-C02-INSPECTION-SURFACE.tar.gz
- Frozen constituent count: 125 regular files

The raw archive, private transport location, constituent filenames, recordings, evaluator internals, and implementation-sensitive material are intentionally not republished here.

## 5. Transport error and preserved HOLD

An initial inspection used GitHub's automatically generated repository source archive rather than the separately attached immutable Release asset.

That generated source archive did not contain the frozen constituent R3A evidence.

The transport error did not cause the HOLD to be removed.

The correct disposition remained HOLD until the intended constituent evidence was independently inspected.

No experiment was rerun or reconstructed to cure the transport error.

## 6. Later constituent inspection

The institutional determination record states that the intended sealed C02 archive, transport-manifest digest, R3A master-evidence-manifest digest, and 125-file constituent count independently reproduced the declared frozen identities.

The retained record is:

TA14_R3A_C02_Institutional_Determination_Record_v1.0.pdf

Record date:

30 August 2026

The public abstract is in:

TA14_R3A_C02_INSTITUTIONAL_DETERMINATION_PUBLIC_ABSTRACT.md

The complete determination PDF is deliberately not republished in this repository.

## 7. Final bounded disposition

The institutional disposition recorded after constituent inspection was:

- SUPPORTED — BOUNDED CONFIGURED PHYSICAL-WITNESS DEMONSTRATION
- R3A-C02 — SATISFIED
- configured-witness proposition: SUPPORTED — BOUNDED
- universal hidden-drift detection: NOT ESTABLISHED
- T4-E Run1 — NOT_ESTABLISHED / PRESERVED
- later Run2 does not retrospectively repair Run1

The determination did not grant materiality, admissibility, Validation Standing, authority, or action to the witness.

## 8. Public Git chronology of the final determination

COBIT-Chain later recorded the external institutional disposition without modifying the frozen R3A/C02 evidence:

- repository: taiwoyusuf/cobit-chain
- record: docs/provenance/TA14_R3A_C02_INSTITUTIONAL_DETERMINATION_2026-08-31.md
- commit: ca53bd34877c6a3964b32fafda50bc59db748749
- commit UTC: 2026-08-31T22:35:16Z
- final integration: PR #89, created 2026-08-31T22:36:23Z, merged 2026-08-31T22:36:37Z

## 9. What this public chain establishes

This public chain establishes a dated sequence of:

frozen evidence identity -> bounded public submission -> HOLD -> C02 constituent-evidence exposure -> later bounded inspection -> changed disposition -> preserved adverse result

It does not claim that every underlying evidence byte is public.

It does not convert a hash into proof of the event the hash represents.

It does not convert an institutional determination into regulatory certification, product validation, production qualification, or universal technical validity.

## 10. Evidence discipline

HASH IDENTITY != SEMANTIC TRUTH

PUBLIC NARRATIVE != PUBLIC VERIFICATION

INSPECTION RECORD != REGULATORY CERTIFICATION

LATER SUPPORT != RETROACTIVE REPAIR

PHYSICAL OBSERVATION != MATERIALITY != ADMISSIBILITY != VALIDATION STANDING != AUTHORITY != ACTION

The public record is intentionally no broader than the evidence and identities exposed.
