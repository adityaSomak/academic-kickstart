+++
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.

date = "2016-04-20T00:00:00"
draft = false

title = "News"
subtitle = ""
widget = "custom"

# Order that this section will appear in.
weight = 30

+++
<script>
    (function($){
        $(window).on("load",function(){
            $("body").mCustomScrollbar({
				theme:"inset-dark",
				scrollInertia:300,
				mouseWheel:{ enable: true }
            });
        });
    })(jQuery);
</script>


<div class="news" style="height:400px;width:100%;font:22px/24px;font-family: cambria;">
    <div class="table-responsive" style="max-height: 30vw">
    <table class="table table-sm table-borderless">            
    <tbody>
            <tr><th scope="row" style="width: 100px">August 2025</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     EMNLP 2025: 1 Main (EduVidQA: Generating and Evaluating Long-form Answers to Student Questions based on Lecture Videos) and 1 findings (NLKI: A lightweight Natural Language Knowledge Integration Framework for improving small VLMs in Commonsense VQA tasks) accepted. Congratulations to all co-authors. Preprints will be out soon.
            </td>
            <tr><th scope="row" style="width: 100px">July 2025</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     IIIT Summer School 2025: My slides presentend at IIIT-H CVIT Summer School of AI is now public <a href="https://drive.google.com/file/d/1iUTRP7bMPAbqFSuF7_UPjF6yoNhR4i_l/view?usp=sharing">Transformers and Large Language Models - A Primer</a> and <a href="https://drive.google.com/file/d/1CPTIlAuCt0dRy9gyAlP7zjyXRB7qQ74E/view?usp=sharing">Reasoning and Large Language Models - Part II</a>. Please do not use the slides without proper acknowledgement. 
            </td>
            <tr><th scope="row" style="width: 100px">June 2025</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     IIIT Summer School 2025: Invited as a speaker for a session at IIIT CVIT Summer School 2025 (<a href="https://cvit.iiit.ac.in/summerschool2025/speakers.php">List of Speakers, CVIT Summer School</a>)
            </td>
            <tr><th scope="row" style="width: 100px">May 2025</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     MSRI 2025: Invited as a speaker/participant at Microsoft Research India Academic Summit 2025.
            </td>
            <tr><th scope="row" style="width: 100px">May 2025</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i>ACL 2025: Paper on "Evaluating LLMs' Mathematical and Coding Competency through Ontology-guided Interventions" accepted in ACL Findings. Co-authors: Pengfei Hong, Deepanway Ghoshal, Navonil Majumdar, Rada Mihalcea, Soujanya Poria
            </td>
            <tr><th scope="row" style="width: 100px">April 2025</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     CACM 2025: Invited to be part of CACM Reviewer Board Pilot project (to be announced on June 1st).
            </td>
            <tr><th scope="row" style="width: 100px">Mar 2025</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     CODS 2025: Invited as a Demo Track co-chair.
            </td>
            <tr><th scope="row" style="width: 100px">Feb 2025</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     IISc: Invited talk on "Integrating Knowledge and Reasoning in Vision & NLP through Neurosymbolic Methods".
            </td>
            <tr><th scope="row" style="width: 100px">Jan 2025</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> NAACL 2025: One long paper in main track <a href="https://arxiv.org/pdf/2502.07101">"SMAB: MAB based word Sensitivity Estimation Framework and its Applications in Adversarial Text Generation"</a> with Saurabh Kumar Pandey, Sachin Vashishtha, and Monojit Choudhury (equal contribution from Saurabh and Sachin).
            </td>
            <tr><th scope="row" style="width: 100px">Dec 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     Invited talk at National Research Council, Canada. Host: Dr. Sowmya Vajjala. Topic: <em>Evolution of Neurosymbolic NLP: From Integrating "Knowledge" to "Skills"</em>.
            </td>
            <tr><th scope="row" style="width: 100px">Sep 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> CONLL 2024: One Long Paper accepted in Main Track about <a href="https://arxiv.org/pdf/2402.12881">Text2Afford: Probing Object Affordance Prediction abilities of Language Models solely from Text</a> (with Sayantan Adak, Daivik Agarwal, Animesh Mukherjee).
            </td>
            <tr><th scope="row" style="width: 100px">Sep 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> EMNLP 2024: Two Long Papers accepted in Main Track about i) <a href="https://openreview.net/pdf?id=6OZm8mkwrp">Code Prompting Elicits Conditional Reasoning Abilities in Text+Code LLMs</a> (with Haritz Puerto, Martin Tutek, Xiaodan Zhu, & Iryna Gurevych), ii) <a href="https://openreview.net/pdf?id=TfBbI5xicm">ERVQA: A Dataset to Benchmark the Readiness of Large Vision Language Models in Hospital Environments</a> (Sourjyadip Ray, Kushal Gupta, Soumi Kundu, Dr Payal Arvind Kasat, Somak Aditya, Pawan Goyal)
            </td>
            <tr><th scope="row" style="width: 100px">June 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    Invited for a talk at <a href="https://www.uni-saarland.de/en/home.html">Saarland University</a>  on "The lack of reasoning ability in LLMs, the promise of Neurosymbolic NLP, and the pitfalls of "both" (Host: <a href="https://www.mhahn.info/">Dr. Michael Hahn</a>).
            </td>
            <tr><th scope="row" style="width: 100px">June 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    Invited for a talk at the Probability for AI-ML-NLP series, IIT Bombay (Host: Dr. Pushpak Bhattacharya).
            </td>
            <tr><th scope="row" style="width: 100px">May 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    Invited for a talk at UKP Day (Host: <a href="https://www.informatik.tu-darmstadt.de/ukp/ukp_home/head_ukp/index.en.jsp">Dr. Iryna Gurevych</a>).
            </td>
             <tr><th scope="row" style="width: 100px">May 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    TU Darmstadt: Visiting UKP Lab, TU Darmstadt for the summer (Host: <a href="https://www.informatik.tu-darmstadt.de/ukp/ukp_home/head_ukp/index.en.jsp">Dr. Iryna Gurevych</a>).
            </td>
            <tr><th scope="row" style="width: 100px">Mar 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> NAACL 2024: Long Paper accepted in Main Track about Tool-Augmented LLMs and Mathematical Reasoning <a href="https://arxiv.org/pdf/2402.17231.pdf">MATHSENSEI: A Tool-Augmented Large Language Model for Mathematical Reasoning</a> with Debrup Das, Debopriyo Banerjee, and Ashish Kulkarni. A shorter draft previously also published in ICLR 2024 ME-FOMO Workshop.
            </td>
            <tr><th scope="row" style="width: 100px">Feb 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   <em>Tr</em>$^2$AIL Lab: <em>Tr</em>$^2$AILer <a href="authors/atharva">Atharva Naik</a> received PhD offers from CMU, USC, UMass Amherst and Cornell.
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Feb 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    <em>Tr</em>$^2$AIL Lab: <em>Tr</em>$^2$AILer <a href="authors/debrupd">Debrup Das</a> received PhD offers from UIUC and UM Amherst.
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Feb 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    ECAI 2024: Serving as an SPC member.
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Feb 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> LREC-COLING 2024: 1 Paper accepted about Jailbreaks and LLMs <a href="https://arxiv.org/abs/2305.14965">Tricking LLMs into Disobedience: Understanding, Analyzing, and Preventing Jailbreaks</a> with Abinav, Atharva, Sachin and Monojit.
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Jan 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    Google Research @Week: Spent a wonderful time at Google Research India with stalwarts from the Indian AI community. Check out posts by Jeff Dean on <a href="https://x.com/somakaditya/status/1752991472914518415?s=20">Twitter</a>.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Jan 2024</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> Preprints: Two new preprints released on numeric and conditional reasoning: 1) <a href=https://arxiv.org/pdf/2401.09395.pdf">"STUCK IN THE QUICKSAND OF NUMERACY, FAR FROM AGI SUMMIT: EVALUATING LLMS’ MATHEMATICAL COMPETENCY THROUGH ONTOLOGY-GUIDED PERTURBATIONS"</a> with SUTD, University of Michigan and 2) <a href="https://arxiv.org/pdf/2401.10065.pdf">Code Prompting Elicits Conditional Reasoning Abilities in Text+Code LLMs"</a> with UKP Lab, TU Dramstadt, Queen's University.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Dec 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    Microsoft: Thanks Microsoft for awarding additional Azure grant of USD 20000 under the  "Accelerate Foundation Models Academic Research" initiative.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Nov 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    CoLM 2023: Invited as Area Chair in the new <a href="https://colmweb.org/index.html">Conference on Langugage Models</a>! Please submit your papers.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Dec 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    Microsoft: Thanks Microsoft for awarding additional Azure grant of USD 20000 under the  "Accelerate Foundation Models Academic Research" initiative.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Nov 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    CoLM 2023: Invited as Area Chair in the new <a href="https://colmweb.org/index.html">Conference on Langugage Models</a>! Please submit your papers.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Nov 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    <em>Tr</em>$^2$AIL Lab: <em>Tr</em>$^2$AILer <a href="authors/sachin">Sachin Vashishtha</a> won the PMRF scholarship for 2023! Congratulations Sachin!
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Nov 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   <em>Tr</em>$^2$AIL Lab: <em>Tr</em>$^2$AILer and MTech student <a href="authors/debrupd">Debrup Das</a>'s internship with Rakuten India got extended for the second time. He is working now for 8 months funded by Rakuten! Congratulations Debrup!!
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Sep 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> AACL-IJCNLP 2023: Two Long papers accepted in Main Conference: 1) SYNC: A Structurally guided Hard Negative Curricula for Efficient Neural Code Search (with Atharva Naik, Soumitra Das, Jyothi Vedurada), 2) Prover: Generating Intermediate Steps for NLI with Commonsense Knowledge Retrieval and Next-Step Prediction (with Deepanway Ghosal, Monojit Choudhury). Stay tuned for code and preprints!
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Aug 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> LREV 2023: LREV Journal on Logical NLI dataset accepted with Ishan Tarunesh and Monojit Choudhury (Updated preprint soon).
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Jun 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    EMNLP 2023: Invited as an Area Chair.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Jun 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   AAAI 2024: Invited as a Senior PC member for the second time. 
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">May 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    Microsoft: Received the "Accelerate Foundation Models Academic Research" 2023 by Microsoft jointly with Prof. Animesh Mukherjee. This comes with large Azure credits and OpenAI API access.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">May 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> ACL 2023: Our work on "A Robust Information-Masking Approach for Domain Counterfactual Generation" with Prof. Soujanya Poria, Pengfei Hong, Rishabh Bhardwaj, and Navonil Majumdar. Full credit goes to my co-authors!!! 
            </td>
            </tr>
             <tr><th scope="row" style="width: 100px">Apr 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    Ashoka: I was invited to give a talk at <a href="https://www.ashoka.edu.in/">Ashoka University</a> for the AI@Ashoka Workshop. The talk slides are available here: <a href="https://drive.google.com/file/d/1tvuSEBKxe87Vl1LGfFc5RZpXi1I2xcc-/view?usp=sharing">AI Progress & Hype under the lens of Reasoning (PDF 14.0 MB size)</a>.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Mar 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   CS60092 COURSE UPDATE:  Recording of GUEST LECTURE BY <a href="https://anikem.github.io/">Dr. Anirudh Kembhavi</a>, Director of Computer Vision at <a href="https://allenai.org/">Allen Institute for AI (AI2)</a> is available <a href="http://shorturl.at/gizQZ">here</a>.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Jan 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    Toloka AI Grant: Received the Toloka AI Annotation Grant of USD 300 for data creation in the Toloka AI platform. Thanks Toloka AI!
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Jan 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   IIT KGP FSRG: Received the FSRG Grant aproval from IIT Kharagpur on "The Role of Feedback in Vision-Language enabled Embodied Agents towards Application to Disaster Management"!
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Jan 2023</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    USPTO: Second patent granted (filed during Adobe Research) on Marketing Knowledge Graph Creation! Congratulations to my co-author (/co-inventor) Dr. Atanu Sinha!
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Dec 2022</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   IndoML 2022: My invited talk on "The Relevance of Representation and Reasoning in the era of (Large) Language Models" is available <a href="https://youtu.be/0US3NMdorPQ?t=5226">here</a>.
            </td>
            </tr>  
            <tr><th scope="row" style="width: 100px">Sep 2022</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> AACL-IJCNLP 2022: Two papers accepted. "Multilingual CheckList: Generation and Evaluation" in AACL Findings and "Vector Space Interpolation for Query Expansion" as a short paper. Kudos to the all my co-authors! <em> Stay tuned for preprints. </em> 
            </td>
            </tr>  
            <tr><th scope="row" style="width: 100px">Sep 2022</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   SERB DST: Startup Research Grant on <em>"Learning from Rules and Data for Image Analytics"</em> got Approved!
            </td>
            </tr>  
            <tr><th scope="row" style="width: 100px">Aug 2022</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   New Prerpint: <a href="https://arxiv.org/abs/2208.14641">Generating Intermediate Steps for NLI with Next-Step Supervision</a>. We show how intermediate steps/proof tree can help. The work is under review. Code and website to be public soon. 
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Jul 2022</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   AAAI 2023: Honored to be serving as a Senior PC member for AAAI 2023! 
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Apr 2022</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   IIT KGP: I was promoted to Assistant Professor Grade-I (effective from Nov 29, 2021).  
            </td>
            </tr>  
            <tr><th scope="row" style="width: 100px">Feb 2022</th>
            <td>
                   Rakuten Institute of Technology: Invited Talk on "Evolution of Representation and Reasoning in the era of Deep Learning".  
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Jan 2022</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   Google India: USD 5K Google Cloud Credits Award.  
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Dec 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   MSR India SNLP Group: Invited End-of-Postdoc Talk.  
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Nov 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   <span class="blink" style="color:red">IIT KGP: Joined IIT KGP CSE as Assistant Professor.</span> 
            </td>
            </tr>   
            <tr><th scope="row" style="width: 100px">Oct 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> AAAI 2022 (Demo): <em>LITMUS Predictor: An AI Assistant for Building Reliable, High-performing and Fair Multilingual NLP Systems</em> accepted in AAAI 2022 Demonstrations track (joint work with the Speech and NLP group at MSR India).  
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Oct 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    EMNLP 2021 (MRL Workshop): <a href="https://github.com/microsoft/TaxiXNLI">TaxiXNLI</a> dataset released publicly!
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Sep 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   EMNLP 2021 (MRL workshop): Work on "Analyzing the Effects of Reasoning Types on Cross-Lingual Transfer Performance" accepted, with co-authors Karthikeyan K, Aalok Sathe and Monojit Choudhury.  
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Aug 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    IndoML 2021: Invited to be a part of the organizing committee (specifically <a href="http://indoml.in/">datathon@IndoML</a>). See <a href="https://labs.iitgn.ac.in/datascience/indoml/">IndoML 2020</a> for reference.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Aug 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                   NeurIPS-2021 MathAI4ED: Invited as a PC member. 
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Aug 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     Invited Lecture at <a href="https://edu.ieee.org/in-acsir/ieee-sps/#1625137355153-2c7ec800-1f0f">IEEE SPS Deep Learning Summer School</a> on  "The Interplay between Deep Learning, Logic, and Reasoning".
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Jun 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     CIKM 2021: Workshop CfP for <a href="https://sites.google.com/view/kinn2021/">"Knowledge Injection in Neural Networks"</a> is now public! Please consider submitting!!
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Jun 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     Seminar at IIT-Hyderabad CSE on "Explicit Knowledge and Reasoning in the era of Deep Learning".
            </td>
            </tr> 
             <tr><th scope="row" style="width: 100px">May 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                     Seminar at IIT-Kharagpur CSE on "Explicit Knowledge and Reasoning in the era of Deep Learning".
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">May 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>
                    Seminar at IIT-Kharagpur Center for AI on "Explicit Knowledge and Reasoning in the era of Deep Learning".
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Mar 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>    ICLR 2021 <a href="https://mathai-iclr.github.io/">(MathAI workshop)</a>: Work on "Analyzing The Nuances of Transformers' Polynomial Simplification Abilities" accepted, with co-authors Vishesh Agarwal, and Navin Goyal. 
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Mar 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>   IJCAI 2021: Workshop CfP for <a href="https://nsnli.github.io">"Is Neuro-symbolic SOTA still a myth for NLI"</a> is now public! Please consider submitting!!
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Mar 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>   IJCAI 2021: Workshop proposoal on "Is Neuro-symbolic SOTA still a myth for NLI" accepted with co-organizers <a href="https://researcher.watson.ibm.com/researcher/view.php?person=ibm-Maria.Chang">Maria Chang</a>, <a href="https://www.cs.utexas.edu/people/faculty-researchers/swarat-chaudhuri">Swarat Chaudhuri</a>, <a href="https://www.microsoft.com/en-us/research/people/monojitc/">Monojit Choudhury</a>, and <a href="https://sebdumancic.github.io/">Sebastijan Dumancic</a>.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Mar 2021</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>  ICLR 2021 <a href="https://mathai-iclr.github.io/">(MathAI workshop)</a>: Invited as PC member.
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Dec 2020</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>  ACL-IJCNLP-2021: Invited as PC member.
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Nov 2020</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>  CoNLL 2020: Our pre-recorded <a href="https://slideslive.com/38939466/taxinli-taking-a-ride-up-the-nlu-hill">talk</a> on TaxiNLI is online. Hope you enjoy (modulo my lack of expressions :))!
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Oct 2020</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>  NAACL-2021: Invited as PC Member.
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Sep 2020</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>  CoNLL-2020: <a href="https://arxiv.org/abs/2009.14505">TaxiNLI: Taking a ride up the NLU Hill</a> accepted at CoNLL.
            </td>
            </tr> 
            <tr><th scope="row" style="width: 100px">Aug 2020</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>  EACL-2021, EMNLP-2020, LANTERN@COLING-20: Invited as PC Member.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Feb 2020</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>   Joined MSR India as a Postdoc Researcher.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Jan 2020</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>  ACL-2020: Invited as PC Member.
            </td>
            </tr>
            <tr><th scope="row" style="width: 100px">Dec 2019</th>
                  <!-- <th scope="row" >Oct 2023</th> -->
            <td>  AAAI-20: "Uncovering Relations for Marketing Knowledge Representation" accepted in StarAI workshop full paper.
            </td>
            </tr>
