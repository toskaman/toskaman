<div align="center">

# Hi, I'm toskaman (MSDOS) 👋

### **Senior Systems & Low-Level Architect • Autonomous AI Fabrics • Engine Reconstruction**
*20+ years building high-performance native engines, zero-trust device fabrics, and verifiable AI systems.*

[![Portfolio](https://img.shields.io/badge/Live_Portfolio-toskaman.github.io%2Fmsdos-00f2ff?style=flat-square&logo=googlechrome&logoColor=white)](https://toskaman.github.io/msdos/)
[![Discord](https://img.shields.io/badge/Discord-therealcopper-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/zNpj8ctH9p)
[![Email](https://img.shields.io/badge/Email-toskaman5962%2Bportfolio%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:toskaman5962+portfolio@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%40toskaman-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/toskaman)
[![Security](https://img.shields.io/badge/Audits-0%2F72_VirusTotal_Clean-brightgreen?style=flat-square&logo=virustotal&logoColor=white)](#-security-integrity--clean-room-standards)

---

> **"I care about things that work on real hardware, with empirical proof, not promises."**  
> Every architecture I build is verified through bit-exact comparisons, regression suites, and physical hardware read-backs.

</div>

---

### 📊 Engineering Evidence at a Glance

| Metric | Measured Value | Verification Benchmark / Scope |
| :--- | :---: | :--- |
| **OpenBridge CI Verification** | **820+ Passing Tests** | Windows + Linux CI matrix, deterministic safety gates |
| **OpenBridge Hardware Records** | **37 Verified Records** | 28 physical devices, 7 VM guests, 2 official emulators |
| **OpenKF Frame Rate** | **671 FPS** | Solo KF-WestLondon vs 120 FPS retail hard engine cap |
| **OpenKF Map Loading Time** | **0.14 s** | ~24x faster than retail v1065 (3.32 s) via memory-mapped pools |
| **Orpane Lossless Compression** | **53/53 Benchmark Wins** | 100% win rate vs 7-Zip 26.02 `-mx9` on Silesia corpus (+2.4 MB saved) |
| **RBX Manager 2 Active Community** | **10,000+ Members** | Windows multi-account management with 0/72 clean VirusTotal |
| **RBX Manager 2 VRAM Reduction** | **-84% per instance** | Custom 320x240 micro-window rasterization vs standard 800x600 |
| **Anticipate Graph Engine Latency** | **18 ms / 100 nodes** | Deterministic transitive impact simulation for Jira Cloud (Codegeist 2026) |
| **BridgeWindows-v4 E2E Test Suite** | **23/23 Passing (100%)** | Mutual HMAC-SHA256 protocol, zero secrets on wire, multi-PC routing |
| **Firefall PIN MMO Server Tests** | **164 Passing Tests** | Full server reconstruction (.NET 9, Matrix/GSS protocol, BepuPhysics v2) |

---

## 🚀 Flagship Engineering Achievements

### 1. 🌐 [OpenBridge](https://github.com/toskaman/openbridge) — Local Meta AI Device Fabric
*Solo entry for the **Meta Global AI Developer Hackathon 2026** (Indie Track, Push the Frontier)*

* **The Vision**: Turn heterogeneous, disconnected household and network hardware into an intelligent, unified fabric where Meta AI models dynamically compose verified cross-device capabilities.
* **Core Architecture**:
  * **Tiered Local Inference**: Local Muse Glimmer (30B) and Llama 3.2 models for request understanding, planning, and on-demand UI synthesis; optional hosted Meta Muse Spark for held-out tasks.
  * **Deterministic Enforcement Gate**: Every AI proposal must clear fingerprint-bound approval, capability validation, and read-back verification before execution.
  * **Multi-Transport Fabric**: Zero-configuration discovery via mDNS, SSDP, router ARP/DHCP tables, ADB, and BLE relays bridging isolated subnets.
  * **Transactional Undo Engine**: Reversible state machine with audit receipts for every physical and virtual action.
* **Empirical Validation**: 820+ automated CI tests, 37 hardware verification records (Android TV, Galaxy Watch7, Freebox Delta, Tuya vacuum, Windows PCs).
* **Stack**: `Python 3.12`, `Llama 3.2`, `Muse Glimmer 30B`, `ADB`, `Bluetooth LE`, `WebSockets`, `FastAPI`.

---

### 2. 🛡️ [Anticipate](https://github.com/toskaman/anticipate-codegeist-2026) — The Decision Firewall for Software Teams
*Built for **Atlassian Codegeist 2026** (Jira Cloud & Forge Platform)*

* **The Problem**: Large-scale agile teams suffer from blind dependency breaks, uncoordinated release merges, and cascading blocker chains.
* **The Solution**: An in-process Decision Firewall for Jira Cloud that intercepts proposed architectural changes, simulates transitive dependency graphs, and blocks high-risk disruptions before commits occur.
* **Key Innovations**:
  * **CORE 0.2.0 Engine**: High-speed deterministic graph simulator evaluating cycles, transitive blockers, and blast radiuses (100 nodes evaluated in ~18 ms).
  * **Prevention Passport**: Cryptographically hash-bound approval contracts ensuring plans cannot drift between sign-off and execution.
  * **Atlassian Rovo MCP Integration**: 3 read-only Model Context Protocol tools enabling Atlassian Rovo AI agents to audit dependency health.
* **Stack**: `TypeScript`, `React`, `Atlassian Forge`, `Zod`, `Vitest`, `Playwright`, `Tailwind CSS`.

---

### 3. ⚡ [OpenKF](https://github.com/toskaman/OpenKF) — Clean-Room Native 64-Bit Killing Floor Client
*High-performance modern game client in Rust with custom Vulkan renderer*

* **Clean-Room Engineering**: Completely fresh 64-bit implementation interfacing directly with retail Unreal Engine 2.5 (v1065) servers and assets without reusing retail binaries.
* **Technical Feats**:
  * **671 FPS vs 120 FPS Engine Cap**: Bypasses retail engine bottleneck, achieving 671 FPS solo and 236 presented FPS during heavy 155-actor multiplayer waves on RTX 4060 Ti.
  * **Sub-Second Map Loading (0.14 s)**: 24x faster than retail (3.32 s) using memory-mapped package parsing and shared GPU mesh pooling.
  * **Full Multiplayer Protocol**: Clean-room implementation of Unreal network replication, Steam authentication, RPC dispatch, and FastDL (`.uz2`) background streaming.
  * **Advanced Audio & Physics**: 2,839/2,839 custom game sounds decoded without fault; articulated Karma multi-body ragdolls and surface-projected decals.
* **Stack**: `Rust`, `Vulkan (ash)`, `Winit`, `Symphonia`, `PresentMon`, `GameSpy Protocol`.

---

### 4. 🛰️ [BridgeWindows-v4](https://github.com/toskaman/BridgeWindows-v4) — Hardened Multi-PC Remote Agent & Wire Protocol
*Scalable, resilient reverse-TCP administration agent for heterogeneous clusters*

* **Architecture**: A central master administers up to 8 concurrent Windows and Linux PCs over low-latency reverse-TCP connections.
* **Security & Auth**:
  * **Zero Secrets on Wire**: Mutual 4-step handshake proving pre-shared key (PSK) knowledge via HMAC-SHA256 (RFC 4231 test vectors) with mutual nonces.
  * **Per-Frame Session MACs**: Every payload is sealed with a unique session key derived from `SHA256(psk || agent_nonce || master_nonce)`.
* **3D Particle Voice Orb**:
  * Real-time audio/network-reactive particle sphere with Siri-style ribbons blitted into 32-bit DIBs via Windows GDI (or 24-bit unicode half-blocks on headless Linux terminals).
* **Test Verification**: 23/23 end-to-end tests passing (100%), including hot binary self-update and seamless auto-reconnect.
* **Stack**: `C/C++`, `Win32 API / GDI`, `Linux Musl`, `Python`, `HMAC-SHA256`, `Zig Cross-Toolchain`.

---

### 5. 📡 [Freenekit](https://github.com/toskaman/Freenekit) — Real-Time Network & Freebox OS Monitor for Windows
*Desktop network telemetry & infrastructure controller for Freebox OS*

* **High-Speed Monitoring**: Second-by-second throughput tracking for 10 Gbps Wi-Fi 7 connections (Freebox Ultra, Delta, Pop, Révolution).
* **Per-Process Bandwidth Breakdown**: Live attribution of downstream/upstream network traffic mapped directly to active Windows TCP connections (Chrome, Discord, Steam, games).
* **Security & Intrusion Alarms**: Native Windows toast notifications triggered on unrecognized MAC addresses joining the local subnet.
* **100% VirusTotal Clean**: 0/72 security detections on official binary release with full reproducible build scripts.
* **Stack**: `TypeScript`, `Electron`, `Vite`, `Freebox OS REST API (HMAC-SHA1)`, `Windows IP Helper API`.

---

### 6. 🎮 [RBX-Manager-2](https://github.com/toskaman/RBX-Manager-2) — High-Performance Roblox Account Manager (RAM)
*Leading multi-instance manager powering an active community of 10,000+ power users*

* **Byfron / Hyperion Anti-Cheat Integrity**: Closes the application mutex safely via native Win32 `DuplicateHandle` (`DUPLICATE_CLOSE_SOURCE`). **Zero DLL injection, zero memory hooking, 100% anti-cheat compliant**.
* **320x240 Micro-Window Architecture**: Bypasses the 800x600 window dimension constraint, slumping per-client VRAM load by ~84% to run dozens of farming instances concurrently on consumer GPUs.
* **Non-Intrusive Background Anti-AFK**: Custom virtual message dispatcher prevents 20-minute inactivity timeouts without stealing physical mouse or keyboard focus.
* **Enterprise-Grade Security**: Master-password-protected Windows DPAPI hardware-bound encryption for stored credentials.
* **Stack**: `C#`, `.NET 8/9`, `WPF`, `Win32 API`, `DPAPI`, `Discord Webhooks`.

---

### 7. 🗜️ [Orpane Lossless Compressor](https://github.com/toskaman/orpane-proof-package) — Advanced Codec Research
*Experimental lossless compression codec outperforming industrial benchmarks*

* **100% Benchmark Win Rate**: Beats 7-Zip 26.02 `-mx9` across all 53 benchmark files in the standard Silesia corpus (+2.4 MB net saved).
* **Cryptographic Verification**: Dual SHA-256 and BLAKE3 bit-exact verification ensuring zero data corruption or stream drift.
* **Published Rust Decompressor**: High-speed, standalone memory-safe decompression runtime published with full proof package.
* **Stack**: `Rust`, `Python`, `Information Theory`, `ANS / Huffman Entropy Coding`, `Dictionary Pre-filtering`.

---

### 8. ⚔️ Firefall PIN MMO Server — Full Clean-Room Server Reconstruction
*Private server reconstruction for Firefall on top of the Pirate Intelligence Network base*

* **Scope**: Complete solo reconstruction across 13 distinct phases: Matrix networking protocol, GSS actor replication, weapons combat, vehicle physics, dynamic economy, and guild systems.
* **Low-Latency Engine**:
  * **BepuPhysics v2**: High-performance spatial indexing, broadphase collision queries, and tick synchronization.
  * **4Hz Server AI Loop**: Dynamic behavioral trees and navmesh traversal for hundreds of hostile creatures.
* **Test Rigor**: 164 unit and integration tests validating packet serialization, movement reconciliation, and state persistence.
* **Stack**: `C#`, `.NET 9`, `BepuPhysics v2`, `UDP Networking`, `Matrix/GSS Protocol`, `SQLite`.

---

## 🛠️ Core Technical Arsenal

```
┌─────────────────┬────────────────────────────────────────────────────────────────────────┐
│ Domain          │ Technologies & Tools                                                   │
├─────────────────┼────────────────────────────────────────────────────────────────────────┤
│ Systems & Low-  │ Rust, C/C++, C# (.NET 9), Win32 API, GDI, Linux Musl, Zig, Vulkan     │
│ Level           │ Memory-Mapped I/O, DPAPI, Multi-threading, Hardware Telemetry          │
├─────────────────┼────────────────────────────────────────────────────────────────────────┤
│ AI & Autonomous │ Muse Glimmer 30B, Llama 3.2, Atlassian Rovo MCP, Model Context Protocol│
│ Fabrics         │ Deterministic Safety Gates, Tool Synthesis, Fingerprint Approval       │
├─────────────────┼────────────────────────────────────────────────────────────────────────┤
│ Network & Game  │ Unreal Engine 2.5 Protocol, Matrix/GSS, Reverse-TCP v4, HMAC-SHA256    │
│ Protocols       │ BepuPhysics v2, FastDL (.uz2), GameSpy, WebSocket, Freebox OS REST     │
├─────────────────┼────────────────────────────────────────────────────────────────────────┤
│ Web & Cloud     │ TypeScript, React, Vite, Node.js, Atlassian Forge, Electron, Tailwind  │
├─────────────────┼────────────────────────────────────────────────────────────────────────┤
│ Quality & QA    │ Vitest, Playwright, PresentMon, SHA-256/BLAKE3 Verification, GitHub CI │
└─────────────────┴────────────────────────────────────────────────────────────────────────┘
```

---

## 💼 Project Acquisition, Licensing & Senior Hiring

Are you looking for an experienced engineer who can solve intractable low-level problems, design resilient device fabrics, or build native high-throughput engines?

### What I Offer:
1. **Commercial Asset Licensing & Acquisition**:
   * Licensing rights, white-label versions, or source code acquisition for **OpenKF**, **RBX-Manager-2**, **BridgeWindows-v4**, or the **Orpane Codec**.
2. **Senior Staff / Principal Engineering Roles**:
   * Available for high-impact roles in Systems Engineering, Low-Level Architecture, Game Engine Development, and AI Infrastructure.
3. **Specialized Technical Consulting**:
   * Protocol reverse-engineering, anti-cheat compatibility audits, high-throughput network architectures, and custom Windows/Linux driver/agent development.

### 📬 Get in Touch

<div align="center">

[![Email](https://img.shields.io/badge/Direct_Email-toskaman5962%2Bportfolio%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:toskaman5962+portfolio@gmail.com)
[![Discord](https://img.shields.io/badge/Discord_Direct-therealcopper-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/zNpj8ctH9p)
[![Portfolio](https://img.shields.io/badge/Explore_Portfolio-Interactive_Showcase-00f2ff?style=for-the-badge&logo=googlechrome&logoColor=white)](https://toskaman.github.io/msdos/)

**Fastest response via Discord (`therealcopper`) or direct Email.**

</div>
