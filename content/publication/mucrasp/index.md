+++
abstract = ""
abstract_short = ""
authors = ["Aritra Dutta", "Somak Aditya"]
date = "2026-05-25"
image_preview = ""
math = true
publication_types = ["3"]
publication = "In ArXiv 2026"
publication_short = "In <span style='color:brown;'>*ArXiv 2026*</span>"
selected = true
featured = false
title = "MuCRASP: Multimodal Chain-of-thought Reasoning aware Structured Pruning"
projects = ["Vision", "NLP", "Compression"]
url_pdf = "https://arxiv.org/abs/2605.25842"
url_code = ""
url_project = ""
url_dataset = ""
url_video = ""


# Optional featured image (relative to `static/img/` folder).
# [header]
# image = ""
# caption = "My caption :smile:"
# focal_point = "center"

[image]
caption = ""
focal_point = "center"
+++

Vision-language models (VLMs) increasingly rely on chain-of-thought (CoT) reasoning to solve complex multimodal tasks, but their large parameter sizes make deployment expensive. Structured pruning offers a natural solution; however, existing methods fail to preserve CoT reasoning accuracy in VLMs. We identify two key reasons: (1) CoT consistency depends on sparse transition points (pivot tokens) in the generation trajectory, while existing pruning methods are CoT-agnostic; and (2) pruning methods designed for unimodal LLMs do not account for activation-distribution differences across visual and textual modalities. Motivated by these observations, we propose MuCRASP, a structured pruning framework that targets reasoning-critical components while preserving cross-modal alignment and accounting for layer-wise sensitivity under a global parameter budget. Experiments on four VLMs across three reasoning benchmarks show that MuCRASP consistently preserves reasoning quality under increasing compression. At 30% pruning on Qwen2.5-VL-7B, MuCRASP achieves an LLM-as-a-Judge score of 8.87 versus 7.32 for the strongest baseline on physical reasoning tasks. Furthermore, MuCRASP maintains high reasoning consistency up to 50% pruning, significantly outperforming prior pruning approaches while exhibiting lower perplexity degradation.