+++
# Date this page was created.
date = "2023-12-20"

# Project title.
title = "CS60092 Information Retrieval (Spring 2024)"

# Project summary to display on homepage.
summary = "Course Page for CS60092"

# Optional image to display on homepage (relative to `static/img/` folder).
# image_preview = "headers/taxinli2.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["deep-learning", "soft-logic"]`
# tags = ["deep-learning", "Logic", "Language", "common-sense", "Semantic Parsing", "Knowledge Acqusition"]

# Optional external URL for project (replaces project detail page).
# external_link = "https://github.com/microsoft/TaxiNLI"

# Does the project detail page use math formatting?
math = false

+++ 

<blockquote>
<table id="nobd" cellspacing="0" cellpadding="2" border="0">
<tbody><tr><td id="nobd" align="left" valign="top"><b>Instructor</b>
    </td><td id="nobd" align="left">&nbsp;&nbsp;&nbsp;
    </td><td id="nobd" align="left"><a href="http://cse.iitkgp.ac.in/~saditya/">Somak Aditya</a>
</td></tr><tr><td id="nobd" valign="top" align="left"><b>Timing (Tentative)</b>
    </td><td id="nobd" valign="top" align="left">&nbsp;&nbsp;&nbsp;
    </td><td id="nobd" valign="top" align="left"> MON (12:00-12:55) , TUE (10:00-11:55)
</td></tr><tr><td id="nobd" valign="top" align="left"><b>First Class (Tentative)</b>
    </td><td id="nobd" valign="top" align="left">&nbsp;&nbsp;&nbsp;
    </td><td id="nobd" valign="top" align="left"><span style="color:red"> January 2nd, 2023 </span>
</td></tr><tr><td id="nobd" valign="top" align="left"><b>Venue</b>
    </td><td id="nobd" valign="top" align="left">&nbsp;&nbsp;&nbsp;
    </td><td id="nobd" valign="top" align="left"> NC242, Nalanda Classroom
</td></tr><tr><td id="nobd" valign="top" align="left"><b>Teaching Assistants</b>
    </td><td id="nobd" valign="top" align="left">&nbsp;&nbsp;&nbsp;
    </td><td id="nobd" valign="top" align="left">
    Sachin Vashishtha (sachinvashistha6916@gmail.com) <br/>
    Anuj Parashar (anujparashar16012000@gmail.com) <br/>
</td></tr></tbody></table>
</blockquote>

<!--
<b>Office Hours</b> <p></p>
Friday - 18:10 - 19:10 (CSE-308)
-->

<p> </p>
<h3>Announcements</h3>
<ul style="list-style-type: square;">



<li>  <span style='color: red'>Note: for students, who are not able to register, kindly wait. I will not be able to answer your emails individually. </span> From time to time, I will approve based on CGPA and other criteria (such as total class strength cap etc.). </li>

<!-- <li> Every <b>registered</b> student should join the Google mailing list <b>ir-2023-spring@googlegroups.com</b>. All urgent announcements would be made through the group. <span style="color:red">This group is meant only for registered (and approved) students. Kindly mention your roll number and the fact that you have registered in ERP.</span></li> -->

<li> IR 2023-24 Spring will be a fully <u>research-oriented course</u>. </li>

<li> First introductory class will be on <b>January 2 (Tuesday), at 10:00 am</b>.</li> 

<li> The course requires an understanding of the foundation of algorithms and data structures, probability and statistics, and knowledge of the basics of Natural Language Processing, and Machine Learning. This will be a research-oriented course that would require students to understand several CS research papers. There will be a term project that needs to be done using Python/Java. It is advisable to take this course only if you have the necessary background.
</li>
</ul>
<p></p>

<p></p>
Weightage: Class-Performance/Quiz (8-10%), Mid-Sem and End-Sem (60%), Term Project (30-32%).
<p></p>

