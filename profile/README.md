<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
<!-- Copyright (C) 2026 Thalles Campagnani -->

# NoBlobs DirtyTeam Organization

This is the Github organization of dirty team of NoBlobs. Here the repositories contain the investigation results of hardware and firmware behavior, and, because of it all repositories remains private.

The results are filtred by docsClean team and published at [`NoBlobs-docsClean`](https://github.com/NoBlobs-docsClean) organization.

Full documentation portal: <https://noblobs-docsclean.github.io>


## Clean-Room Architecture

Three-stage clean-room workflow:

1. **Hardware Analysis** ([`NoBlobs-dirtyTeam`](https://github.com/NoBlobs-dirtyTeam), this organization, private repositories) — Investigates hardware and firmware behavior in isolation.
2. **Public Specification & Audit** ([`NoBlobs-docsClean`](https://github.com/NoBlobs-docsClean)) — Filters and publishes fact-only hardware contracts, register maps, memory layouts, protocols, public ABIs, and empirically verified silicon behavior, with **no proprietary code, disassembly, decompiled symbols, internal strings, or binary blobs**.
3. **Independent Implementation** ([`NoBlobs`](https://github.com/NoBlobs)) — Consumes only these public specifications and open-source standards to build independent open-source firmware from scratch.

See the [Clean-Room Process & Firewall](https://noblobs-docsclean.github.io/clean-room/) for details.

---

## Licensing

All specifications are licensed under **Creative Commons Attribution-ShareAlike 4.0 International (`CC-BY-SA-4.0`)** and publish at [`NoBlobs-docsClean`](https://github.com/NoBlobs-docsClean).
