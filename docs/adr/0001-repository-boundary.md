<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
BITSTREAM-EVIDENCE-CI — repository foundation
-->

# Decision: separate FPGA build evidence from source projects and generic storage

## Context

A tool version string, successful process exit, report screenshot or synthesis checkpoint does not establish complete build provenance, final artifact identity, reproducibility or release eligibility. Existing source projects need independent consumers that retain these distinctions.

## Decision

Bitstream Evidence CI owns complete pin admission, version-specific build adapter, unique attempt capture, exact report interpretation, rebuild comparison and native build-history semantics. Libero is the first adapter. Source projects retain their actual RTL, constraints, generators, Tcl and CI. Shared evidence operations come from separately installed Evidence Manifest Toolkit; generic experiment storage remains with Experiment Ledger.

## Consequences

Repository controls can be qualified before vendor runtime exists. They cannot qualify absent builds or history. Actual vendor versions/formats, installed evidence provider, complete numerical cohorts, external acceptance policy and real consumers must be exercised before support is claimed. Rebuild comparison needs two actual existing attempts and immutable history needs actual state/recovery tests. Future hosted operation has a separate authority and lifecycle boundary.
