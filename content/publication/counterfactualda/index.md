+++
abstract = ""
abstract_short = ""
authors = ["Pengfei Hong", "Rishabh Bhardwaj", "Navonil Majumdar", "Somak Aditya", "Soujanya Poria"]
date = "2023-05-03"
image_preview = ""
math = true
publication_types = ["3"]
publication = "In ACL 2023 (Findings) Long Paper"
publication_short = "In *ACL 2023 (Long Paper Findings)* "
selected = true
featured = true
title = "A Robust Information-Masking Approach for Domain Counterfactual Generation"
projects = ["NLP"]
url_pdf = "https://arxiv.org/pdf/2305.02858.pdf"
url_code = "https://github.com/declare-lab/remask"
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

Domain shift is a big challenge in NLP, thus, many approaches resort to learning domain-invariant features to mitigate the inference phase domain shift. Such methods, however, fail to leverage the domain-specific nuances relevant to the task at hand. To avoid such drawbacks, domain counterfactual generation aims to transform a text from the source domain to a given target domain. However, due to the limited availability of data, such frequency-based methods often miss and lead to some valid and spurious domain-token associations. Hence, we employ a three-step domain obfuscation approach that involves frequency and attention norm-based masking, to mask domain-specific cues, and unmasking to regain the domain generic context. Our experiments empirically show that the counterfactual samples sourced from our masked text lead to improved domain transfer on 10 out of 12 domain sentiment classification settings, with an average of 2% accuracy improvement over the state-of-the-art for unsupervised domain adaptation (UDA). Further our model outperforms the state-of-the-art by achieving 1.4% average accuracy improvement in the adversarial domain adaptation (ADA) setting. Moreover, our model also shows its domain adaptation efficacy on a large multi-domain intent classification dataset where it attains state-of-the-art results.