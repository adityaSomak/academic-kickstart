+++
abstract = ""
abstract_short = ""
authors = ["Man Luo", "Shrinidhi Kumbhar", "Ming shen", "Mihir Parmar", "Neeraj Varshney", "Pratyay Banerjee", "admin", "Chitta Baral"]
date = "2023-11-07"
image_preview = "headers/taxinli2.png"
math = true
publication_types = ["2"]
publication = "In ArXiv 2023"
publication_short = "In <span style='color:brown;'>*ArXiv 2023*</span>"
selected = true
featured = false
title = "Towards LogiGLUE: A Brief Survey and A Benchmark for Analyzing Logical Reasoning Capabilities of Language Models"
projects = ["nlp"]
url_pdf = "https://arxiv.org/pdf/2310.00836.pdf"
url_dataset = "https://huggingface.co/datasets/logicreasoning/logi_glue"
url_code = "https://huggingface.co/logicreasoning/LogiT5"
url_poster = ""
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

Logical reasoning is fundamental for humans yet presents a substantial challenge in the domain of Artificial Intelligence. Initially, researchers used Knowledge Representation and Reasoning (KR) systems that did not scale and required non-trivial manual effort. Recently, the emergence of large language models (LLMs) has demonstrated the ability to overcome various limitations of formal Knowledge Representation (KR) systems. Consequently, there’s a growing interest in using LLMs for logical reasoning via natural language. 

This work strives to understand the proficiency of LLMs in logical reasoning by offering a brief review of the latest progress in this area; with a focus on the logical reasoning datasets, tasks, and the methods adopted to utilize LLMs for reasoning. To offer a thorough analysis, we’ve compiled a benchmark titled LogiGLUE. This includes 24 varied datasets encompassing deductive, abductive, and inductive reasoning. We have standardized these datasets into Seq2Seq tasks to facilitate straightforward training and evaluation for future research. Utilizing LogiGLUE as a foundation, we have trained an instruction fine-tuned language model, resulting in LogiT5. We study single-task training, multi-task training, and a "chain-of-thought" knowledge distillation finetuning technique to assess the model’s performance across the different logical reasoning categories. By this comprehensive process, we aim to shed light on the capabilities and potential pathways for enhancing logical reasoning proficiency in LLMs, paving the way for more advanced and nuanced developments in this
critical field.