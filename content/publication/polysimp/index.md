+++
abstract = ""
abstract_short = ""
authors = ["Vishesh Agarwal", "Somak Aditya", "Navin Goyal"]
date = "2021-05-07"
image_preview = "headers/taxinli2.png"
math = true
publication_types = ["1"]
publication = "In ICLR 2021 MathAI Workshop"
publication_short = "In *ICLR 2021 MathAI*"
selected = true
featured = true
title = "Analyzing the Nuances of Transformers' Polynomial Simplification Abilities"
projects = ["symbolicmath"]
url_pdf = "https://mathai-iclr.github.io/papers/papers/MATHAI_6_paper.pdf"
url_poster = "https://mathai-iclr.github.io/papers/posters/MATHAI_6_poster.pdf"
url_video = "https://www.youtube.com/watch?v=Qjh76c3_qLI&feature=youtu.be"


# Optional featured image (relative to `static/img/` folder).
# [header]
# image = ""
# caption = "My caption :smile:"
# focal_point = "center"

[image]
caption = ""
focal_point = "center"
+++

Symbolic Mathematical tasks such as integration often require multiple welldefined steps and understanding of sub-tasks to reach a solution. To understand Transformers’ abilities in such tasks in a fine-grained manner, we deviate from traditional end-to-end settings, and explore a step-wise polynomial simplification task. Polynomials can be written in a simple normal form as a sum of monomials which are ordered in a lexicographic order. For a polynomial which is not necessarily in this normal form, a sequence of simplification steps is applied to reach the fully simplified (i.e., in the normal form) polynomial. We propose a synthetic Polynomial dataset generation algorithm that generates polynomials with unique proof steps. Through varying coefficient configurations, input representation, proof granularity, and extensive hyper-parameter tuning, we observe that Transformers consistently struggle with numeric multiplication. We explore two ways to mitigate this: Curriculum Learning and a Symbolic Calculator approach (where the numeric operations are offloaded to a calculator). Both approaches provide significant gains over the vanilla Transformers-based baseline.
