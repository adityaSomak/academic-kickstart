+++
abstract = ""
abstract_short = ""
authors = ["Deepanway Ghoshal", "Somak Aditya", "Monojit Choudhury"]
date = "2022-08-31"
image_preview = ""
math = true
publication_types = ["3"]
publication = "In ArXiv 2022"
publication_short = "In *ArXiv 2022* (under review)"
selected = true
featured = true
title = "Generating Intermediate Steps for NLI with Next-Step Supervision"
projects = ["nlp"]
url_pdf = "https://arxiv.org/abs/2208.14641"
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

The Natural Language Inference (NLI) task often requires reasoning over multiple steps to reach the conclusion. While the necessity of generating such intermediate steps (instead of a summary explanation) has gained popular support, it is unclear how to generate such steps without complete end-to-end supervision and how such generated steps can be further utilized. In this work, we train a sequence-to-sequence model to generate only the next step given an NLI premise and hypothesis pair (and previous steps); then enhance it with external knowledge and symbolic search to generate intermediate steps with only next-step supervision. We show the correctness of such generated steps through automated and human verification. Furthermore, we show that such generated steps can help improve end-to-end NLI task performance using simple data augmentation strategies, across multiple public NLI datasets.
