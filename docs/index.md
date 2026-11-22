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

This repository is preparing a tool for complete FPGA build evidence and independently checked rebuild decisions. Its current executable surface is repository validation tooling. It has no installed build-evidence package, public vendor runner or qualified bitstream result.

Bitstream Evidence CI is part of the **SC Neuromorphic Computing Systems** group (SC-NEUROMORPHIC-COMPUTING-SYSTEMS). The [group and project map](https://github.com/anulum/sc-neurocore/blob/main/docs/ecosystem.md) shows the whole programme and where this repository sits in it.

The intended workflow binds complete sources and toolchain, a unique attempt, raw reports, explicit outcome and final programming artifact. It preserves failed/incomplete attempts. Exact printed values, reproducible bytes, trusted history completeness and physical measurements require distinct evidence.

Read [Architecture](ARCHITECTURE.md), [validation tooling](validation-tooling.md), [data boundaries](THREAT_MODEL.md) and the [repository boundary decision](adr/0001-repository-boundary.md).
