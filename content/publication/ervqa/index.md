+++
abstract = ""
abstract_short = ""
authors = ["Sourjyadip Ray", "Kushal Gupta", "Soumi Kundu", "Dr Payal Arvind Kasat", "Somak Aditya", "Pawan Goyal"]
date = "2024-09-20"
image_preview = ""
math = true
publication_types = ["3"]
publication = "In EMNLP 2024 Main"
publication_short = "In <span style='color:brown;'>*EMNLP 2024 (Main)*</span>"
selected = true
featured = true
title = "ERVQA: A Dataset to Benchmark the Readiness of Large Vision Language Models in Hospital Environments"
projects = ["nlp","Vision"]
url_pdf = "https://openreview.net/pdf?id=TfBbI5xicm"
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

 The global shortage of healthcare workers has demanded the development of smart healthcare assistants, which can help monitor and alert healthcare workers when necessary. We examine the healthcare knowledge of existing Large Vision Language Models (LVLMs) via the Visual Question Answering (VQA) task in hospital settings through expert annotated open-ended questions. We introduce the Emergency Room Visual Question Answering (ERVQA) dataset, consisting of 790 <image, question, answer> triplets covering diverse emergency room scenarios, a seminal benchmark for LVLMs. By developing a detailed error taxonomy and analyzing answer trends, we reveal the nuanced nature of the task. We benchmark state-of-the-art open-source and closed LVLMs using traditional and adapted VQA metrics: Entailment Score and CLIPScore Confidence. Analyzing errors across models, we infer trends based on properties like decoder type, model size, and in-context examples. Our findings suggest the ERVQA dataset presents a highly complex task, highlighting the need for specialized, domain-specific solutions.