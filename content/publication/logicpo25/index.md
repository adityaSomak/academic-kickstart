+++
abstract = ""
abstract_short = ""
authors = ["Koushik Viswanadha","Deepanway Ghoshal", "Somak Aditya"]
date = "2025-06-23"
image_preview = ""
math = true
publication_types = ["3"]
publication = "In *ArXiv* 2025"
publication_short = "In <span style='color:brown;'>*ArXiv 2025*</span>"
selected = true
featured = true
title = "LOGICPO: Efficient Translation of NL-based Logical Problems to FOL using LLMs and Preference Optimization"
projects = ["nlp","neurosymbolic"]
url_pdf = "https://arxiv.org/abs/2506.18383"
url_code = "https://github.com/goku80903/LogicPO"
url_poster = ""
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

Logical reasoning is a key task for artificial intelligence due to it’s role in major downstream tasks such as Question Answering, Summarization. Recent neurosymbolic methods in improving the reasoning ability of Large Language Models (LLM) fall short in correctly converting a natural language reasoning problem to an equivalent logical formulation, which hinders the framework’s overall ability to reason. Towards this, we propose to use finetuning on a preference optimization dataset to learn to translate a natural language reasoning problem in its entirety to a consistent logical program by 1) introducing a new supervised and preference optimization dataset (LOGICPO), and 2) adopting popular techniques such as Direct Preference Optimization (DPO), Kahneman-Tversky optimization (KTO) to finetune open-source LLMs. Our best model with QWEN-2.5 (14B) consistently outperforms GPT-4’s (8-shot) by producing 6% more logically correct and with 8% less syntax errors. We show that translating problems as a whole significantly surpasses sentence-wise text to First order Logic (FOL) baselines. We further explicitly discuss the categories of errors that
our framework addresses (and does not address), in the context of recent
comparable Neurosymbolic provers.