<!-- 
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Dec 2019]</span>  IJCAI-20: Invited as PC Member.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Oct 2019]</span>  AAAI-20: Exploratory Navigation and Selective Readoing got accepted as AAAI demo.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Sep 2019]</span>  Adobe News: Knowledge Graph Research appears in <a href="https://research.adobe.com/news/knowledge-graphs-turning-complex-information-into-helpful-answers/">Adobe News</a> !
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2019]</span>  AAAI-20: Invited as an AAAI 2020 PC Member!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2019]</span>  IJCAI-19: Invited as an IJCAI DC Career Panelist!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2019]</span>  IJCAI-19: Our work on <a href="https://www.ijcai.org/proceedings/2019/0873.pdf">Integrating Knowledge and Reasoning in Image Understanding"</a> got accepted in IJCAI 2019 Survey!
<br/>
-->
    </tbody>
    </table>
     </div> 
</div>

<!-- <div class="mCustomScrollbar" data-mcs-theme="inset-dark" style="height:300px;width:100%;font:22px/24px;font-family: cambria; overflow:auto;">  -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Feb 2024]</span> <em>Tr</em>$^2$AIL Lab: <em>Tr</em>$^2$AILer <a href="authors/atharva">Atharva Naik</a> received PhD offers from CMU, USC, UMass Amherst and Cornell.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Feb 2024]</span> <em>Tr</em>$^2$AIL Lab: <em>Tr</em>$^2$AILer <a href="authors/debrupd">Debrup Das</a> received PhD offers from UIUC and UM Amherst.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Feb 2024]</span> ECAI 2024: Serving as an SPC member.
 <br/>
