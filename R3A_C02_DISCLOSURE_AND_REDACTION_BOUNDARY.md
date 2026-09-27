# R3A/C02 Public Disclosure and Redaction Boundary

## Objective

Expose enough provenance for an outside reader to inspect the chronology and evidence identities without unnecessarily disclosing protected implementation detail, private communications, personal information, security-sensitive material, or future intellectual-property strategy.

## Controlling rule

Do not alter the frozen original evidence in order to make it public.

Where public abstraction or redaction is necessary, the public artifact must be clearly identified as a derivative and must never be represented as the original frozen artifact.

## Publicly disclosed

This repository may disclose frozen evidence roots and package digests; seal dates and times already used as provenance; bounded proposition and claim ceiling; HOLD / SATISFIED chronology; preserved adverse-result status; Git commit identities; and the high-level institutional disposition.

## Deliberately withheld

The following remain non-public here unless separately reviewed and authorized:

- raw physical-observation evidence;
- complete frozen constituent evidence files;
- implementation-sensitive constituent manifests;
- evaluator source, algorithms, thresholds, or internal control logic not already deliberately public;
- private transport and access-control details;
- private direct-message screenshots and message metadata;
- personal contact information, home information, device serials, hostnames, internal addresses, credentials, secrets, or tokens;
- employer-confidential, customer-confidential, site-confidential, or regulated operational data;
- unpublished patent drafting, continuation strategy, future claims, trade-secret material, or implementation detail whose disclosure is not necessary to establish provenance.

## Original versus derivative

A redacted or summarized public file is a derivative public record.

It must not reuse an original artifact's hash as if the derivative were byte-identical.

The original hash remains an identity anchor for the original object only.

The derivative receives its own Git object and commit identity.

## Chronology preservation

The following historical states must remain visible: original frozen submission with external determination still PENDING; later external documentary review and HOLD; transport mistake; HOLD preserved despite explanation; constituent evidence later made inspectable; later bounded inspection; changed final disposition; earlier adverse T4-E Run1 preserved.

No later publication may rewrite an earlier state as though the later evidence had already existed.

## Intellectual-property boundary

Public provenance does not require publication of all implementation detail.

This repository is an evidence and review surface, not a complete implementation disclosure.

Publication of hashes, chronology, and bounded findings does not intentionally expand the technical disclosure beyond material selected for public examination.

## No certification implication

Nothing in this public package represents regulatory certification, validated production use, clinical validation, product certification, universal hidden-drift detection, autonomous execution authority, or endorsement by COBIT, ISACA, a regulator, or any employer.

The record remains bounded to the evidence and proposition stated.


## Architecture and provenance boundary

External examination does not transfer architecture ownership or authorship.

VSA / COBIT-Chain / RAMAT and TA-14 remain separately stewarded. This public package may identify TA-14's institutional examination and public findings, but it must not present TA-14 concepts, terminology, mechanisms, or independently developed work as originating in VSA / COBIT-Chain / RAMAT.

Likewise, similarity or later convergence does not by itself establish derivation in either direction.

Where a later refinement is materially sharpened by external work, the relevant provenance record should preserve the external source and exposure chronology.

A public hash, registration date, review date, or repository commit is evidence of that particular recorded event; it is not by itself a legal conclusion about inventorship, patent priority, ownership, or derivation.

## External-link integrity

A user-controlled summary must not substitute for an unavailable external institutional record.

Where an external institution maintains a public finding or registry page, this repository should link to the institution-controlled page when that improves independent inspectability without increasing protected technical disclosure.

If an external link later becomes unavailable or changes route, preserve the previously recorded identifier and chronology and mark the link state explicitly rather than silently replacing the missing institutional record with a stronger user-authored assertion.
