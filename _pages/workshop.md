---
permalink: /workshop/
title: "GenBench Workshop 2024"
toc: true
author_profile: false
layout: single_wide
toc_sticky: true
excerpt: "The second workshop on generalisation (benchmarking) in NLP"
header:
  overlay_color: "#268"
---

# News
- EMNLP week is here! You will find our programme here: [https://genbench.org/workshop_programme](https://genbench.org/workshop_programme).
- Would you like to present your EMNLP 2024 Findings paper at the GenBench workshop? Email us, and we'll see whether it's a match!
- We extended the submission deadline for scholarships, papers & CBT submissions: submit by August 18, AoE!
- Thanks to our workshop sponsor Amazon, we'll be giving out a best paper award, and have travel scholarships available for students! Apply for the scholarships now: [https://genbench.org/workshop/#scholarships](https://genbench.org/workshop/#scholarships).
- Our [call for papers](../cfp2024.txt) is online!
- Delighted to announce the GenBench 2024 Workshop will come back @ EMNLP 2024

# Venue

The Second GenBench workshop will be held at [EMNLP 2024](https://2024.emnlp.org/) in Miami, Florida on November 16.

# Important dates (Tentative)

- **August 18, 2024** – Paper submission deadline
- **September 20, 2024** - Notification deadline
- **October 4, 2024** – Camera-ready deadline (you can use up to 9 pages for your camera-ready paper!)
- **November 16, 2024** – Workshop

*Note: all deadlines are 11:59PM UTC-12:00. We will accept ARR submissions; corresponding deadlines will be announced at a later moment in time.*


# Workshop description

The ability to generalise well is often mentioned as one of the primary desiderata for models of natural language processing (NLP).
Yet, there are still many open questions related to what it means for an NLP model to generalise well, and how generalisation should be evaluated.
LLMs, trained on gigantic training corpora that are – at best – hard to analyse or not publicly available at all, bring a new set of challenges to the topic.
The second GenBench workshop aims to serve as a cornerstone to catalyse research on generalisation in the NLP community.
The workshop has two concrete goals:
* Bring together different expert communities to discuss challenging questions relating to generalisation in NLP;
* Establish a shared platform for state-of-the-art generalisation testing in NLP. We started this last year, and this year's collaborative benchmarking task (CBT) is solely LLM-focused!

# Submissions

We call for two types of submissions: regular workshop submissions and CBT submissions.

## Submission type 1: generalisation and opinion papers

Regular workshop submissions present papers on the topic of generalisation. 
Topics of interest include, but are not limited to:
- Opinion or position papers about generalisation and how it should be evaluated;
- Analyses of how existing or new models generalise;
- Empirical studies that propose new paradigms to evaluate generalisation;
- Meta-analyses that compare how results from different generalisation studies compare;
- Meta-analyses that study how different types of generalisation are related;
- Papers that discuss how generalisation of LLMs can be evaluated;
- Papers that discuss why generalisation is (not) important in the era of LLMs;
- Studies on the relationship between generalisation and fairness or robustness.

If you are unsure whether a specific topic is suitable, feel free to contact the workshop organizers at [genbench@googlegroups.com](mailto:genbench@googlegroups.com).

## Submission type 2: the Collaborative Benchmarking Task

The goal of this year's CBT is to generate versions of existing evaluation datasets for LLMs with a larger distribution shift than the original test set, given a particular training corpus.
We focus on three training corpora: C4, RedPajama-Data-1T, and Dolma, and three evaluation datasets: MMLU, HumanEval, and SiQA.
All three corpora are publicly available, and they can be searched via the [What's in My Big Data API](https://github.com/allenai/wimbd).

To submit to the CBT, design a method to measure distribution shift for one or more of these evaluation datasets, and generate one or more versions of the dataset that have a larger distribution shift according to this method. 
Newly generated sets should have at least 200 examples.

Practically speaking, CBT submissions consist of:
1. the data/task artefact (submitted through [https://github.com/GenBench/genbench_cbt](https://github.com/GenBench/genbench_cbt))
2. a paper describing the dataset and its method of construction (submitted through [https://openreview.net/group?id=GenBench.org/2024/Workshop](https://openreview.net/group?id=GenBench.org/2024/Workshop))

More detailed guidelines are provided here: [https://genbench.org/cbt](https://genbench.org/cbt).

## Archival vs extended abstract
Both types of submission can be archival papers or extended abstracts.
Archival papers are up to 8 pages excluding references and report on completed, original and unpublished research. They follow the requirements of regular EMNLP 2024 submissions. Accepted papers will be published in the workshop proceedings and are expected to be presented at the workshop. The papers will undergo double-blind peer review and should thus be anonymised. Extended abstracts can be up to 2 pages excluding references, and may report on work in progress or be cross-submissions of work that has already appeared in another venue. Abstract titles will be posted on the workshop website, but will not be included in the proceedings.

## Submission instructions
For both archival papers and extended abstracts, we refer to the EMNLP 2024 website for paper templates and requirements. Additional requirements for both regular workshop papers and collaborative benchmarking task submissions can be found on our website. 

All submissions can be submitted through OpenReview: [https://openreview.net/group?id=GenBench.org/2024/Workshop](https://openreview.net/group?id=GenBench.org/2024/Workshop).

## Preprints
We do not have an anonymity deadline, preprints are allowed, both before the submission deadline as well as after.

# Sponsors
We would like to thank Amazon for sponsoring our workshop. 

![Amazon Sponsor](/img/sponsor/amazon_logo_RGB.png){:width="400px"}

## Scholarships
With the support of our workshop sponsor Amazon, we are offering 5 scholarships, each covering up to $750 of travel expenses and/or (virtual) registration fees.
We strongly encourage students from developing countries and marginalized communities to apply.
To submit your application, please send us an email with the following information (the deadline is *August 18*):
- your CV
- A few motivational sentences: why do you want to attend the workshop, and how would the funds help you with that?

# Contact
You can reach out to us via the following email address: [genbench@googlegroups.com](mailto:genbench@googlegroups.com)

The GenBench-2024 workshop is organised by:
- <b>Dieuwke Hupkes</b>: a research scientist at Meta. Her primary research interest is better understanding models for NLP and how that relates to (linguistic, philosophical) knowledge about language; lately she has focussed specifically on LLM evaluation.
- <b>Verna Dankers</b>: a PhD student at the Centre for Doctoral Training in NLP, University of Edinburgh. Her primary research interests lie at the intersection of compositional generalisation for natural language tasks and interpretability.  
- <b>Khuyagbaatar Batsuren</b>: a research scientist at Openstream.ai. His research focuses on multi-agent collaboration, planning, agentic AI, and subword tokenization.
- <b>Amirhossein Kazemnejad</b>: a master's student at McGill University and Mila, where he studies the generalisation capabilities of Transformers.
- <b>Christos Christodoulopoulos</b>: a Senior Applied Scientist at Amazon Research Cambridge, working on knowledge extraction and verification.
- <b>Mario Giulianelli</b>: a postdoctoral fellow at ETH Zürich, he studies information processing in humans and computational models of language. His current focus areas include language model evaluation and analysis, computational psycholinguistics, semantic variation and change.
- <b>Ryan Cotterell</b>: an assistant professor of computer science at ETH Zürich where he is affiliated with the Institute for Machine Learning, the AI Center, and the Media Technology Center. He primarily researches topics in natural language processing and machine learning.

# Program Committee
Sachin Agarwal, Apple <br>
Parsa Bagherzadeh, McGill University<br>
Marco Basaldella, Amazon<br>
Jonathan Brophy, University of Oregon<br>
Lisa Bylinina, Utrecht University<br>
Gautier Dagan, University of Edinburgh<br>
Erenay Dayanik, Amazon<br>
Subham De, Meta AI<br>
Bryan Eikema, University of Amsterdam<br>
Jean-Philippe Fauconnier, Apple<br>
Antske Fokkens, VU University Amsterdam<br>
Robert Frank, Yale University<br>
Richard Futrell, University of California, Irvine<br>
Michael Eric Goodale, Ecole Normale Supérieure de Paris<br>
Deepanshu Gupta, Apple<br>
Coleman Haley, University of Edinburgh<br>
Cassandra L Jacobs, State University of New York, Buffalo<br>
Yangfeng Ji, University of Virginia<br>
Bogdan Kulynych, CHUV - University Hospital Lausanne<br>
Jenny Kunz, Linköping University<br>
Matthias Lindemann, University of Edinburgh<br>
R. Thomas McCoy, Yale University<br>
Kate McCurdy, Universität des Saarlandes<br>
Houman Mehrafarin, Heriot-Watt University<br>
Koji Mineshima, Keio University<br>
Mira Moukheiber, Massachusetts Institute of Technology<br>
Anmol Nayak, Bosch<br>
Swetasudha Panda, Oracle<br>
Lis Pereira, National Institute of Information and Communications Technology (NICT)<br>
Jirui Qi, University of Groningen<br>
Rudolf Rosa, Charles University<br>
Rimvydas Rubavicius, Edinburgh University<br>
Djamé Seddah, Inria Paris (on teaching leave from Sorbonne Université)<br>
Tatiana Shavrina, Artificial Intelligence Research Institute<br>
Sanchit Sinha, University of Virginia<br>
Shane Steinert-Threlkeld, University of Washington<br>
Aditya Kaushik Surikuchi, University of Amsterdam<br>
Jithendra Vepa, Idiap Research Institute<br>
Fabio Massimo Zanzotto, University of Rome Tor Vergata<br>
Churan Zhi, University of California, San Diego<br>
Michal Štefánik, Masaryk University<br>


# Anti-Harassment Policy
GenBench adheres to the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/sphp?title=Anti-Harassment_Policy).

<script type="text/javascript">
var links = document.links;
for (var i = 0, linksLength = links.length; i < linksLength; i++)
	if (links[i].hostname != window.location.hostname)
	    links[i].target = '_blank';
</script>
