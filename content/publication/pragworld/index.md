+++
abstract = ""
abstract_short = ""
authors = ["Sachin Vashistha", "Aryan Bibhuti", "Atharva Naik", "Martin Tutek", "Somak Aditya"]
date = "2025-11-08"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In AAAI 2026 Main Track (Oral)"
publication_short = "In <span style='color:brown;'>*AAAI 2026 (Main Track Oral) 17.6% acceptance rate*</span>"
selected = true
featured = true
title = "PRAGWORLD: A Benchmark Evaluating LLMs' Local World Model under Minimal Linguistic Alterations and Conversational Dynamics"
projects = ["nlp","AI"]
url_pdf = "https://arxiv.org/abs/2511.13021"
url_code = "https://github.com/SachinVashisth/PRAGWORLD"
url_project = "pragworld/index.html"
url_dataset = "https://github.com/SachinVashisth/PRAGWORLD"
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

Real-world conversations are rich with pragmatic elements, such as entity mentions, references, and implicatures. Understanding such nuances is a requirement for successful natural communication, and often requires building a local world model which encodes such elements and captures the dynamics of their evolving states. However, it is not well-understood whether language models (LMs) construct or maintain a robust implicit representation of conversations. In this work, we evaluate the ability of LMs to encode and update their internal world model in dyadic conversations and test their malleability under linguistic alterations. To facilitate this, we apply seven minimal linguistic alterations to conversations sourced from popular datasets and construct two benchmarks comprising yes-no questions. We evaluate a wide range of open and closed source LMs and observe that they struggle to maintain robust accuracy. Our analysis unveils that LMs struggle to memorize crucial details, such as tracking entities under linguistic alterations to conversations. We then propose a dual-perspective interpretability framework which identifies transformer layers that are useful or harmful and highlights linguistic alterations most influenced by harmful layers, typically due to encoding spurious signals or relying on shortcuts. Inspired by these insights, we propose two layer-regularization based fine-tuning strategies that suppress the effect of the harmful layers.