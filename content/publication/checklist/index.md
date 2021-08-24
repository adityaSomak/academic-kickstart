+++
abstract = ""
abstract_short = ""
authors = ["Ishan Tarunesh", "Somak Aditya", "Monojit Choudhury"]
date = "2021-07-22"
image_preview = "headers/taxinli2.png"
math = true
publication_types = ["3"]
publication = "In ArxiV"
publication_short = "In *ArXiv 2021*"
selected = true
featured = false
title = "Trusting RoBERTa over BERT: Insights from CheckListing the Natural Language Inference Task"
url_pdf = "https://arxiv.org/pdf/2107.07229.pdf"
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

The recent state-of-the-art natural language understanding (NLU) systems often behave unpredictably, failing on simpler reasoning examples. Despite this, there has been limited focus on quantifying progress towards systems with more predictable behavior. We think that reasoning capability-wise behavioral summary (proposed in Ribeiro et al. (2020)) is a step towards bridging this gap. We create a CHECKLIST test-suite (184K examples) for the Natural Language Inference (NLI) task, a representative NLU task. We benchmark state-of-the-art NLI systems on this test-suite, which reveals fine-grained insights into the reasoning abilities of BERT and RoBERTa. Our analysis further reveals inconsistencies of the models on examples derived from the same template or distinct templates but pertaining to same reasoning capability, indicating that generalizing the models’ behavior through observations made on a CheckList is non-trivial. Through an user-study, we find that users were able to utilize behavioral information to generalize much better for examples predicted from RoBERTa, compared to that of BERT.

