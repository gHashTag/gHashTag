# Dmitrii Vasilev — Ternary AI · FPGA · Custom Number Formats

> **I specialize in ternary models and designed GF-T — a ternary-native number format that beats comparable formats on benchmarks.**
>
> *I take that format from an arXiv paper to silicon — and make the neural network **train itself** on the FPGA. Math → spec → RTL → silicon → on-device ML, solo, on a fully open-source flow.*

**Open to remote contract work** · Ko Samui, Thailand 🌴 · UTC+7

**🎯 Looking for:** hardware-AI · ML-systems · FPGA / RTL roles — remote, full-time or contract
**🔨 Currently:** proving on-device neural-net *training* on FPGA — `.t27` spec → Verilog → silicon, bit-exact

📄 **Full CV / resume:** [CV.md](./CV.md)

[![Available for Hire](https://img.shields.io/badge/✅%20Available-Remote%20Contract-brightgreen?style=for-the-badge)](mailto:admin@t27.ai)
[![Email](https://img.shields.io/badge/Email-admin@t27.ai-blue?style=for-the-badge&logo=gmail)](mailto:admin@t27.ai)
[![Telegram](https://img.shields.io/badge/Telegram-@t27__lang-2CA5E0?style=for-the-badge&logo=telegram)](https://t.me/t27_lang)
[![Twitter](https://img.shields.io/badge/Twitter-@t27__dev-1DA1F2?style=for-the-badge&logo=twitter)](https://x.com/t27_dev)
[![arXiv](https://img.shields.io/badge/arXiv-2606.05017-b31b1b?style=for-the-badge&logo=arxiv)](https://arxiv.org/abs/2606.05017)
[![arXiv](https://img.shields.io/badge/arXiv-2606.09686-b31b1b?style=for-the-badge&logo=arxiv)](https://arxiv.org/abs/2606.09686)

---

## 🔬 Hire me for hardware-verified RTL

**Send your RTL — get it measured on a live Xilinx Artix-7, not simulated.**

You receive a signed report: bit-exact conformance against an *independent* reference model
(KAT vectors, not a testbench written from the same source), achieved timing and slack,
resource usage, a latch-free check, and the bitstream — produced on a fully open-source flow
(Yosys · nextpnr-xilinx · prjxray · openFPGALoader · iverilog), so **you can re-run every
number yourself without a vendor licence**.

- 🌐 **[t27.ai/verification](https://t27.ai/verification)** — full details, scope and terms
- 📄 **[Read a sample report](https://github.com/gHashTag/trinity/blob/main/docs/verification/SAMPLE-REPORT.md)** — real GF16 4×4 matmul on XC7A200T
- 📊 **[t27.ai/proof](https://t27.ai/proof)** — every measured result, and how it was verified
- 🔧 **[t27.ai/ip](https://t27.ai/ip)** — license a core that has already been to silicon
- 🎓 **[t27.ai/course](https://t27.ai/course)** — the same method taught: train a neural network on an FPGA
- 💵 From **$300** per core · 3–5 working days · **first module free**
- 🔒 Your sources are never published or reused, and are deleted on request. NDA welcome.
- 📬 **[admin@t27.ai](mailto:admin@t27.ai?subject=Hardware%20verification%20request)**

*Useful if you publish open-source IP, are preparing a tape-out, or need "measured on hardware"
numbers for a paper instead of simulation-only results.*

---

## 🔥 What I Do


I specialize in **ternary ML** — I design the number formats, the hardware that runs them, and the agent systems on top, from RTL to silicon.

- ⚡ **FPGA RTL** — custom float arithmetic, matmul cores, open-source toolchain (Yosys / nextpnr / XVC)
- 🧠 **ML Infrastructure** — CPU-optimized training, quantization, ternary neural nets in Rust
- 🤖 **AI Agent Systems** — multi-agent orchestration, MCP, Claude, RAG pipelines
- 📱 **React Native / TypeScript** — production apps and courses since 2016

---

## 🏆 Verified Results (2026)


| What | Numbers |
|---|---|
| **GF-T — best-in-class ternary format (mine)** | ternary-native GoldenFloat ladder (GF-T8/16/32) — **measured to beat comparable ternary formats** (≈3–5.5× vs tekum16, mid/far range) · no regime decode · native ternary exponent |
| **Neural net that _trains itself_ on FPGA** | on-chip SGD · binary + 3-class classification **100% held-out** · 2-layer ReLU solves **XOR** · every node **bit-exact** spec→silicon · open flow |
| GF16 4×4 matmul on FPGA | **323 MHz · 41.2 GOPS · 0 DSP48 · 0 latches** — running on hardware |
| TinyTapeout SKY130 ASIC | GDS ✅ · GL test ✅ · Precheck ✅ — chip tape-out path confirmed |
| Ternary LLM on $30 FPGA | **63 tok/s @ 1W** · 0 multipliers · open toolchain · [DOI](https://doi.org/10.5281/zenodo.18947017) |
| **tri-net — full ternary network stack (OSI / TCP-IP analog)** | 133 `.t27` specs · ternary GF16 PHY · BPSK modem over AD9361 · ETX mesh routing · AEAD crypto (ChaCha20-Poly1305 / X25519) · every layer formally specified & FPGA-synthesizable · **proven device-to-device over the air** |

---

## 📄 Papers


- **GoldenFloat: A Phi-Derived Static-Split Floating-Point Family from GF4 to GF1024 with a Lucas-Exact Integer Identity** — [arXiv:2606.05017](https://arxiv.org/abs/2606.05017)
- **An 83-Format Numeric Catalog with Bit-Exact Conformance Vectors: A Vendor-Neutral Reference for FP8, BF16, MXFP4, and Microscaling Formats** — [arXiv:2606.09686](https://arxiv.org/abs/2606.09686)

---

## 🏅 Competitions, grants & open-source

- **Google DeepMind AGI Hackathon 2026** — [`agi-hackathon`](https://github.com/gHashTag/agi-hackathon) evaluation framework
- **The Open League (TON)** — NeuroCalls meeting-analysis service
- **OpenAI Parameter Golf** — competition entry with novel **GF16 quantization** (Trinity Cognitive Stack): ~50% weight compression · ~3e-5 roundtrip error — [`parameter-golf-trinity`](https://github.com/gHashTag/parameter-golf-trinity)
- **DARPA CLARA** (PA-25-07-02) — submission: Trinity Cognitive Stack; 10 CLARA reasoning gaps realized in open-RTL silicon (TinyTapeout SKY130, 3 chips) — [`trinity-clara`](https://github.com/gHashTag/trinity-clara)
- **187 public repositories** — the **Trinity** ecosystem: ternary compute, FPGA, formal Coq/Rocq proofs, MCP servers, on-chain contracts

---


<details>
<summary><b>💼 Services & rates</b> &nbsp;— click to expand</summary>

## 💼 Services


| Service | Stack | Rate |
|---|---|---|
| FPGA RTL design & verification | Verilog, Yosys, nextpnr, openXC7, iverilog | **$60–100 /hr** |
| ML infra & custom float formats | Rust, Python, GF16, ternary quantization | **$60–90 /hr** |
| AI agent architecture | Claude, MCP, RAG, multi-agent orchestration | **$50–80 /hr** |
| React Native / TypeScript | RN, GraphQL, Supabase, Cloudflare Workers | **$40–70 /hr** |
| Technical consulting / architecture review | ML systems, FPGA, distributed compute | **$100+ /hr** |

> 📩 **[admin@t27.ai](mailto:admin@t27.ai)** · **[Telegram @t27_dev](https://t.me/t27_dev)** · Response within a few hours

</details>

---

<details>
<summary><b>🛠 Full technical stack</b> &nbsp;— click to expand</summary>

## 🛠 Technical Stack


```
FPGA / Hardware    Verilog · Yosys · nextpnr · prjxray · openXC7 · XVC/JTAG
                   openFPGALoader · Vivado · iverilog · SKY130 PDK · TinyTapeout

Systems / Research Rust · Zig · Coq · LaTeX · GF16 custom float · ternary logic
                   FPGA-validated arithmetic · open silicon flow

AI / ML            Claude Code · MCP · RAG · multi-agent systems · LLM training
                   CPU-optimized inference · neural net quantization

Web / Mobile       TypeScript · React Native · React · Node.js · GraphQL
                   Supabase · Cloudflare Workers · Gleam

Blockchain / Web3  Solana · Ethereum · ERC-20 · DeFi · DAO tokenomics
```

</details>

---

## 📂 Key Projects


| Repo | Description |
|---|---|
| [trinity-fpga](https://github.com/gHashTag/trinity-fpga) | GF16 matmul FPGA core — 323 MHz, TinyTapeout ASIC, ring oscillator clock |
| [tt-trinity-gf16](https://github.com/gHashTag/tt-trinity-gf16) | TinyTapeout TTSKY26a submission — GDS ✅ GL test ✅ Precheck ✅ |
| [zig-golden-float](https://github.com/gHashTag/zig-golden-float) | GF16 / TF3 custom float formats — bias=31, phi-structured |
| [t27](https://github.com/gHashTag/t27) | Spec-first language for ternary compute — 31 rings, [DOI](https://doi.org/10.5281/zenodo.19456875) |
| [trinity](https://github.com/gHashTag/trinity) | `tri` CLI · VSA · BitNet LLM · DePIN mesh inference |
| [trios](https://github.com/gHashTag/trios) | PhD Golden Chain — 42 chapters, golden-ratio physics constants |
| [trios-railway](https://github.com/gHashTag/trios-railway) | Railway MCP · IGLA orchestration in Rust |
| [trinity-clara](https://github.com/gHashTag/trinity-clara) | DARPA CLARA proposal · 84 Coq proofs |

---

<details>
<summary><b>📈 GitHub stats & Zenodo DOIs</b> &nbsp;— click to expand</summary>

## 📈 GitHub


[![Repos](https://img.shields.io/badge/Repositories-217%20total-blue?style=flat-square&logo=github)](https://github.com/gHashTag?tab=repositories)
[![Public](https://img.shields.io/badge/Public-187-blue?style=flat-square&logo=github)](https://github.com/gHashTag?tab=repositories)
[![Followers](https://img.shields.io/badge/Followers-89-lightgrey?style=flat-square&logo=github)](https://github.com/gHashTag?tab=followers)
[![Since](https://img.shields.io/badge/GitHub%20since-2014-informational?style=flat-square&logo=github)](https://github.com/gHashTag)

**217 repos (187 public + 30 private) · 89 followers · on GitHub since 2014**

> **Canonical resource list:** [t27.ai/#/resources](https://t27.ai/#/resources) — every paper, DOI,
> upstream patch, channel and identity, each with the date it was last verified. If this README
> and that page disagree, the page is right.

**Zenodo DOIs:**
- [10.5281/zenodo.19456875](https://doi.org/10.5281/zenodo.19456875) — GoldenFloat: φ-Optimal Floating-Point Formats for Ternary Computing (T27), v0.1.0
- [10.5281/zenodo.19227879](https://doi.org/10.5281/zenodo.19227879) — Trinity S³AI Framework — Complete Research Collection v5.0
- [10.5281/zenodo.18947017](https://doi.org/10.5281/zenodo.18947017) — Trinity v2.0.2 — FPGA Autoregressive Ternary LLM

</details>

---

<details>
<summary><b>🧾 Experience — 6 roles (FPGA/ML · Vibee · HAQQ · JS CAMP · LEELA · NeuroBlogger), 2015→now</b> &nbsp;— click to expand</summary>

## 🧾 Experience


| Period | Role |
|---|---|
| 2026 – now | FPGA/ML Research Engineer — GF16 matmul, TinyTapeout silicon, trinity-fpga |
| 2025 – now | VibeCoder Consultant @ [Vibee](https://999-web.vercel.app/academy) — AI agents, multi-agent architectures |
| 2024 – now | Founder — NeuroBlogger · NeuroCalls — voice & content AI agents |
| 2022–2023 | Senior React Native Developer @ HAQQ (UAE) — Islamic blockchain, team of 8 |
| 2016 – now | Founder — JS CAMP · JavaScript / React Native school |
| 2015 – now | Founder — LEELA Chakra AI · App Store + Google Play |

</details>

---

<details>
<summary><b>🎓 Education — PhD in progress · State Univ. of Management · AWS Community Builder</b> &nbsp;— click to expand</summary>

## 🎓 Education


- **PhD in progress** — *Golden Chain: Unification of Physical Constants via Golden Ratio* (2026–)
- **State University of Management, Moscow** — Management (2006)
- **AWS Community Builders** member

</details>

---

## 📬 Contact


| | |
|---|---|
| 📧 Email | [admin@t27.ai](mailto:admin@t27.ai) |
| 💬 Telegram | [@t27_dev](https://t.me/t27_dev) |
| 🐦 Twitter/X | [@t27_dev](https://x.com/t27_dev) |
| 📞 Phone | +66 (96) 2401-4170 |
| 📍 Location | Ko Samui, Thailand 🇹🇭 · Remote worldwide |

---

<sub>*φ² + φ⁻² = 3 · Building hardware that thinks*</sub>

---
