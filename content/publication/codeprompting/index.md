+++
abstract = ""
abstract_short = ""
authors = ["Haritz Puerto", "Martin Tutek", "Somak Aditya", "Xiaodan Zhu", "Iryna Gurevych"]
date = "2024-02-18"
image_preview = ""
math = true
publication_types = ["3"]
publication = "In ICLR ME-FOMO Workshop"
publication_short = "In <span style='color:brown;'>*ArXiv 2024*</span>"
selected = true
featured = true
title = "Code Prompting Elicits Conditional Reasoning Abilities in Text+ Code LLMs"
projects = ["nlp","code"]
url_pdf = "https://arxiv.org/abs/2401.10065"
url_code = ""
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

Reasoning is a fundamental component for achieving language understanding. Among the multiple types of reasoning, conditional reasoning, the ability to draw different conclusions depending on some condition, has been understudied in large language models (LLMs). Recent prompting methods, such as chain of thought, have significantly improved LLMs on reasoning tasks. Nevertheless, there is still little understanding of what triggers reasoning abilities in LLMs. We hypothesize that code prompts can trigger conditional reasoning in LLMs trained on text and code. We propose a chain of prompts that transforms a natural language problem into code and prompts the LLM with the generated code. Our experiments find that code prompts exhibit a performance boost between 2.6 and 7.7 points on GPT 3.5 across multiple datasets requiring conditional reasoning. We then conduct experiments to discover how code prompts elicit conditional reasoning abilities and through which features. We observe that prompts need to contain natural language text accompanied by high-quality code that closely represents the semantics of the instance text. Furthermore, we show that code prompts are more efficient, requiring fewer demonstrations, and that they trigger superior state tracking of variables or key entities.