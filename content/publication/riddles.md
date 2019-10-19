+++
abstract = ""
abstract_short = ""
authors = ["Somak Aditya", "Yezhou Yang", "Chitta Baral", "Yiannis Aloimonos"]
date = "2018-07-01"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In UAI. 2018"
publication_short = "In *UAI 2018*"
selected = true
title = "Combining Knowledge and Reasoning through Probabilistic Soft Logic for Image Puzzle Solving"
url_pdf = "http://auai.org/uai2018/proceedings/papers/83.pdf"
url_project = "https://imageriddle.wordpress.com/imageriddle/"
# url_slides = "#"


# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/fall_h.jpg"
caption = "My caption :smile:"

+++

In this work, we explore a genre of puzzles (“image riddles”) which involves a set of images and a question. 
Answering these puzzles require both capabilities involving visual detection (including object, activity recognition) and, 
knowledge-based or commonsense reasoning. We compile a dataset of over 3k riddles where each riddle consists of 4 images and 
a groundtruth answer. The annotations are validated using crowd-sourced evaluation. We also define an automatic evaluation 
metric to track future progress. Our task bears similarity with the commonly known IQ tasks such as analogy solving, 
sequence filling that are often used to test intelligence.

We develop a Probabilistic Reasoning-based approach that utilizes probabilistic commonsense knowledge to answer these 
riddles with a reasonable accuracy. We demonstrate the results of our approach using both automatic and human evaluations. 
Our approach achieves some promising results ($12\%$ improvement over baseline) for these riddles and provides a strong baseline for future attempts. We make 
the entire dataset and related materials publicly available to the community.
