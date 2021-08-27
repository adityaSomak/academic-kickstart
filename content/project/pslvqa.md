+++
# Date this page was created.
date = "2015-11-08"

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

Many vision and language tasks require commonsense reasoning beyond data-driven image and natural language processing. Cognitive Sciences and Active Vision literature points to an explicit iterative interaction
among perception, reasoning, and memeory (knowledge) modules ([DeepIU ACS 2015](https://www.public.asu.edu/~cbaral/papers/acs2016.pdf)).

<h3> Captioning </h3> 
In our earliest attempt ([CVIU 2017](https://imagesdg.wordpress.com/image-to-scene-description-graph/) ), we used a combination of image classification, reasoning with commonsense knowledge (extracted from training captions) to propose a Scene Description Graph as an intermediate representation for a natural image. We showed the efficacy of this representation through image captioning, image retrieval tasks (and QA case studies.)

<h3> Visual QA, Image Puzzles and Visual Reasoning </h3>
We have proposed instantiations of this abstract architecture to solve image puzzles, VQA and visual reasoning tasks such as CLEVR. In our [AAAI 2018 VQA](https://visionandreasoning.wordpress.com), and [UAI 2018 Puzzles](https://imageriddle.wordpress.com/imageriddle/) work, we have proposed an explicit probabilistic soft logic layer on top of a neural architecture that helps integrate commonsense knowledge and induces post-hoc interpretability.

Later on, for an end-to-end (differentiable) integration of spatial knowledge, we explore a combination of knowledge distillation, probabilistic logic, and relational network in our [WACV 2019 CLEVR](https://www.public.asu.edu/~cbaral/papers/2019-wacv.pdf).


<div>
<div id="References" align="left" style="width: 100%; overflow-y: hidden;" class="wcustomhtml"><h3 style="margin-bottom:0px;">References</h3>
<hr style="float: center"></div>
</div>
<ul> 
<li> 
Somak Aditya, Yezhou Yang, Chitta Baral. Integrating Knowledge and Reasoning in Image Understanding. IJCAI 2019. 
</li>
<li>
Somak Aditya, Rudra Saha, Yezhou Yang and Chitta Baral. Spatial Knowledge Distillation to aid Visual Reasoning. WACV 2019. 
</li>
<li>
Somak Aditya, Yezhou Yang, Chitta Baral. Explicit Reasoning over End-to-End Neural Architectures for Visual Question Answering. AAAI 2018.
</li>
<li>
Somak Aditya, Yezhou Yang, Chitta Baral and Yiannis Aloimonos. Combining Knowledge and Reasoning through Probabilistic Soft Logic for Image Puzzle Solving. UAI 2018.
</li>
<li>
Somak Aditya, Yezhou Yang, Chitta Baral, Yiannis Aloimonos and Cornelia Fermuller. Image Understanding using Vision and Reasoning through Scene Description Graph. Computer Vision and Image Understanding Journal. (Accepted December 2017)
</li>
<li>
Somak Aditya, Yezhou Yang, Chitta Baral and Yiannis Aloimonos. Answering Image Riddles using Vision and Reasoning through Probabilistic Soft Logic.. Arxiv version. 2016. Website with additional information on this work.
</li>
<li>
Somak Aditya, Chitta Baral, Yezhou Yang, Yiannnis Aloimonos and Cornelia Fermuller. DeepIU: An architecture for image understanding. Advances in Cognitive Systems. 2016.
</li>
<li>
Somak Aditya, Yezhou Yang, Chitta Baral, Cornelia Fermuller, Yiannis Aloimonos. From Images to Sentences through Scene Description Graphs using Commonsense Reasoning and Knowledge. Arxiv version.
</li>
<li>
Somak Aditya, Yiannis Aloimonos, Chitta Baral, Cornelia Fermuller and Yezhou Yang. Visual common-sense for scene understanding using perception, semantic parsing and reasoning. Common-sense 2015, AAAI 2015 Spring Symposium. (Appenidix with code.)
</li>
</ul>
