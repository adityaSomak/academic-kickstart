+++
abstract = ""
abstract_short = ""
authors = ["Pratik Joshi*", "Somak Aditya*", "Aalok Sathe*", "Monojit Choudhury"]
date = "2020-07-18"
image_preview = "headers/taxinli2.png"
math = true
publication_types = ["1"]
publication = "In CoNLL 2020"
publication_short = "In *CoNLL 2020*"
selected = true
featured = true
title = "TaxiNLI: Taking a Ride up the NLU Hill"
url_pdf = "https://www.aclweb.org/anthology/2020.conll-1.4/"
url_dataset = "https://github.com/microsoft/TaxiNLI"
url_slides = "https://slideslive.com/38939466/taxinli-taking-a-ride-up-the-nlu-hill"


# Optional featured image (relative to `static/img/` folder).
# [header]
# image = ""
# caption = "My caption :smile:"
# focal_point = "center"

[image]
caption = ""
focal_point = "center"
+++

Pre-trained Transformer-based neural architectures have consistently achieved state-of-the-art performance in the Natural Language Inference (NLI) task. Since NLI examples encompass a variety of linguistic, logical, and reasoning phenomena, it remains unclear as to which specific concepts are learnt by the trained systems and where they can achieve strong generalization. To investigate this question, we propose a taxonomic hierarchy of categories that are relevant for the NLI task. We introduce TAXINLI, a new dataset, that has 10k examples from the MNLI dataset (Williams et al., 2018) with these taxonomic labels. Through various experiments on TAXINLI, we observe that whereas for certain taxonomic categories SOTA neural models have achieved near perfect accuracies - a large jump over the previous models - some categories still remain difficult. Our work adds to the growing body of literature that shows the gaps in the current NLI systems and datasets through a systematic presentation and analysis of reasoning categories.
