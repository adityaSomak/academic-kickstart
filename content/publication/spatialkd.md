+++
abstract = ""
abstract_short = ""
authors = ["Somak Aditya", "Rudra Saha", "Yezhou Yang", "Chitta Baral"]
date = "2019-01-09"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In WACV 2019"
publication_short = "In *WACV 2019*"
selected = true
title = "Spatial Knowledge Distillation to aid Visual Reasoning"
url_pdf = ""
url_project = ""
# url_slides = "#"


# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/vqa_spatial_kd.png"
caption = "My caption :smile:"

+++

For tasks involving language and vision, the current state-of-the-art methods do not leverage any additional information
that might be present to gather privileged knowledge. Instead, such an ability is expected to be learnt during the training
phase. One such task is Visual Question Answering, where large diagnostic datasets have been proposed to
test a system’s capability of reasoning and answering questions about images. In
this work, we take a step towards integrating this additional privileged information in the form of spatial knowledge to
aid in visual reasoning. We propose a framework that combines recent advances in knowledge distillation (teacherstudent
framework), relational reasoning and probabilistic logical languages to incorporate such knowledge in existing
neural networks for the surrogate task of fact-based Visual Question Answering. Specifically, for a question posed
against an image, we use a probabilistic logical language to encode the spatial knowledge and the spatial understanding
about the question in the form of a mask that is directly provided to the teacher network. The student network learns
from the ground-truth information as well as the teacher’s prediction via distillation. We also demonstrate the impact
of predicting such a mask inside the teacher’s network using attention. Empirically, we show that both the methods
improve the test accuracy over a state-of-the-art approach on a publicly available dataset.
