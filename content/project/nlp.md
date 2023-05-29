+++
# Date this page was created.
date = "2016-02-24"

# Project title.
title = "Reasoning in NLP"

# Project summary to display on homepage.
summary = "We investigate how to evaluate, explain and enhance neural models under the lens of reasoning."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "headers/taxinli2.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["deep-learning", "soft-logic"]`
tags = ["deep-learning", "Logic", "NLP", "common-sense", "Semantic Parsing", "Knowledge Acqusition"]

# Optional external URL for project (replaces project detail page).
# external_link = "https://github.com/microsoft/TaxiNLI"

# Does the project detail page use math formatting?
math = false

+++

Models that claim to understand language, should also be able to demonstrate its abilities to reason across various dimensions. My present goal is to *evaluate*, *enhance* and *explain* the reasoning capabilities of such systems (or language models).

<h3> Natural Language Inference </h3>
Large pre-trained language models show high performance in popular NLP benchmarks (GLUE, SuperGLUE), while failing poorly in datasets with targeted linguistic and logical phenomena. We consolidate the interesting reasoning phenomena
in Taxonomy of reasoning w.r.t the NLI task. Our first work along this line published in [CoNLL 2020](https://github.com/microsoft/TaxiNLI) showed that these models (BERT, RoBERTa) may not know how to perform certain types of reasoning such as causal, numeric, spatial, temporal; but they can identify the type of reasoning required for a new example. 

We did a follow-up, adapting the CheckList methodology, where we create a large [CheckList-NLI](https://github.com/microsoft/LoNLI) dataset to individually yet collectively test different reasoning capabilities, including pragmatic ones. Through our test-suite, we show that such a post-hoc evaluation provides a more comprehensive overview of the behavioral nature of the language models. A thorough human study with Linguistic Olympiad participants shows that behavioral summary leads to better explanation and RoBERTa's behavior is more predictable than BERT. Currently, we are also exploring augmenting NLI datasets with verifiable proofs.

Summary and Extensions:
<ul> 
<li> [TaxiNLI: Taxonomic Fragmentation of the NLI Task](https://github.com/microsoft/TaxiNLI), <em>CoNLL 2020</em>
</li>
<li> [TaxiXNLI: Multi-lingual Extension of TaxiNLI](https://github.com/microsoft/TaxiXNLI), <em>EMNLP 2021 MRL Workshop</em>
</li>
<li> [LoNLI: Testing Diverse Reasoning of NLI Systems](https://github.com/microsoft/LoNLI), <em>Under review in LRE</em>
</li>

</ul>

<div>
<h4> Enhancing NLI: Multi-hop, Causality and Counterfactuals </h4>
As observed through TaxiNLI family of work, language models struggle with many important reasoning types. With Deepanway Ghoshal and Monojit choudhury, we explored a <b>less annotation-intensive</b> way to <a href=https://arxiv.org/abs/2208.14641">generate intermediate steps</a> for complex reasoning examples in free-form NLI datasets. We observe, not only, we can generate such multi-hop steps without end-to-end supervision; but the steps are accurate as they <em>can be augmented directly</em> to improve NLI model's predictive ability. 


<img src="/project/prooftypes.png" alt="img"/>
</div>

References
<ul>
<li> [Generating Intermediate Steps for NLI with Next-Step Supervision](https://arxiv.org/abs/2208.14641), <em>ArXiv 2022, Under review</em>
</li>
</ul>

<hr style="width:100%;text-align:left;margin-left:0">

Previously I have been interested in mapping natural language to formal language representation and reasoning with it. My proposed solutions towards Question-Answering and Winograd Schema Challenge during my Ph.D have been motivated by the central idea of semantic parsing, followed by logical (or probabilistic logical) reasoning.

<h3> Semantic Parsing (K-Parser) </h3>
We (led by co-authors Arpit Sharma and Nguyen Vo) have explored mapping of natural language to formal representation, that enbales logical reasoning. Through several papers ([K-Parser IJCAI-15](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.717.6262&rep=rep1&type=pdf), [K-Parser NAACL 15](https://aclanthology.org/W15-0811.pdf)), we showed how such semantic parsing enables us to find event mentions, and (even patially but interpretably) solved Winograd Schema challenge problems.

<!-- <div>
<div id="References" align="left" style="width: 100%; overflow-y: hidden;" class="wcustomhtml"><h3 style="margin-bottom:0px;">References</h3>
<hr style="float: center"></div>
</div>
<ul>
<li>
Ishan Tarunesh, Somak Aditya, Monojit Choudhury. Trusting RoBERTa over BERT: Insights from CheckListing the Natural Language Inference Task. Arxiv 2015. 
</li><li>
Pratik Joshi*, Somak Aditya*, Aalok Sathe*, Monojit Choudhury. TaxiNLI: Taking a Ride up the NLU Hill. CoNLL 2020.
</li><li>
Arpit Sharma, Somak Aditya, Vo Nguyen and Chitta Baral. Towards Addressing the Winograd Schema Challenge - Building and Using a Semantic Parser and a Knowledge Hunting Module. IJCAI 2015.
</li><li>
Somak Aditya, Chitta Baral, Nguyen Ha Vo, Joohyung Lee, Jieping Ye, Zaw Naung, Barry Lumpkin, Jenny Hastings, Richard Scherl, Dawn M. Sweet, Daniela Inclezan. Recognizing Social Constructs from Textual Conversation. HLT-NAACL 2015.
</li><li>
Arpit Sharma, Nguyen H. Vo, Somak Aditya and Chitta Baral. Identifying Various Kinds of Event Mentions in K-Parser Output The 3rd Workshop on EVENTS: Definition, Detection, Coreference, and Representation. HLT-NAACL 2015.
</li>
</ul> -->



