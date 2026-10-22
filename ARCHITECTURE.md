<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
BITSTREAM-EVIDENCE-CI — repository foundation
-->

# Architecture

## Current executable surface

The checkout contains repository validation tools, dedicated tests, workflow definitions and native documentation. No domain package, FPGA vendor driver, immutable build ledger or qualified build result is available. Repository metadata keeps domain capabilities and claims empty.

## Intended data flow

Complete source and toolchain admission produces an unsigned pin candidate. A separately installed evidence provider supplies the required detached seal. An owned version-specific adapter creates a unique bounded attempt, captures all required raw outputs and records failure or success honestly. Exact report interpretation precedes native entry construction. Independent comparison consumes two actual existing attempts; it performs no build.

## Ownership

This project owns build evidence, raw report interpretation, rebuild comparison and build-history semantics. Source projects own their RTL, constraints, generators and vendor scripts. Evidence Manifest Toolkit owns Common operations. Experiment Ledger supplies generic storage. Deploy Pack, Model Provenance, Recorder, Assurance and Studio consume versioned admitted evidence instead of substituting their own eligibility checks.

## Validity and recovery

The intended native entry has fifteen required root fields. Actual predecessor and sequence remain distinct from externally trusted genesis, head, range and attempt population. A consistent prefix cannot prove complete history. Compare-and-swap, replay/conflict, interrupted persistence and restoration need actual runtime tests before a durability claim.

Libero is first. A report-only stage cannot masquerade as final programming output. Complete numerical cohorts, external baseline/policy, actual rebuild and current provider qualification are required at their own boundaries. Further public details are in [the documentation architecture](docs/ARCHITECTURE.md).
