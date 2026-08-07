# Dmitrii Vasilev

### I take a novel number format from an arXiv paper to silicon — and make the neural network *train itself* on the FPGA.

Math → formal spec → RTL → FPGA/ASIC → on-device ML → formal proof. Solo, on a fully open-source flow.

**Open to remote roles & contract work** · Ko Samui, Thailand 🌴 · UTC+7

[![Available](https://img.shields.io/badge/✅%20Open%20to-Remote%20/%20Contract-brightgreen?style=for-the-badge)](mailto:admin@t27.dev)
[![Email](https://img.shields.io/badge/Email-admin@t27.dev-blue?style=for-the-badge&logo=gmail)](mailto:admin@t27.dev)
[![Telegram](https://img.shields.io/badge/Telegram-@t27__dev-2CA5E0?style=for-the-badge&logo=telegram)](https://t.me/t27_dev)
[![Twitter](https://img.shields.io/badge/X-@t27__dev-1DA1F2?style=for-the-badge&logo=twitter)](https://x.com/t27_dev)
[![arXiv](https://img.shields.io/badge/arXiv-2606.05017-b31b1b?style=for-the-badge&logo=arxiv)](https://arxiv.org/abs/2606.05017)
[![arXiv](https://img.shields.io/badge/arXiv-2606.09686-b31b1b?style=for-the-badge&logo=arxiv)](https://arxiv.org/abs/2606.09686)

---

## What makes me different

Most people do **one** of: number-format research, RTL, ML infra, or formal methods. I do the **whole chain**, and I close the loop on real hardware:

> **The network *is* the specification.** I write it in a tiny spec language (`.t27`), a compiler emits synthesizable Verilog, every node is proven **bit-exact** against an independent model, and it runs — and **learns** — on a live Artix-7. No Vivado, no Docker.

---

## 🏆 Verified on hardware (2026)

| What | Numbers |
|---|---|
| **Neural net that *trains itself* on FPGA** | on-chip SGD · binary + 3-class classification **100% held-out** · 2-layer ReLU solves **XOR** · every node **bit-exact** spec→silicon · open flow |
| GF16 4×4 matmul on FPGA | **323 MHz · 41.2 GOPS · 0 DSP48 · 0 latches** — running on hardware |
| Ternary LLM on a \$30 FPGA | **63 tok/s @ 1 W** · **0 multipliers** · open toolchain · [DOI](https://doi.org/10.5281/zenodo.18947017) |
| TinyTapeout SKY130 ASIC | GDS ✅ · gate-level test ✅ · precheck ✅ — tape-out path confirmed |
| Custom number format | **GoldenFloat** (φ-derived static-split float, GF4→GF1024) — [published](https://arxiv.org/abs/2606.05017) + measured to beat comparable formats |

*Full open-source silicon flow: Yosys · nextpnr-xilinx · prjxray · openFPGALoader · iverilog — built natively on macOS arm64.*

---

## 📄 Papers

- **GoldenFloat: A Phi-Derived Static-Split Floating-Point Family from GF4 to GF1024 with a Lucas-Exact Integer Identity** — [arXiv:2606.05017](https://arxiv.org/abs/2606.05017)
- **An 83-Format Numeric Catalog with Bit-Exact Conformance Vectors: A Vendor-Neutral Reference for FP8, BF16, MXFP4, and Microscaling Formats** — [arXiv:2606.09686](https://arxiv.org/abs/2606.09686)

---

## 🔧 Selected work

| Repo | What it is | Stack |
|---|---|---|
| **[t27](https://github.com/gHashTag/t27)** | Spec-first ternary language: `.t27` → Verilog / Rust / C, bit-exact, test-driven | Zig |
| **[trinity-fpga](https://github.com/gHashTag/trinity-fpga)** | Open FPGA synthesis infra — RTL to bitstream without vendor tools | Zig / Verilog |
| **[zig-golden-float](https://github.com/gHashTag/zig-golden-float)** | GoldenFloat16 — φ-optimized ML number formats | Zig |
| **[trinity-s3ai](https://github.com/gHashTag/trinity-s3ai)** | Hardware-verified research + **Coq/Rocq** machine-checked proofs | Rocq |
| **[tri-net](https://github.com/gHashTag/tri-net)** | Ternary-native mesh network — routing + AEAD crypto, spec-first (OSI-style stack in `.t27`) | Rust |
| **[trinity](https://github.com/gHashTag/trinity)** | The Trinity compute stack (ternary / φ-structured) | Zig |

---

## 🧭 Where I fit

- **Deep-tech / hardware-AI R&D** — number formats, quantization, BitNet-class accelerators, edge inference & on-device training
- **RTL / FPGA & open silicon** — spec-driven Verilog, verification, Yosys/nextpnr/prjxray/TinyTapeout flows
- **Formal-methods-adjacent systems** — spec-first design, bit-exact conformance, Coq proofs
- **Systems in Rust / Zig** — mesh networking, crypto framing, compilers
- **AI agent systems** — multi-agent orchestration, MCP, RAG (I ship with them daily)
- *Bonus:* 10 yrs communicating this stuff — ran a JS school ([JS Camp](https://github.com/gHashTag/jscamp)), React Native courses, and write the papers myself.

---

## 💼 Engagements

| Track | Best for | Rate |
|---|---|---|
| FPGA RTL design & verification | Verilog · Yosys · nextpnr · openXC7 · iverilog | **\$60–100/hr** |
| ML infra & custom float formats | Rust · Python · GF16 · ternary quantization | **\$60–90/hr** |
| Deep-tech research collaboration | novel arithmetic, edge-AI, formal specs | *let's talk* |
| AI agent architecture | Claude · MCP · RAG · multi-agent | **\$50–80/hr** |
| Architecture / technical review | ML systems · FPGA · distributed compute | **\$100+/hr** |

📩 **[admin@t27.dev](mailto:admin@t27.dev)** · **[Telegram @t27_dev](https://t.me/t27_dev)** · replies within a few hours

---

## 🛠 Stack

```
Hardware      Verilog · Yosys · nextpnr · prjxray · openXC7 · openFPGALoader
              iverilog · JTAG/XVC · SKY130 PDK · TinyTapeout · GF16 float

Systems       Rust · Zig · Coq/Rocq · LaTeX · ternary logic · spec→silicon
              mesh networking · AEAD crypto · compilers

AI / ML       on-device training · quantization · Claude Code · MCP · RAG
              multi-agent orchestration · CPU-optimized inference

Web / Mobile  TypeScript · React Native · React · Node · GraphQL · Supabase
```

<sub>φ² + 1/φ² = 3 · Trinity</sub>
