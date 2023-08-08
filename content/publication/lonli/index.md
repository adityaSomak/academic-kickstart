+++
abstract = ""
abstract_short = ""
authors = ["Ishan Tarunesh", "admin", "Monojit Choudhury"]
date = "2023-08-07"
image_preview = "headers/taxinli2.png"
math = true
publication_types = ["2"]
publication = "In Language Resources and Evaluations 2023"
publication_short = "In *LREV 2023* (In Print)"
selected = true
featured = false
title = "LoNLI: An Extensible Framework for Testing Diverse Logical Reasoning Capabilities for NLI"
projects = ["nlp"]
url_pdf = "https://arxiv.org/abs/2112.02333.pdf"
url_dataset = "https://github.com/microsoft/LoNLI"
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

Natural Language Inference (NLI) is considered a representative task to test natural language understanding (NLU).  In this work, we propose an extensible framework to collectively yet categorically test diverse Logical reasoning capabilities required for NLI (and by extension, NLU). Motivated by behavioral testing, we create a semi-synthetic large test-bench (363 templates, 363k examples) and an associated framework that offers following utilities: 1) individually test and analyze reasoning capabilities along 17 reasoning dimensions (including pragmatic reasoning), 2) design experiments to study cross-capability information content (leave one out or bring one in); and 3) the synthetic nature enable us to control for artifacts and biases. We extend a publicly available framework of automated test case instantiation from free-form natural language templates (CheckList), and a well-defined taxonomy of capabilities to cover a wide range of increasingly harder test cases while varying the complexity of natural language. Through our analysis of state-of-the-art NLI systems, we observe that our benchmark is indeed hard (and non-trivial even with training on additional resources). Some capabilities stand out as harder. Further fine-grained analysis and fine-tuning experiments reveal more insights about these capabilities and the models -- supporting and extending previous observations; thus showing the utility of the proposed testbench.

