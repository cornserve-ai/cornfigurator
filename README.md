<div align="center">
<h2>Cornfigurator: <i>Automatic Deployment Planning for Multimodal AI</i></h2>

[![Cornserve](https://custom-icon-badges.demolab.com/badge/Cornserve-cornserve.ai-1D63ED.svg?logo=home&logoColor=white&logoSource=feather)](https://github.com/cornserve-ai/cornserve)
[![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.14098)
</div>

---

Cornfigurator is a deployment planner for generic Any-to-Any model inference serving. Given a model and workload, it explores the full spectrum of deployment strategies — from colocation to disaggregation and mixes of the two — and uses coarse-to-fine statistical evaluation to navigate the large plan space efficiently.

The current `c11r` planner works directly with [Cornserve](https://github.com/cornserve-ai/cornserve) as its profiling and execution backend, and upcoming work will add support for [vLLM-Omni](https://github.com/vllm-project/vllm-omni) and [SGLang-Omni](https://github.com/sgl-project/sglang-omni).

## Status

Source code is still under construction and will be released here soon.

---

For the full design and evaluation, see our paper: ["Cornfigurator: Automated Planning for Any-to-Any Multimodal Model Serving"](https://arxiv.org/abs/2512.14098).
