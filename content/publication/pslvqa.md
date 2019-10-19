+++
abstract = ""
abstract_short = ""
authors = ["Somak Aditya", "Yezhou Yang", "Chitta Baral"]
date = "2018-11-17"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In AAAI 2018"
publication_short = "In *AAAI 2018*"
selected = true
title = "Explicit Reasoning over End-to-End Neural Architectures"
url_pdf = "http://www.public.asu.edu/~cbaral/papers/2018-aaai-psl.pdf"
url_project = "https://visionandreasoning.wordpress.com"
# url_slides = "#"


# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/VQAFigure.png"
caption = "My caption :smile:"

+++

Many vision and language tasks require commonsense reasoning beyond data-driven image and natural language pro-
cessing. Here we adopt Visual Question Answering (VQA) as an example task, where a system is expected to answer a
question in natural language about an image. Current state-of-the-art systems attempted to solve the task using deep neural
architectures and achieved promising performance. However, the resulting systems are generally opaque and they struggle
in understanding questions for which extra knowledge is required. In this paper, we present an explicit reasoning layer on
top of a set of penultimate neural network based systems. The reasoning layer enables reasoning and answering questions
where additional knowledge is required, and at the same time provides an interpretable interface to the end users. Specif-
ically, the reasoning layer adopts a Probabilistic Soft Logic (PSL) based engine to reason over a basket of inputs: visual
relations, semantic parse of the question, and background ontological knowledge from word2vec and ConceptNet. 
Experimental analysis of the answers and the key evidential predicates generated on the VQA dataset validate our approach.