<i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> <span style="font-weight: bold;">[Feb 2024]</span> LREC-COLING 2024: 1 Paper accepted about Jailbreaks and LLMs <a href="https://arxiv.org/abs/2305.14965">Tricking LLMs into Disobedience: Understanding, Analyzing, and Preventing Jailbreaks</a> with Abinav, Atharva, Sachin and Monojit.
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Jan 2024]</span> Google Research @Week: Spent a wonderful time at Google Research India with stalwarts from the Indian AI community. Check out posts by Jeff Dean on <a href="https://x.com/somakaditya/status/1752991472914518415?s=20">Twitter</a>.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Jan 2024]</span> Preprints: Two new preprints released on numeric and conditional reasoning: 1) <a href=https://arxiv.org/pdf/2401.09395.pdf">"STUCK IN THE QUICKSAND OF NUMERACY, FAR FROM AGI SUMMIT: EVALUATING LLMS’ MATHEMATICAL COMPETENCY THROUGH ONTOLOGY-GUIDED PERTURBATIONS"</a> with SUTD, University of Michigan and 2) <a href="https://arxiv.org/pdf/2401.10065.pdf">Code Prompting Elicits Conditional Reasoning Abilities in Text+Code LLMs"</a> with UKP Lab, TU Dramstadt, Queen's University.
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Dec 2023]</span> Microsoft: Thanks Microsoft for awarding additional Azure grant of USD 20000 under the  "Accelerate Foundation Models Academic Research" initiative.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>[Nov 2023]</span> CoLM 2023: Invited as Area Chair in the new <a href="https://colmweb.org/index.html">Conference on Langugage Models</a>! Please submit your papers.
<br/> -->
<!-- <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> <span style="font-weight: bold;">[Nov 2023]</span> <em>Tr</em>$^2$AIL Lab: <em>Tr</em>$^2$AILer <a href="authors/sachin">Sachin Vashishtha</a> won the PMRF scholarship for 2023! Congratulations Sachin!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Nov 2023]</span> <em>Tr</em>$^2$AIL Lab: <em>Tr</em>$^2$AILer and MTech student <a href="authors/sachin">Debrup Das</a>'s internship with Rakuten India got extended for the second time. He is working now for 8 months funded by Rakuten! Congratulations Debrup!!
<br/> -->
<!-- <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> <span style="font-weight: bold;">[Sep 2023]</span> AACL-IJCNLP 2023: Two Long papers accepted in Main Conference: 1) SYNC: A Structurally guided Hard Negative Curricula for Efficient Neural Code Search (with Atharva Naik, Soumitra Das, Jyothi Vedurada), 2) Prover: Generating Intermediate Steps for NLI with Commonsense Knowledge Retrieval and Next-Step Prediction (with Deepanway Ghosal, Monojit Choudhury). Stay tuned for code and preprints!
<br/>
<i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> <span style="font-weight: bold;">[Aug 2023]</span> LREV 2023: LREV Journal on Logical NLI dataset accepted with Ishan Tarunesh and Monojit Choudhury (Updated preprint soon).
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Jul 2023]</span> CS60050: NO DIRECT EMAILS FOR COURSE REGISTRATION WILL BE ENTERTAINED. They may be spammed or even reported.
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>  <span style="font-weight: bold;">[Jun 2023]</span> EMNLP 2023: Invited as an Area Chair.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>  <span style="font-weight: bold;">[Jun 2023]</span> AAAI 2024: Invited as a Senior PC member for the second time. 
<br/> -->
<!-- <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i>  <span style="font-weight: bold;">[May 2023]</span> Microsoft: Received the "Accelerate Foundation Models Academic Research" 2023 by Microsoft jointly with Prof. Animesh Mukherjee. This comes with large Azure credits and OpenAI API access. 
<br/>
<i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i>  <span style="font-weight: bold;">[May 2023]</span> ACL 2023: Our work on "A Robust Information-Masking Approach for Domain Counterfactual Generation" with Prof. Soujanya Poria, Pengfei Hong, Rishabh Bhardwaj, and Navonil Majumdar. Full credit goes to my co-authors!!!
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Apr 2023]</span> Ashoka: I was invited to give a talk at <a href="https://www.ashoka.edu.in/">Ashoka University</a> for the AI@Ashoka Workshop. The talk slides are available here: <a href="https://drive.google.com/file/d/1tvuSEBKxe87Vl1LGfFc5RZpXi1I2xcc-/view?usp=sharing">AI Progress & Hype under the lens of Reasoning (PDF 14.0 MB size)</a>.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Mar 2023]</span> CS60092 COURSE UPDATE:  Recording of GUEST LECTURE BY <a href="https://anikem.github.io/">Dr. Anirudh Kembhavi</a>, Director of Computer Vision at <a href="https://allenai.org/">Allen Institute for AI (AI2)</a> is available <a href="http://shorturl.at/gizQZ">here</a>.
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">
[Jan 2023]</span> Toloka AI Grant: Received the Toloka AI Annotation Grant of USD 300 for data creation in the Toloka AI platform. Thanks Toloka AI!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">
[Jan 2023]</span> IIT KGP FSRG: Received the FSRG Grant aproval from IIT Kharagpur on "The Role of Feedback in Vision-Language enabled Embodied Agents towards Application to Disaster Management"!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">
[Jan 2023]</span> USPTO: Second patent granted (filed during Adobe Research) on Marketing Knowledge Graph Creation! Congratulations to my co-author (/co-inventor) Dr. Atanu Sinha!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Jan 2023]</span> CS60092 COURSE UPDATE:  <span style='color: red'>INVITED GUEST LECTURE</span> BY <a href="https://anikem.github.io/">Dr. Anirudh Kembhavi</a>, Director of Computer Vision at <a href="https://allenai.org/">Allen Institute for AI (AI2)</a> on MARCH 13, MONDAY confirmed!!
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>   <span style="font-weight: bold;">[Dec 2022]</span> IndoML 2022: My invited talk on "The Relevance of Representation and Reasoning in the era of (Large) Language Models" is available <a href="https://youtu.be/0US3NMdorPQ?t=5226">here</a>.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>   <span style="font-weight: bold;">[Sep 2022]</span> AACL-IJCNLP 2022: Two papers accepted. "Multilingual CheckList: Generation and Evaluation" in AACL Findings and "Vector Space Interpolation for Query Expansion" as a short paper. Kudos to the all my co-authors! <em> Stay tuned for preprints. </em> 
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>   <span style="font-weight: bold;">[Sep 2022]</span> SERB DST: Startup Research Grant on <em>"Learning from Rules and Data for Image Analytics"</em> got Approved!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>   <span style="font-weight: bold;">[Aug 2022]</span> New Prerpint: <a href="https://arxiv.org/abs/2208.14641">Generating Intermediate Steps for NLI with Next-Step Supervision</a>. We show how intermediate steps/proof tree can help. The work is under review. Code and website to be public soon.
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>   <span style="font-weight: bold;">[Jul 2022]</span>  AAAI 2023: Honored to be serving as a Senior PC member for AAAI 2023!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>   <span style="font-weight: bold;">[Apr 2022]</span>  I was promoted to Assistant Professor Grade-I (effective from Nov 29, 2021). 
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>   <span style="font-weight: bold;">[Feb 2022]</span>  Rakuten Institute of Technology: Invited Talk on "Evolution of Representation and Reasoning in the era of Deep Learning". 
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>   <span style="font-weight: bold;">[Jan 2022]</span>  Google India: USD 5K Google Cloud Credits Award. 
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>   <span style="font-weight: bold;">[Dec 2021]</span>  MSR India SNLP Group: Invited End-of-Postdoc Talk.</span>. 
<br/>
<span class="blink" style="color:red"><i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i>   <span style="font-weight: bold;">[Nov 2021]</span>  IIT KGP: Joined IIT KGP as Assistant Professor</span>. 
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>  <span style="font-weight: bold;">[Oct 2021]</span>  AAAI 2022 (Demo): <em>LITMUS Predictor: An AI Assistant for Building Reliable, High-performing and Fair Multilingual NLP Systems</em> accepted in AAAI 2022 Demonstrations track (joint work with the Speech and NLP group at MSR India). 
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>  <span style="font-weight: bold;">[Oct 2021]</span>  IndoML 2021: <a href="https://indoml.in/"> IndoML Datathon</a> registration is open for students. Lucrative cash prize, and a series of exciting talks by thought leaders in ML/NLP awaits you! So go forth and <a href="https://docs.google.com/forms/d/e/1FAIpQLSd5qftS0eyfIH3QGk3YTwCmMHX7uLVDrk4Q7uz4fQ08nIc_Qw/viewform">register</a>.
<br/>
<i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> 
<span style="font-weight: bold;">[Oct 2021]</span>  EMNLP 2021 (MRL Workshop): <a href="https://github.com/microsoft/TaxiXNLI">TaxiXNLI</a> dataset released publicly!
<br/>-->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Sep 2021]</span>  EMNLP 2021 (MRL workshop): Work on "Analyzing the Effects of Reasoning Types on Cross-Lingual Transfer Performance" accepted, with co-authors Karthikeyan K, Aalok Sathe and Monojit Choudhury.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2021]</span>  MILA Philosophy of NLP Reading Group: Invited as a speaker.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2021]</span>  IndoML 2021: Invited to be a part of the organizing committee (specifically <a href="http://indoml.in/">datathon@IndoML</a>). See <a href="https://labs.iitgn.ac.in/datascience/indoml/">IndoML 2020</a> for reference.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2021]</span>  NeurIPS-2021 MathAI4ED: Invited as a PC member.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>  <span style="font-weight: bold;">[Aug 2021]</span>   Invited Lecture at <a href="https://edu.ieee.org/in-acsir/ieee-sps/#1625137355153-2c7ec800-1f0f">IEEE SPS Deep Learning Summer School</a> on  "The Interplay between Deep Learning, Logic, and Reasoning"
<br/>  -->
 <!-- <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i>  <span style="font-weight: bold;">[Jun 2021]</span>   CIKM 2021: Workshop CfP for <a href="https://sites.google.com/view/kinn2021/">"Knowledge Injection in Neural Networks"</a> is now public! Please consider submitting!!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>  <span style="font-weight: bold;">[Jun 2021]</span>   Seminar at IIT-Hyderabad CSE on "Explicit Knowledge and Reasoning in the era of Deep Learning"
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>   <span style="font-weight: bold;">[May 2021]</span>   Seminar at IIT-Kharagpur CSE on "Explicit Knowledge and Reasoning in the era of Deep Learning".
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i>   <span style="font-weight: bold;">[May 2021]</span>   Seminar at IIT-Kharagpur Center for AI on "Explicit Knowledge and Reasoning in the era of Deep Learning".
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i><span style="font-weight: bold;">[Mar 2021]</span>  ICLR 2021 <a href="https://mathai-iclr.github.io/">(MathAI workshop)</a>: Work on "Analyzing The Nuances of Transformers' Polynomial Simplification Abilities" accepted, with co-authors Vishesh Agarwal, and Navin Goyal. 
<br/>
<i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i>  <span style="font-weight: bold;">[Mar 2021]</span>   IJCAI 2021: Workshop CfP for <a href="https://nsnli.github.io">"Is Neuro-symbolic SOTA still a myth for NLI"</a> is now public! Please consider submitting!!
<br/>
<i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> <span style="font-weight: bold;">[Mar 2021]</span>  IJCAI 2021: Workshop proposoal on "Is Neuro-symbolic SOTA still a myth for NLI" accepted with co-organizers <a href="https://researcher.watson.ibm.com/researcher/view.php?person=ibm-Maria.Chang">Maria Chang</a>, <a href="https://www.cs.utexas.edu/people/faculty-researchers/swarat-chaudhuri">Swarat Chaudhuri</a>, <a href="https://www.microsoft.com/en-us/research/people/monojitc/">Monojit Choudhury</a>, and <a href="https://sebdumancic.github.io/">Sebastijan Dumancic</a>.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Mar 2021]</span>  ICLR 2021 <a href="https://mathai-iclr.github.io/">(MathAI workshop)</a>: Invited as PC member.
<br/> 
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Dec 2020]</span>  ACL-IJCNLP-2021: Invited as PC member.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Nov 2020]</span>  CoNLL 2020: Our pre-recorded <a href="https://slideslive.com/38939466/taxinli-taking-a-ride-up-the-nlu-hill">talk</a> on TaxiNLI is online. Hope you enjoy (modulo my lack of expressions :))!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Oct 2020]</span>  NAACL-2021: Invited as PC Member.
<br/> 
<i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> 
<span style="font-weight: bold;">[Oct 2020]</span>  CoNLL-2020: <a href="https://github.com/microsoft/TaxiNLI">TaxiNLI</a> dataset released publicly!
<br/> 
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Sep 2020]</span>  CoNLL-2020: <a href="https://arxiv.org/abs/2009.14505">TaxiNLI: Taking a ride up the NLU Hill</a> accepted at CoNLL.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2020]</span>  EACL-2021: Invited as PC Member.
<br/> -->
<!-- <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Mar 2020]</span>  EMNLP-20: Invited as PC Member. 
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Mar 2020]</span>  LANTERN@COLING-20: Invited as PC Member.
<br/>
<i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> 
<span style="font-weight: bold;">[Feb 2020]</span>  Joined MSR India as a Postdoc Researcher.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Jan 2020]</span>  ACL-20: Invited as PC Member.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Dec 2019]</span> USPTO: "Knowledge-sharing between cross-domain Agents" work approved internally to be filed..
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Dec 2019]</span>  AAAI-20: "Uncovering Relations for Marketing Knowledge Representation" accepted in StarAI workshop full paper.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Dec 2019]</span>  IJCAI-20: Invited as PC Member.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Oct 2019]</span>  AAAI-20: Exploratory Navigation and Selective Readoing got accepted as AAAI demo.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Sep 2019]</span>  Adobe News: Knowledge Graph Research appears in <a href="https://research.adobe.com/news/knowledge-graphs-turning-complex-information-into-helpful-answers/">Adobe News</a> !
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2019]</span>  AAAI-20: Invited as an AAAI 2020 PC Member!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2019]</span>  IJCAI-19: Invited as an IJCAI DC Career Panelist!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2019]</span>  IJCAI-19: Our work on <a href="https://www.ijcai.org/proceedings/2019/0873.pdf">Integrating Knowledge and Reasoning in Image Understanding"</a> got accepted in IJCAI 2019 Survey!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[May 2019]</span>  USPTO: First patent on Marketing Knowledge Graph Creation approved!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Nov 2018]</span> WACV-19: Our work on "Spatial Knowledge Distillation on Visual Reasoning" got accepted in WACV 2019!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Oct 2018]</span> KR-19: We had a successful workshop filled with intersting talks from researchers from University of Leeds, IBM Research US, University of Adelaide and Army Research Lab. Their
talks are avaibale at: <a href="https://sites.google.com/view/r2k2018/schedule"></a>.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2018]</span>   My doctoral dissertation is now publicly available for download in the <a href="https://repository.asu.edu/items/50115">ASU Digital Repostory</a>.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Aug 2018]</span>  UAI-18: We presented this <a href="https://drive.google.com/file/d/1ZwNZDw656IHWb4FLb0pcDltn9rrTHZlg/view?usp=sharing">poster</a> for "Combining Knowledge and Reasoning through Probabilistic Soft Logic for Image Puzzle Solving" in UAI 2018.
<br/>
 <i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> <span style="font-weight: bold;">[June 2018]</span>  Successfully defended my thesis. My slides are available on <a href="https://www.dropbox.com/s/xzkr2c7r95wgkpq/PhDDefenseTalk2018.pdf?dl=0">dropbox</a>.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[June 2018]</span> Published the Image Riddles code for public use that was used in UAI-18 work. Visit <a href="https://github.com/adityaSomak/ImageRiddleSolving">Github</a>.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[June 2018]</span> Published the PSL engine code for public use that was used in AAAI-18 work. Visit <a href="https://github.com/adityaSomak/PSLQA">Github</a>.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[May 2018]</span>  UAI-18: Our paper on Image Riddles is accepted in <a href="http://auai.org/uai2018/index.php">UAI 2018</a> (30% acceptance rate).
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[May 2018]</span>  Invited as a reviewer in Robotics and Autonomus Systems journal.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[May 2018]</span>  Our <a href="https://sites.google.com/view/r2k2018/home">Website</a> for KR-2018 workshop is live! Please consider submitting to the workshop.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Mar 2018]</span>  We are organizing the first workshop on "Induce and Deduce: Integrating learning of representations and models with deductive, explainable reasoning that leverages knowledge" in KR 2018 (Phoenix, 27-29 Oct). Website coming soon!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Mar 2018]</span>  I am awarded the University Graduate Fellowship for Spring 2018 for the third time. Thank you ASU, CIDSE!
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Feb 2018]</span>  AAAI-18: Presented our work on "Explicit Reasoning over End-to-End Neural Architectures" in AAAI 2018.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Jan 2018]</span>  ASU SW Robotics Symposium-18: Presented our work on "Explicit Reasoning over End-to-End Neural Architectures" in ASU SouthWest Robotics Symposium. The work was nominated for Best Abstract award.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Dec 2017]</span>  CVIU-17: Our accepted manuscript in CVIU is now available online: <a href="http://www.sciencedirect.com/science/article/pii/S1077314217302291">"Image Understanding using Vision and Reasoning through Scene Description Graph"</a>
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Dec 2017]</span>  CVIU-17: Our work "Image Understanding using Vision and Reasoning through Scene Description Graph" has been accepted in the reputed <b>Computer Vision and Image Understanding (CVIU)</b> journal.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Nov 2017]</span>  Our Work on Explicit Reasoning over End-To-End Neural Architectures has been accepted in <b>AAAI 2018 (Acceptance Rate: 24.5%, 933 accepted out of 3.8k)</b>.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Nov 2017]</span>  <a href="http://www.visionandreasoning.wordpress.com">Vision and Reasoning Website</a> is live.</b>
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Oct 2017]</span>  Invited as a reviewer for The Visual Computer journal.
<br/>
  <i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[July 2017]</span>  Work on Image Riddles accepted as Extended Abstract on <a href="http://www.visionmeetscognition.org/schedule.html">Vision Meets Cognition Workshop, CVPR 2017</a>.
