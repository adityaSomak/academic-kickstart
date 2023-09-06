+++
abstract = ""
abstract_short = ""
authors = ["Deepanway Ghoshal", "Somak Aditya", "Monojit Choudhury"]
date = "2023-09-05"
image_preview = ""
math = true
publication_types = ["3"]
publication = "In *AACL-IJCNLP* 2023"
publication_short = "In <span style='color:brown;'>*AACL-IJCNLP 2023 (Main)*</span>"
selected = true
featured = true
title = "Prover: Generating Intermediate Steps for NLI with Commonsense Knowledge Retrieval and Next-Step Prediction"
projects = ["nlp","neurosymbolic"]
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

The Natural Language Inference (NLI) task often requires reasoning over multiple steps to reach the conclusion. While the necessity of generating such intermediate steps (instead of a summary explanation) has gained popular support, it is unclear how to generate such steps without complete end-to-end supervision and how such generated steps can be further utilized. In this work, we train and enhance a sequence-to-sequence next-step prediction model with external commonsense knowledge and search to generate intermediate steps with limited next-step supervision. We show the correctness of such generated steps through human verification, on MNLI and MED datasets (and discuss the limitations through qualitative examples). We show that such generated steps can help improve end-to-end NLI task performance using simple data augmentation strategies. Using a CheckList dataset for NLI, we also explore the effect of augmentation on specific reasoning types. 