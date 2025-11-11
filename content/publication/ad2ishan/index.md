+++
abstract = ""
abstract_short = ""
authors = ["Ishan Sahu", "Somnath Hazra", "Somak Aditya", "Soumyajit Dey"]
date = "2025-11-11"
image_preview = ""
math = true
publication_types = ["3"]
publication = "In WACV 2026 Main"
publication_short = "In <span style='color:brown;'>*WACV 2026 (Main)*</span>"
selected = true
featured = true
title = "AD$^2$: Analysis and Detection of Adversarial Threats in Visual Perception for End-to-End Autonomous Driving Systems"
projects = ["Vision", "Autonomousdriving"]
url_pdf = "https://openreview.net/pdf?id=eJbUur76J5"
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

End-to-end autonomous driving systems have achieved significant progress, yet their adversarial robustness remains largely underexplored. In this work, we conduct a closed-loop evaluation of state-of-the-art autonomous driving agents under black-box adversarial threat models in CARLA. Specifically, we consider three representative attack vectors on the visual perception pipeline: (i) a physics-based blur attack induced by acoustic waves, (ii) an electromagnetic interference attack that distorts captured images, and (iii) a digital attack that adds ghost objects as carefully crafted bounded perturbations on images. Our experiments on two advanced agents, Transfuser and Interfuser, reveal severe vulnerabilities to such attacks, with driving scores dropping by up to 99% in the worst case, raising valid safety concerns. To help mitigate such threats, we further propose a lightweight Attack Detection model for Autonomous Driving systems (AD$^2$) based on attention mechanisms that capture spatial–temporal consistency. Comprehensive experiments across multi-camera inputs on CARLA show that our detector achieves superior detection capability and computational efficiency compared to existing approaches.