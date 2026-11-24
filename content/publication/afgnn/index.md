+++
abstract = ""
abstract_short = ""
authors = ["Ponnampalam Pirapuraj", "Tamal Mondal", "Sharanya Gupta", "Akash Lal", "Somak Aditya", "Jyothi Vedurada"]
date = "2026-04-13"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In MSR 2026"
publication_short = "In <span style='color:brown;'>*MSR 2026*</span>"
selected = true
featured = false
title = "AFGNN: API misuse detection using graph neural networks and clustering"
projects = ["Neurosymbolic", "API misuse"]
url_pdf = "https://dl.acm.org/doi/full/10.1145/3793302.3793372"
url_code = ""
url_project = ""
url_dataset = ""
url_video = ""


# Optional featured image (relative to `static/img/` folder).
# [header]
# image = ""
# caption = "My caption :smile:"
# focal_point = "center"

[image]
caption = ""
focal_point = "center"
+++

Application Programming Interfaces (APIs) are crucial to software development, enabling integration of existing systems with new applications by reusing tried and tested code, saving development time and increasing software safety. In particular, the Java standard library APIs, along with numerous third-party APIs, are extensively utilized in the development of enterprise application software. However, their misuse remains a significant source of bugs and vulnerabilities. Furthermore, due to the limited examples in the official API documentation, developers often rely on online portals and generative AI models to learn unfamiliar APIs, but using such examples may introduce unintentional errors in the software. In this paper, we present AFGNN, a novel Graph Neural Network (GNN)-based framework for efficiently detecting API misuses in Java code. AFGNN uses a novel API Flow Graph (AFG) representation that captures the API execution sequence, data, and control flow information present in the code to model the API usage patterns. AFGNN uses self-supervised pre-training with AFG representation to effectively compute the embeddings for unknown API usage examples and cluster them to identify different usage patterns. Experiments on popular API usage datasets show that AFGNN significantly outperforms state-of-the-art small language models and API misuse detectors.