<h3> Topics Covered </h3>
<table class="table">
  <tr class='weekbegin active'>
    <th width="9%">Week</th>
    <th width="9%">Date</th>
    <!-- <th width="12%">Event</th> -->
    <th width="41%">Description & materials</th>
    <th width="41%">Readings & other resources</th>
  </tr>

  <tr class='weekbegin'>
    <td>Week 1</td>
    <td>Mon. 09/01 <br/> </td>
    <!-- <td>Lecture (Pandu)</td> -->
    <td><b>Introduction to the course</b><br /><br />
      <ul>
	<!-- <li> Videos: <a href="complementary_video_slides/05-01-07-IR-SemistructuredData.pptx">"Semistructured Data"</a> </li> -->
    <li>Slides:
    	     <a href="/files/IRSp24/Lec1.pdf">PDF</a> 
	</li>  
    </ul>
    </td>
    <td>
      <ul>
        <li><a href="http://nlp.stanford.edu/IR-book/pdf/01bool.pdf">IIR chapter 1</a></li>
        <li>MG section 3.2</li>
        <li>MIR section 8.2</li>
        <li><a href="http://www.rhymezone.com/shakespeare/">Shakespeare plays</a></li>
      </ul>
    </td>
  </tr>

  <tr>
    <td></td>
    <td>Tue 10/01 </td>
    <!-- <td>Lecture (Chris)</td> -->
    <td><b>Boolean Retrieval</b>: Dictionary and postings lists, boolean querying
    <!--(<a href="https://github.com/manning/MergeAlgorithms">starter code</a>)-->
    <br/><br/>
    <ul>
	<!-- <li> Videos: <a href="complementary_video_slides/05-01-07-IR-SemistructuredData.pptx">"Semistructured Data"</a> </li> -->
    <li>Slides:
    	     <a href="/files/IRSp23/Lec2.pdf">PDF</a> 
	</li>
    </td>
    <td>
    <ul>
        <li><a href="http://nlp.stanford.edu/IR-book/pdf/02voc.pdf">IIR chapter 2</a></li>
      </ul>
    </td>
  </tr>
