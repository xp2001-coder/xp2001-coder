<!-- The banner plays automatically. Keep its link on this page: GitHub otherwise opens the image viewer. -->
<p align="center">
  <a href="#!">
    <picture>
      <source media="(prefers-reduced-motion: reduce)" srcset="./assets/banner-static.png" />
      <img src="./assets/banner-v2.gif" alt="xp2001-coder — a black cat blinking in a gentle breeze, with a flowing scarf and softly rocking football and basketball" width="100%" />
    </picture>
  </a>
</p>

I work on AI infrastructure, model quantization, inference performance, and distributed LLM systems.

### Selected Work

- **Model Quantization** — Research and tooling · [LLMC](https://github.com/ModelTC/LightCompress) · [MQBench](https://github.com/ModelTC/MQBench) · [PPQ](https://github.com/OpenPPL/ppq)
- **LLM Inference & GPU Kernels** — Runtime performance and MACA backend work · `C++ / Python / CUDA / MACA` · [vLLM](https://github.com/xp2001-coder/vllm) · [SGLang](https://github.com/xp2001-coder/sglang) · [llama.cpp](https://github.com/xp2001-coder/llama.cpp)
- **Distributed Inference** — KV-cache transport and distributed serving · [Mooncake](https://github.com/xp2001-coder/Mooncake)
- **Learning Notes** — [zero2vllm](https://github.com/xp2001-coder/zero2vllm) · Inference systems from first principles.

### Open Source

- **[Mooncake](https://github.com/kvcache-ai/Mooncake)** — Proposed Transfer Engine fixes for MACA IPC locality, deferred batch cleanup, and protocol-aware buffer metadata removal. · [#4678](https://github.com/kvcache-ai/Mooncake/pull/4678) · [#4712](https://github.com/kvcache-ai/Mooncake/pull/4712) · [#4738](https://github.com/kvcache-ai/Mooncake/pull/4738)
- **[llama.cpp](https://github.com/ggml-org/llama.cpp)** — Responsible for MACA backend integration, maintenance, and inference optimization on MetaX GPUs.
