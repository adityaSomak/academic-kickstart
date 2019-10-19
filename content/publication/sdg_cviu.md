+++
abstract = ""
abstract_short = ""
authors = ["Somak Aditya", "Yezhou Yang", "Chitta Baral", "Cornelia Fermuller", "Yiannis Aloimonos"]
date = "2017-12-18"
image_preview = ""
math = true
publication_types = ["2"]
publication = "Computer Vision and Image Understanding"
publication_short = "In CVIU 2017"
selected = true
title = "Image Understanding using Vision and Reasoning through Scene Description Graph"
url_pdf = "http://www.sciencedirect.com/science/article/pii/S1077314217302291"
url_project = "https://imagesdg.wordpress.com/image-to-scene-description-graph/"
# url_slides = "#"


# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/cviu.png"
caption = "My caption :smile:"

+++

Two of the fundamental tasks in image understanding using text are caption generation and visual question answering 
[4, 72]. This work presents an intermediate knowledge structure that can be used for both tasks to obtain increased interpretability. 
We call this knowledge structure Scene Description Graph (SDG), as it is a directed labeled graph, representing objects, actions, 
regions, as well as their attributes, along with inferred concepts and semantic (from KM-Ontology [12]), ontological (i.e. superclass, hasProperty), 
and spatial relations. Thereby a general architecture is proposed in which a system can represent both the content and underlying concepts of an 
image using an SDG. The architecture is implemented using generic visual recognition techniques and commonsense reasoning to extract graphs from 
images. The utility of the generated SDGs is demonstrated in the applications of image captioning, image retrieval, and through examples in 
visual question answering. The experiments in this work show that the extracted graphs capture syntactic and semantic content of images 
with reasonable accuracy.
