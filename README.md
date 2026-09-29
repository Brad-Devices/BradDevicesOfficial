# Brad Devices

> Software before silicon. Receipts after that.

Brad Devices is a vertically-integrated computer company designing **silicon, memory, an operating system and the software that builds them** — under one roof, as one coherent plan.

- **Website:** <https://brad-devices.vercel.app>
- **Founder:** Festus Bradley Nyadimo ("The Architect")
- **Origin:** Built in Africa, for the World

---

## What this repo is

The public brand home for Brad Devices. It holds the logos, wordmarks and brand guidelines so the identity stays consistent everywhere it appears — and so the story is easy to link to, cite and share.

## The ecosystem

| Layer | What ships | What is designed |
|-------|-----------|------------------|
| **Toolchain** | `bradc` (assembler), `BVRT` (interpreter), `braddev` (CLI), `bradgdb` (debugger), `BradTimeline` (profiler) — all run today, verified in CI | — |
| **GPU software** | BradSense-Render M0 — spatial upscaler, measured 39.43 / 39.44 / 39.57 dB PSNR | M1–M4 temporal ladder queued |
| **CPU** | — | BradISA (instruction set), BradCore, BradChip (5 tiers), BradXon |
| **GPU** | — | Torox G1, BradGfx (discrete), BradFx (integrated), BradApex (datacenter) |
| **NPU** | — | BradNPU, NCC clusters, HB-AIM, AI-ISA, MoE |
| **Memory** | — | SPMP (unified pool), BradRAM (JEDEC dies + Brad controller), BradDrive, BradNAND |
| **OS** | — | BradOS, Kinetic Unified Driver, Brad-CVT |
| **Services** | BMS (reference server runs) | BradCloud, BradPay, BradMail, BradHub, BradGeo |

## The two rules

1. **Two ISAs, never one.** BradISA is the CPU. BradVector is the GPU. They meet on the BradFusion fabric and share SPMP memory — they do not share instructions.
2. **Receipts before promises.** Every claim carries a tag — SHIPPED (software runs today), DESIGNED (silicon designed), VISION (honest future) — and a link to verify it.

## Brand assets

| Asset | Location |
|-------|----------|
| Icon (SVG, white/black) | `assets/logos/` |
| Full logo (PNG) | `assets/logos/` |
| Wordmark (SVG, white/black) | `assets/wordmarks/` |
| Wordmark (PNG) | `assets/wordmarks/` |

See [`BRAND.md`](BRAND.md) for usage rules.

## Verify, don't take our word for it

The toolchain runs in your browser — open the [site](https://brad-devices.vercel.app/) and watch it assemble, execute and debug BradVector code. The receipts are the product.

---

*Brad Devices — a complete computer ecosystem, designed from one coherent plan.*
