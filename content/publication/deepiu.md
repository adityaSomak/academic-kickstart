+++
abstract = ""
abstract_short = ""
authors = ["Somak Aditya", "Yezhou Yang", "Chitta Baral", "Cornelia Fermuller", "Yiannis Aloimonos"]
date = "2016-06-01"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In  Advances in Cognitive Systems (ACS) 4 (2016)"
publication_short = "In *ACS, 2016*"
selected = true
title = "DeepIU: An Architecture for Image Understanding"
url_pdf = "http://www.public.asu.edu/~cbaral/papers/acs2016.pdf"
url_project = "https://imagesdg.wordpress.com/image-to-scene-description-graph/"
url_slides = "pdf/DeepIU.pdf"

# [[url_custom]]
# name = "Custom Link"
# url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/vis_architecture.png"
caption = "My caption :smile:"

+++

Image Understanding is fundamental to systems that need to extract contents and infer concepts
from images. In this paper, we develop an architecture for understanding images, through which a
system can recognize the content and the underlying concepts of an image and, reason and answer
questions about both using a visual module, a reasoning module, and a commonsense knowledge
base. In this architecture, visual data combines with background knowledge and; iterates through
visual and reasoning modules to answer questions about an image or to generate a textual description
of an image. We first provide motivations of such a Deep Image Understanding architecture
and then, we describe the necessary components it should include. We also introduce our own
preliminary implementation of this architecture and empirically show how this more generic implementation
compares with a recent end-to-end Neural approach on specific applications. We
address the knowledge-representation challenge in such an architecture by representing an image
using a directed labeled graph (called Scene Description Graph). Our implementation uses generic
visual recognition techniques and commonsense reasoning to extract such graphs from images.
Our experiments show that the extracted graphs capture the syntactic and semantic content of an
image with reasonable accuracy.
