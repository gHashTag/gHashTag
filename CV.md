# Dmitrii Vasilev — Curriculum Vitae

**Ternary AI · FPGA · Custom Number Formats** · Ko Samui, Thailand 🇹🇭 · Remote worldwide (UTC+7)
📧 [admin@t27.ai](mailto:admin@t27.ai) · 💬 [Telegram @t27_dev](https://t.me/t27_dev) · 🐦 [X @t27_dev](https://x.com/t27_dev) · 📞 +66 62 401 4170

> I take a novel number format from an arXiv paper to silicon — and make the neural network **train itself** on the FPGA. Math → formal spec → RTL → FPGA/ASIC → on-device ML → machine-checked proof. Solo, on a fully open-source flow.

---

## Summary

Ternary-AI systems research engineer who **specializes in ternary models** and owns the **whole chain**: number-format research, spec-first RTL, FPGA/ASIC bring-up, on-device ML, and formal verification. I designed **GF-T** — a ternary-native float format **measured to beat comparable ternary formats on benchmarks** (≈3–5.5× vs tekum16) — and the broader **GoldenFloat** φ-derived family (arXiv); built a spec-first compiler (`.t27` → Verilog, bit-exact), and proved a neural network that **trains itself on a live Artix-7** — using only open-source tools (Yosys / nextpnr / prjxray), no Vivado, no Docker. 10+ years shipping and teaching software (JS school, React Native, AI agents).

**Open to:** remote **hardware-AI · ML-systems · FPGA/RTL** roles — full-time or contract.

---

## Verified results (2026, on hardware)

- **Neural net that trains itself on FPGA** — on-chip SGD; binary + 3-class classification **100% held-out**; 2-layer ReLU solves **XOR**; every node **bit-exact** from `.t27` spec to silicon; open-source flow.
- **GF-T — my ternary number format, measured against five competitor formats from their specifications** — ternary-native GoldenFloat ladder (GF-T8/16/32), measured to beat comparable ternary formats (≈3–5.5× vs tekum16), no regime decode, native ternary exponent.
- **GF16 4×4 matmul on FPGA** — **synthesis figures on file (an earlier 323 MHz timing claim was withdrawn after review)**, running on hardware.
- **Ternary LLM on a \$30 FPGA** — **63 tok/s @ 1 W (an earlier "0 multipliers" claim was withdrawn after review)**, open toolchain — [DOI 10.5281/zenodo.18947017](https://doi.org/10.5281/zenodo.18947017).
- **TinyTapeout SKY130 ASIC** — GDS ✅ · gate-level test ✅ · precheck ✅ (tape-out path confirmed).

---

## Publications

- **GoldenFloat: A Phi-Derived Static-Split Floating-Point Family from GF4 to GF1024 with a Lucas-Exact Integer Identity** — [arXiv:2606.05017](https://arxiv.org/abs/2606.05017)
- **An 83-Format Numeric Catalog with Bit-Exact Conformance Vectors: A Vendor-Neutral Reference for FP8, BF16, MXFP4, and Microscaling Formats** — [arXiv:2606.09686](https://arxiv.org/abs/2606.09686)

**Zenodo DOIs:** [t27 language spec](https://doi.org/10.5281/zenodo.19456875) · [Trinity v9.0](https://doi.org/10.5281/zenodo.19227879) · [FPGA autoregressive LLM](https://doi.org/10.5281/zenodo.18947017)

---

## Experience

| Period | Role |
|---|---|
| 2026 – now | **FPGA / ML Research Engineer** — GF16 matmul, TinyTapeout silicon, `trinity-fpga`, on-device training |
| 2025 – now | **VibeCoder Consultant** @ [Vibee](https://999-web.vercel.app/academy) — AI agents, multi-agent architectures |
| 2024 – now | **Founder** — NeuroBlogger · NeuroCalls — voice & content AI agents |
| 2022 – 2023 | **Senior React Native Developer** @ HAQQ (UAE) — Islamic blockchain, team of 8 |
| 2016 – now | **Founder** — [JS CAMP](https://github.com/gHashTag/jscamp) — JavaScript / React Native school |
| 2015 – now | **Founder** — LEELA Chakra AI — App Store + Google Play |

---

## Education

- **PhD in progress** — *Golden Chain: Unification of Physical Constants via Golden Ratio* (2026–)
- **State University of Management, Moscow** — Management (2006)
- **AWS Community Builders** — member

---

## Selected projects

| Repo | Description |
|---|---|
| [trinity-fpga](https://github.com/gHashTag/trinity-fpga) | GF16 matmul FPGA core, TinyTapeout GDS (withdrawn before fabrication), ring-oscillator clock |
| [t27](https://github.com/gHashTag/t27) | Spec-first language for ternary compute — `.t27` → Verilog, bit-exact |
| [zig-golden-float](https://github.com/gHashTag/zig-golden-float) | GF16 / TF3 custom float formats — φ-structured |
| [trinity-s3ai](https://github.com/gHashTag/trinity-s3ai) | Hardware-verified research + Coq/Rocq machine-checked proofs |
| [tri-net](https://github.com/gHashTag/tri-net) | Ternary-native mesh network — routing + AEAD crypto, spec-first stack |
| [tt-trinity-gf16](https://github.com/gHashTag/tt-trinity-gf16) | TinyTapeout TTSKY26a submission — GDS ✅ GL test ✅ Precheck ✅ |
| [trinity](https://github.com/gHashTag/trinity) | `tri` CLI · VSA · BitNet LLM · DePIN mesh inference |
| [trinity-clara](https://github.com/gHashTag/trinity-clara) | DARPA CLARA proposal · 84 Coq proofs |

---

## Technical skills

```
Hardware      Verilog · Yosys · nextpnr · prjxray · openXC7 · openFPGALoader
              iverilog · JTAG/XVC · SKY130 PDK · TinyTapeout · GF16 float
Systems       Rust · Zig · Coq/Rocq · LaTeX · ternary logic · spec→silicon
              mesh networking · AEAD crypto · compilers
AI / ML       on-device training · quantization · Claude Code · MCP · RAG
              multi-agent orchestration · CPU-optimized inference
Web / Mobile  TypeScript · React Native · React · Node.js · GraphQL · Supabase
```

---

## Contact

| | |
|---|---|
| 📧 Email | [admin@t27.ai](mailto:admin@t27.ai) |
| 💬 Telegram | [@t27_dev](https://t.me/t27_dev) |
| 🐦 X / Twitter | [@t27_dev](https://x.com/t27_dev) |
| 📞 Phone | +66 62 401 4170 |
| 📍 Location | Ko Samui, Thailand 🇹🇭 · Remote worldwide |

<sub>φ² + φ⁻² = 3 · Building hardware that thinks</sub>