<tr class='weekbegin'>
    <td>Week 2</td>
    <td>Mon 15/ 01 <br/> Tue 16/01</td>
    <td><b>The term vocabulary & postings lists</b><br /><br />
    <ul>
         <li>Slides:
             <a href="/files/IRSp22/Lec3.pdf">PDF</a>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="https://nlp.stanford.edu/IR-book/pdf/02voc.pdf">IIR chapter 2</a></li>
        <li><a href="http://www.sims.berkeley.edu/~hearst/irbook/porter.html">Porter's stemmer (MIR)</a></li>
        <li><a href="http://www.tartarus.org/~martin/PorterStemmer/">Porter stemming algorithm (Official)</a></li>
      </ul>
    </td>
  </tr>
   <tr class="weekbegin">
    <td>Week 3</td>
    <td>Mon. 22 / 01</td>
    <td><b>Skip Pointers, Phrase Queries and Positional Indexing</b><br /><br />
    <ul>
         <li>Slides:
             <a href="/files/IRSp24/Lec4.pdf">PDF</a>
      </ul>
    </td>
    <td><ul>
        <li><a href="https://nlp.stanford.edu/IR-book/pdf/02voc.pdf">IIR chapter 2</a></li>
        <li><a href="http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.17.524">A skip list cookbook (Pugh 1990)</a></li>
        <li><a href="http://portal.acm.org/citation.cfm?id=1028102">Fast phrase querying with combined indexes (Williams, Zobel, Bahle 2004)</a></li>
        <li><a href="http://portal.acm.org/citation.cfm?id=564415">Efficient phrase querying with an auxiliary index (Bahle, Williams, Zobel 2002)</a></li>
      </ul>
    </td>
  </tr>
   <tr class='warning'>
    <td>Week 4</td>
    <td>Tues 23 / 01 & Mon 29 / 01</td>
    <td><b>Scoring, term weighting & the vector space model</b><br /><br />
    <ul>
         <li>Slides:
             <a href="/files/IRSp24/Lec5.pdf">PDF</a>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="https://nlp.stanford.edu/IR-book/pdf/06vect.pdf">IIR chapter 6</a></li>
        <li><a href="https://www.cs.utah.edu/~jeffp/teaching/cs5140-S15/cs5140/L4-Jaccard+nGram.pdf">Jaccard Similarity and n-Grams document</a></li>
        <li><a href="https://en.wikipedia.org/wiki/Cosine_similarity#Soft_cosine_measure">Soft Cosine Measure</a></li>
        <li><a href="https://redirect.cs.umbc.edu/~nicholas/676/papers/p21-singhal.pdf">Pivoted Document Length Norm</a></li>
      </ul>
    </td>
  </tr>
  <tr class='weekbegin'>
    <td>Week 5</td>
    <td>Tue. 30/ 01 & Mon. 05 / 02</td>
    <td><b>Dictionaries and Tolerant Retieval</b><br /><br />
    <ul>
         <li>Slides:
             <a href="/files/IRSp22/Lec6.pdf">PDF</a>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="https://nlp.stanford.edu/IR-book/pdf/03dict.pdf">IIR chapter 3</a></li>
      </ul>
    </td>
  </tr>
    <tr class="warning">
    <td></td>
    <td>Tues. 06 / 02</td>
    <td><b>Evaluation</b><br /><br />
    <ul>
         <li>Slides:
             <a href="/files/IRSp24/Lec7.pdf">PDF</a>
      </ul>
    </td>
    <td>
    <ul>
        <li><a href="https://nlp.stanford.edu/IR-book/pdf/08eval.pdf">IIR chapter 8</a></li>
        <li><a href="https://towardsdatascience.com/what-is-average-precision-in-object-detection-localization-algorithms-and-how-to-calculate-it-3f330efe697b">Average Precision</a></li>
      </ul>
    </td>
  </tr>
  <tr class='weekbegin'>
    <td>Week 6</td>
    <td>Mon. 12/02</td>
    <td><b>Index Constructions</b><br /><br />
    <ul>
         <li>Slides:
             <a href="/files/IRSp22/Lec8.pdf">PDF</a>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="https://nlp.stanford.edu/IR-book/pdf/04const.pdf">IIR chapter 4</a></li>
      </ul>
    </td>
  </tr>
  <tr class='warning'>
    <td></td>
    <td>Mon. 13/02 </td>
    <td><b>Tutorial 1</b><br /><br />
    <ul>To be Updated</ul>
    </td>
    <td>
      <ul>
        <li><a href="https://nlp.stanford.edu/IR-book/exercises.html">IIR Exercises (From IIR book and Other Problem Sets)</a></li>
      </ul>
    </td>
  </tr>
  <tr class='weekbegin'>
    <td>Week 7</td>
    <td>Tue. 27/ 02</td>
    <td><b>Index Compression</b><br /><br />
    <ul>
         <li>Slides:
             <a href="/files/IRSp22/Lec9.pdf">PDF</a>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="https://nlp.stanford.edu/IR-book/pdf/05comp.pdf">IIR chapter 5</a></li>
      </ul>
    </td>
  </tr>
   <tr class="weekbegin">
    <td></td>
    <td>Mon. 4 / 03 & Tues. 5 / 03</td>
    <td><b>Relevance Feedback & Query Expansion</b><br /><br />
    <ul>
         <li>Slides:
             <a href="/files/IRSp24/Lec10.pdf">PDF</a>
      </ul>
    </td>
    <td>
    <ul>
        <li><a href="https://nlp.stanford.edu/IR-book/pdf/09expand.pdf">IIR chapter 9</a></li>
        <li><a href="https://sigir.org/files/museum/pub-08/XXIII-1.pdf">Rocchios's Feedback Paper (SIGIR 1965)</a></li>
        <li><a href="https://www.cs.cornell.edu/people/tj/publications/joachims_97a.pdf">Probabilistic Analysis of the Rocchio (Joachim '97)</a></li>
      </ul>
    </td>
  </tr>
</table>


<h3>Tentative Topics </h3>
<ul>
<li> Boolean retrieval </li>
<li> The term vocabulary & postings lists </li>
<li> Skip Pointers, Phrase Queries and Positional Indexing</li>
<li> Scoring, term weighting & the vector space model</li>
<li> Dictionaries and Tolerant Retrieval</li>
<li> Evaluation in information retrieval</li>
<li> Index Construction and Compression</li>
<li> Relevance feedback & query expansion</li>
<li> Probabilistic information retrieval</li>
<li> <b>Language models for information retrieval (Probabilistic, RNN, Transformers)</b></li>
<li> <b>Retrieval-Augmented Generation (RAG) and Large Language Models</b></li>
<li> Link analysis -- HITS, PageRank</li>
<li> Word Vectors</li>
<li> Learning to Rank</li>
</ul> 

<h3> Pre-requisites for the course </h3>
<ul>
<li> Data structures and Algorithms </li> 
<li> Probability and Statistics </li> 
<li> Basics of Machine Learning </li> 
<li> Basics of Natural Language Processing (Some might be covered during the course) </li> 
<li> Basics of Graph algorithms (Some might be covered during the course) </li> 
<li> Programming in Python/Java </b> </li> 
</ul>

<h3> Reference Literature, Useful Tools and Software Resources </h3>
<ol>
  <li> <a href="https://nlp.stanford.edu/IR-book/information-retrieval-book.html">Manning, Christopher D., Prabhakar Raghavan, and Hinrich Schütze. <em>Introduction to information retrieval</em>, Cambridge: Cambridge university press, 2008.</a></li>
  <li> Research Papers shared in class. </li>
  <li> Pranav Rajpurkar's <a href="https://docs.google.com/document/d/1uvAbEhbgS_M-uDMTzmOWRlYxqCkogKRXdbKYYT98ooc/edit#">Harvard CS197 AI Research Experiences</a></li>
</ol>

<span style="color:red"> Every test should be attempted individually by each student. Plagiarism in any form will be severely penalized.</span>