<br/>
<i class="fa fa-bullhorn" style="color:red;text-shadow:1px 1px 1px #000;"></i> <span style="font-weight: bold;">[May 2017]</span>  Thesis proposal accepted, and officially advanced to candidacy.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[May 2017]</span>  Joined JDE, Verisk Analytics as Cognitive Analytics and Machine Learning Research Intern, under Dr. Maneesh Singh, Director, JDE, Cognitive Analytics.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[May 2017]</span> Unofficially a Ph.D. Candidate, after successfully defending my proposal on "Knowledge and Reasoning in Image Understanding".
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[May 2017]</span> Invited as a <a href="https://ijcai-17.org/program-committee.html">review-assistant for IJCAI 2017</a>.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[March 2017]</span>   Awarded University Graduate Fellowship for Spring 2017 from ASU, for the third time.
<br/>
<i class="fas fa-star fa-xs" style="color:gold;text-shadow:2px 2px 2px #000;vertical-align: middle;"></i> <span style="font-weight: bold;">[Feb 2017]</span>  Attended AAAI-2017 (DC and the main Conference). Great to know that people are interested in Vision and Reasoning approaches. Here is the <a href="https://sites.google.com/site/somakaditya86/IJCAI_poster_vertical.pdf">poster</a> I presented at the main conference.
<br/>
</div> -->


