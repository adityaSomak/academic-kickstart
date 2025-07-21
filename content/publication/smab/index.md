+++
abstract = ""
abstract_short = ""
authors = ["Saurabh Kumar Pandey", "Sachin Vashishtha", "Somak Aditya", "Monojit Choudhury"]
date = "2025-01-20"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In NAACL 2025 Main"
publication_short = "In <span style='color:brown;'>*NAACL 2025 (Main)*</span>"
selected = true
featured = true
title = "SMAB: MAB based word Sensitivity Estimation Framework and its Applications in Adversarial Text Generation"
projects = ["nlp"]
url_pdf = "https://arxiv.org/pdf/2502.07101"
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

 To understand the complexity of sequence classification tasks, Hahn et al. (2021) proposed sensitivity as the number of disjoint subsets of the input sequence that can each be individually changed to change the output. Though effective, calculating sensitivity at scale using this framework is costly because of exponential time complexity. Therefore, we introduce a Sensitivity-based Multi-Armed Bandit framework (SMAB), which provides a scalable approach for calculating word-level local (sentence-level) and global (aggregated) sensitivities concerning an underlying text classifier for any dataset. We establish the effectiveness of our approach through various applications. We perform a case study on CHECKLIST generated sentiment analysis dataset where we show that our algorithm indeed captures intuitively high and low-sensitive words. Through experiments on multiple tasks and languages, we show that sensitivity can serve as a proxy for accuracy in the absence of gold data. Lastly, we show that guiding perturbation prompts using sensitivity values in adversarial example generation improves attack success rate by 15.58%, whereas using sensitivity as an additional reward in adversarial paraphrase generation gives a 12.00% improvement over SOTA approaches. Warning: Contains potentially offensive content.