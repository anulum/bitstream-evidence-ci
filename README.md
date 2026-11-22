<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
BITSTREAM-EVIDENCE-CI — repository foundation
-->

# Bitstream Evidence CI

Bitstream Evidence CI is being built to preserve source-pinned FPGA build attempts, exact tool-reported metrics and independently checked rebuild decisions. This checkout contains repository validation tooling and documentation. Full foundation qualification is in progress. There is no installed build-evidence package, vendor build runner, public build-evidence command or qualified bitstream result.

Bitstream Evidence CI is part of the **SC Neuromorphic Computing Systems** group (SC-NEUROMORPHIC-COMPUTING-SYSTEMS). The [group and project map](https://github.com/anulum/sc-neurocore/blob/main/docs/ecosystem.md) shows the whole programme and where this repository sits in it.

## Boundary

This project owns the planned complete build-input admission, version-specific adapter, attempt capture, exact report interpretation, rebuild comparison and immutable build-history semantics. Evidence Manifest Toolkit owns shared evidence assembly and verification. Experiment Ledger owns generic experiment storage. Existing source projects retain their RTL, Tcl, generator and CI implementations.

Libero is the first intended vendor adapter. Later Vivado and Quartus adapters need their own actual source, tool, report and output-stage qualification. A synthesis checkpoint, netlist, presence/version probe or screenshot is not a successfully produced final programming artifact.

## Current tooling

Seven repository controls inspect metadata, source attribution, workflows, dependency alignment, native documentation, inventory and preflight orchestration. The selected native-tool bootstrap verifies development executable and licence bytes. The descriptor declares architecture-only maturity and empty implemented domain capability and claim inventories.

Use the exact development environment in [Contributing](CONTRIBUTING.md). Named entry points are make metadata, make source-provenance, make workflows, make dependencies, make docs, make inventory and make licence. Full CI/preflight belongs in CI or an explicitly admitted pre-push environment. See [Validation](VALIDATION.md) for scope and limits.

## Intended evidence

A complete future run binds exact input and environment identities, target and toolchain, a unique attempt, raw required reports, explicit success/failure and final artifact identity. Exact printed timing/resource/power values retain their complete cohorts and units. Release acceptance requires actual independently captured rebuild comparison and an external policy/baseline; recording a failed attempt remains a successful recording operation.

## Documentation and support

[Architecture](ARCHITECTURE.md), [support](SUPPORT.md), [security reporting](SECURITY.md) and [citation metadata](CITATION.cff) describe this checkout's scope. No hosted service, package release, DOI, public CI status, reproducible vendor build, device measurement or performance advantage is claimed.

## Licence

Source is licensed under [AGPL-3.0-or-later](LICENSE). A commercial licence is available through the contact in [NOTICE](NOTICE.md).

![ANULUM](docs/assets/anulum_logo_company.jpg)

![Fortis Studio](docs/assets/fortis_studio_logo.jpg)

## Text and data mining reservation
The rightsholder, Miroslav Šotek (ANULUM), expressly reserves the use of the
works in this repository for text and data mining, including the collection of
this content for, and its use in, training, fine-tuning or evaluating machine
learning and artificial intelligence models, in accordance with Article 4(3) of
Directive (EU) 2019/790 and the national provisions transposing it.

No permission for such use has been granted beyond what the licence in
`LICENSE` grants. This reservation does not change that licence: uses the
licence permits remain permitted on its terms, including its attribution and
share-alike conditions.

Reservation made on 2026-10-19. Requests for permission: contact the
rightsholder through the contact listed in this repository.
