<img src="assets/signature-2.svg" width="44" height="44" alt="MSDOS10" />

# MSDOS10

**Independent Software & Systems Engineer**

I build software that has to hold up on real machines: automation across devices that were never meant to cooperate, applied AI with a gate around the model, and native systems with a measurement beside the claim.

Automation · Applied AI · Native systems

[Portfolio](https://toskaman.github.io/) · [Contact](#contact)

## Selected work

### [OpenBridge](https://github.com/toskaman/openbridge)

Connects devices that were never built to work together, and runs an action only after validation, approval, and a read-back.

Showcased runs are labeled as hardware, a virtual machine, an emulator, or a simulation.

Release [v0.3.2](https://github.com/toskaman/openbridge/releases/tag/v0.3.2). The device log records 37 verified rows: 28 on real hardware, 7 on guest VMs, 2 on official emulators. CI on main was green on 9 Nov 2026. PolyForm Strict 1.0.0.

[Evidence](https://github.com/toskaman/openbridge/blob/main/docs/DEVICE_EVIDENCE.json) · [Demo](https://youtu.be/TZaxCcRmrLQ)

### [GENESIS RT](https://github.com/toskaman/genesis-rt)

Turns a constrained machine description into QNX-native control software, injects faults, and writes a verdict that can be checked offline.

A requirement change should leave a trace, not a screenshot.

The repository reports 16/16 on the current on-target matrix, QNX 8 in QEMU x86_64. Host CI was green on 10 Nov 2026. No physical board. No safety certification. [Apache-2.0](https://github.com/toskaman/genesis-rt/blob/main/LICENSE).

[Claims](https://github.com/toskaman/genesis-rt/blob/main/docs/CLAIMS.md)

### [Anticipate](https://github.com/toskaman/anticipate-codegeist-2026)

Checks a risky Jira change before it ships: what depends on it, which option is safer, and whether that evidence has changed since approval.

Built for the ticket that looks local and breaks something two links away.

Atlassian Forge app. Recorded as production 4.3.0 on the owner's Jira site, 10 Nov 2026, with CI green on that main revision. Codegeist 2026 entry. No award is announced. Joint work with Orphee.

[Evidence](https://github.com/toskaman/anticipate-codegeist-2026/blob/main/docs/evidence/EVIDENCE_PACK.md)

## Other work

**[OpenKF](https://github.com/toskaman/OpenKF)** — 64-bit Killing Floor client in Rust: retail protocol, Vulkan, Steam auth. One author-measured headless run on 30 Oct 2026 reported 671 fps and a 0.14 s load on an RTX 4060 Ti; the retail client was at its 120 fps cap. [Method and limits](https://github.com/toskaman/OpenKF/blob/main/docs/BENCHMARKS.md). GPL-3.0. Requires a licensed copy of the game.

**[Orpane](https://github.com/toskaman/orpane-proof-package)** — Lossless compression with a public bit-exact check against reference codecs. The encoder is closed, the ratio figures are author-measured, and the repository has no licence file.

**[Freenekit](https://github.com/toskaman/Freenekit)** — Windows monitor for a Freebox: bandwidth and network state. Release [v1.0.0](https://github.com/toskaman/Freenekit/releases/tag/v1.0.0). No licence file in the repository.

**[BridgeWindows](https://github.com/toskaman/BridgeWindows-v4)** — Multi-PC agent bridge with an HMAC handshake. The channel is authenticated and still plaintext, for a trusted LAN. No GitHub release and no licence file.

**[PHOENIX](https://github.com/toskaman/UGREEN-PHOENIX)** — Recovery checks for a UGREEN NAS project, using fixed evidence labels. The official static checker passed. A run on real NAS hardware is not in the repository yet.

## Range

**Systems** — Rust, C, C++, Vulkan. Native clients, generated control code, measured runtimes.

**AI and automation** — Local inference, device integration, and a deterministic gate when a model is wrong.

**Product engineering** — Python, TypeScript, Electron, Atlassian Forge.

## Practice

- A number stays next to its revision, its method, and its limit.
- A model may propose. A deterministic check decides.
- Tests and CI travel with the result.
- Shared or missing rights are named before any commercial conversation.

## Contact

For collaboration, licensing, or acquisition, email [toskaman5962+portfolio@gmail.com](mailto:toskaman5962+portfolio@gmail.com).

[Discord](https://discord.gg/zNpj8ctH9p) — therealcopper. The server is a community. Email is the right channel for work.

AMD ROCm Certified Associate, earned 5 Nov 2026.

<details>
<summary>Licensing</summary>

- **OpenBridge** — PolyForm Strict 1.0.0 on current main. That licence limits use.
- **Anticipate** — proprietary, shared 50/50 with Orphee. A deal needs both holders. Write to info@lepcpro.fr.
- **GENESIS RT** — Apache-2.0.
- **OpenKF** — GPL-3.0-or-later. The clean-room statement is the author's. Any acquisition needs an IP review, and the game itself is not mine to license.
- **Orpane, Freenekit, BridgeWindows** — no licence file. Evaluation only, in writing.

Nothing on this page is an offer to sell a right that is shared, missing, or someone else's.

</details>
