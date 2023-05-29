+++
# Date this page was created.
date = "2020-03-01"

# Project title.
title = "Symbolic Mathematics"

# Project summary to display on homepage.
summary = "We explore multi-hop reasoning capabilities of Transformer/GNN methods in purely symbolic domains."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "headers/sdg.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["symbolic", "ATP", "transformers", "logic", "deep-learning"]

# Optional external URL for project (replaces project detail page).
# external_link = "https://imagesdg.wordpress.com/image-to-scene-description-graph/"

# Does the project detail page use math formatting?
math = false

+++

In a recent work ([PolySimp ICLR 2021 MathAI Workshop](https://mathai-iclr.github.io/papers/papers/MATHAI_6_paper.pdf)) with Navin Goyal and Vishesh Agarwal, we explored Transformers' abilities to perform multiple-step reasoning in well-defined purely symbolic tasks such as step-wise polynomial simplification.  Polynomials can be written in a simple normal form as a sum of monomials which are ordered in a lexicographic order. For a polynomial which is not necessarily in this normal form, a sequence of simplification steps is applied to reach the fully simplified (i.e., in the normal form) polynomial. We propose a synthetic Polynomial dataset generation algorithm that generates polynomials with unique proof steps. 

Through varying coefficient configurations, input representation, proof granularity, and extensive hyper-parameter tuning, we observe that Transformers consistently struggle with numeric multiplication. We explore two ways to mitigate this: Curriculum Learning and a Symbolic Calculator approach (where the numeric operations are offloaded to a calculator). Both approaches provide significant gains over the vanilla Transformers-based baseline.


<!-- <div>
<div id="References" align="left" style="width: 100%; overflow-y: hidden;" class="wcustomhtml"><h3 style="margin-bottom:0px;">References</h3>
<hr style="float: center"></div>
</div>
<ul>
<li>
Vishesh Agarwal, Somak Aditya, Navin Goyal. Analyzing the Nuances of Transformers' Polynomial Simplification Abilities. ICLR 2021 MathAI Workshop. 
</li>
</ul> -->