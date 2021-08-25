+++
# Date this page was created.
date = "2018-11-08"

# Project title.
title = "Vision and Reasoning"

# Project summary to display on homepage.
summary = "In this project, we explore how reasoning with knowledge enhance image understanding."

# Optional image to display on homepage (relative to `static/img/` folder).
# image_preview = "headers/VQAFigure.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["deep-learning", "soft-logic"]`
tags = ["deep-learning", "soft-logic", "Vision and Language", "Vision", "Language"]

# Optional external URL for project (replaces project detail page).
# external_link = "https://visionandreasoning.wordpress.com"

# Does the project detail page use math formatting?
math = false

+++

Many vision and language tasks require commonsense reasoning beyond data-driven image and natural language processing. Cognitive Sciences and older Active Vision literature points to an explicit iterative interaction
between perception, reasoning and memeory (knowledge) modules ([ACS paper](https://www.public.asu.edu/~cbaral/papers/acs2016.pdf)).

We have proposed instantiations of this abstract architecture to solve image puzzles, VQA and visual reasoning tasks such as CLEVR. In our [AAAI 2018 VQA](https://visionandreasoning.wordpress.com), and [UAI 2018 Puzzles](https://imageriddle.wordpress.com/imageriddle/), we have proposed an explicit probabilistic soft logic layer on top of a neural architecture that helps integrate commonsense knowledge and induces post-hoc interpretability.

Later on, for an end-to-end (differentiable) integration of spatial knowledge, we explore a combination of knowledge distillation, probabilistic logic, and relational network in our [WACV 2019 CLEVR](https://www.public.asu.edu/~cbaral/papers/2019-wacv.pdf).