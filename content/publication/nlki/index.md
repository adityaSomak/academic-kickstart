+++
abstract = ""
abstract_short = ""
authors = ["Aritra Dutta", "Swapnanil Mukherjee", "Deepanway Ghoshal", "Somak Aditya"]
date = "2025-08-20"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *EMNLP* 2025"
publication_short = "In <span style='color:brown;'>*EMNLP 2025 (Findings)*</span>"
selected = true
featured = true
title = "NLKI: A lightweight Natural Language Knowledge Integration Framework for improving small VLMs in Commonsense VQA tasks"
projects = ["vision","neurosymbolic"]
url_pdf = "https://arxiv.org/pdf/2508.19724"
url_code = "https://github.com/beingdutta/NLKI-Lightweight-Natural-Language-Knowledge-Integration-Framework"
url_poster = ""
url_project = "https://beingdutta.github.io/NLKI-Project-Page-EMNLP-2025-Findings/"
url_dataset = "https://github.com/beingdutta/NLKI-Lightweight-Natural-Language-Knowledge-Integration-Framework"
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

Commonsense visual–question answering often hinges on knowledge that is missing from
the image or the question. Small visionlanguage models (sVLMs) such as ViLT, VisualBERT and FLAVA therefore lag behind their larger generative counterparts. To study the effect of careful commonsense knowledge integration on sVLMs, we present an end-to-end framework (NLKI) that (i) retrieves natural language facts, (ii) prompts an LLM to craft natural language explanations, and (iii) feeds both signals to sVLMs respectively across two commonsense VQA datasets (CRIC, AOKVQA)
and a visual-entailment dataset (e-SNLI-VE). Facts retrieved using a fine-tuned ColBERTv2
and an object information-enriched prompt yield explanations that largely cut down hallucinations, while lifting the end-to-end answer accuracy by up to 7% (across 3 datasets), making FLAVA and other models in NLKI match or exceed medium-sized VLMs such as Qwen-2VL-2B and SmolVLM-2.5B. As these benchmarks contain 10–25% label noise, additional finetuning using noise-robust losses (such as symmetric cross entropy and generalised cross entropy) adds another 2.5% in CRIC, and 5.5%
in AOKVQA. Our findings expose when LLMbased commonsense knowledge beats retrieval
from commonsense knowledge bases, how noise-aware training stabilises small models
in the context of external knowledge augmentation, and why parameter-efficient commonsense reasoning is now within reach for 250M models.