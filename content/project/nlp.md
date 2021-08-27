+++
# Date this page was created.
date = "2016-02-24"

# Project title.
title = "Natural Language Processing"

# Project summary to display on homepage.
summary = "We investigate how to evaluate, explain and enhance neural models under the lens of reasoning."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "headers/taxinli2.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["deep-learning", "soft-logic"]`
tags = ["deep-learning", "Logic", "Language", "common-sense", "Semantic Parsing", "Knowledge Acqusition"]

# Optional external URL for project (replaces project detail page).
# external_link = "https://github.com/microsoft/TaxiNLI"

# Does the project detail page use math formatting?
math = false

+++

Using Natural Language Inference task (NLI) as a representative task for natural language understanding (NLU), my goal is the *evaluate*, *enhance* and *explain* the reasoning capabilities of language models.

<h3> Natural Language Inference </h3>
Large pre-trained language models show high performance in popular NLP benchmarks (GLUE, SuperGLUE), while failing poorly in datasets with targeted linguistic and logical phenomena. We consolidate the interesting reasoning phenomena
in Taxonomy of reasoning w.r.t the NLI task. Our first work along this line published in [CoNLL 2020](https://github.com/microsoft/TaxiNLI) showed that these models (BERT, RoBERTa) may not know how to perform certain types of reasoning such as causal, numeric, spatial, temporal; but they can identify the type of reasoning required for a new example. 

We did a follow-up, adapting the CheckList methodology, where we create a large [CheckList-NLI](https://arxiv.org/abs/2107.07229) dataset to individually yet collectively test different reasoning capabilities, including pragmatic ones. Through our test-suite, we show that such a post-hoc evaluation provides a more comprehensive overview of the behavioral nature of the language models. A thorough human study with Linguistic Olympiad participants shows that behavioral summary leads to better explanation and RoBERTa's behavior is more predictable than BERT.

<hr style="width:100%;text-align:left;margin-left:0">
<h3> Semantic Parsing </h3>
We (along with co-authors Arpit Sharma and Nguyen Vo) have explored mapping of natural language to formal representation, that enbales logical reasoning. Through several papers ([K-Parser IJCAI-15](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.717.6262&rep=rep1&type=pdf), [K-Parser NAACL 15](https://aclanthology.org/W15-0811.pdf)), we showed how such semantic parsing enables us to find event mentions, and (even patially but interpretably) solved Winograd Schema challenge problems.

<div>
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
</ul>



