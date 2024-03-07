+++
abstract = ""
abstract_short = ""
authors = ["Debrup Das", "Debopriyo Banerjee", "Somak Aditya", "Ashish Kulkarni"]
date = "2024-02-28"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In ICLR ME-FOMO Workshop"
publication_short = "In <span style='color:brown;'>*ICLR ME-FOMO Workshop*</span> &  *NAACL 2024 (under Review)*"
selected = true
featured = true
title = "MATHSENSEI: A Tool-Augmented Large Language Model for Mathematical Reasoning"
projects = ["nlp","neurosymbolic"]
url_pdf = "https://arxiv.org/pdf/2402.17231.pdf"
url_code = "https://github.com/Debrup-61/MathSensei"
url_page = ""
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

Tool-augmented Large Language Models (TALM) are known to enhance the skillset of
large language models (LLM), thereby, leading to their improved reasoning abilities across
many tasks. While, TALMs have been successfully employed in different question-answering
benchmarks, their efficacy on complex mathematical reasoning benchmarks, and, the potential complimentary benefits offered by tools for knowledge retrieval and mathematical equation solving, are open research questions. In this work, we present MATHSENSEI, a toolaugmented large language model for mathematical reasoning. Augmented with tools for knowledge retrieval (Bing Web Search), program execution (Python), and symbolic equation solving (Wolfram-Alpha), we study the
complimentary benefits of these tools through evaluations on mathematical reasoning datasets.
We perform exhaustive ablations on MATH, a popular dataset for evaluating mathematical reasoning on diverse mathematical disciplines. We also conduct experiments involving well-known tool planners to study the impact of tool sequencing on the model performance. MATHSENSEI achieves 13.5% better accuracy over gpt-3.5-turbo with chain-ofthought on the MATH dataset. We further observe that TALMs are not as effective for simpler math word problems (in GSM-8k), and
the benefit increases as the complexity and required knowledge increases (progressively
over AQuA, MMLU-Math, and higher level complex questions in MATH). The code and data are available at <a href="https://github.com/Debrup61/MathSensei">MathSensei-Github</a>.