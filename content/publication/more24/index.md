+++
abstract = ""
abstract_short = ""
authors = ["Pengfei Hong", "Deepanway Ghoshal", "Navonil Majumdar", "Somak Aditya", "Rada Mihalcea", "Soujanya Poria"]
date = "2024-01-17"
image_preview = ""
math = true
publication_types = ["3"]
publication = "In ArXiv"
publication_short = "In <span style='color:brown;'>*ArXiv 2024*</span> "
selected = true
featured = true
title = "STUCK IN THE QUICKSAND OF NUMERACY, FAR FROM AGI SUMMIT: EVALUATING LLMS' MATHEMATICAL COMPETENCY THROUGH ONTOLOGY-GUIDED PERTURBATIONS"
projects = ["nlp", "symbolicmath"]
url_pdf = "https://arxiv.org/pdf/2401.09395.pdf"
url_code = "https://huggingface.co/datasets/declare-lab/GSM8k_MORE"
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

Recent advancements in Large Language Models (LLMs) have showcased striking results on existing logical reasoning benchmarks, with some models even surpassing human performance. However, the true depth of their competencies and robustness, in mathematical reasoning tasks, remains an open question. In response, we develop (i) an ontology of perturbations of maths questions, (ii) a semi-automatic method of perturbation, and (iii) a dataset of perturbed maths questions 
to probe the limits of LLM capabilities in mathematical-reasoning tasks.
These controlled perturbations span across multiple fine dimensions of the structural and representational aspects of maths questions. Using GPT-4, we generated the <span style="font-variant-caps: small-caps">More</span> dataset by perturbing randomly selected five seed questions from GSM8K. This process was guided by our ontology and involved a thorough automatic and manual filtering process, yielding a set of 216 maths problems.
We conducted comprehensive evaluation of both closed-source and open-source LLMs on <span style="font-variant-caps: small-caps">More</span>. The results show a significant performance drop across all the models against the perturbed questions. This strongly suggests that current LLMs lack robust mathematical skills and a deep understanding of reasoning. This research not only identifies multiple gaps in the capabilities of current models, but also highlights multiple potential directions for future development. Our dataset will be made publicly available at <a href="https://huggingface.co/datasets/declare-lab/GSM8k_MORE">huggingface library</a>.