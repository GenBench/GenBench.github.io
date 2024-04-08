---
permalink: /workshop/
title: "GenBench Workshop 2024"
toc: true
author_profile: false
layout: single_wide
toc_sticky: true
excerpt: "The second workshop on (benchmarking) generalisation in NLP"
header:
  overlay_color: "#268"
---

# News
<!-- - The GenBench proceedings can be [found online](https://aclanthology.org/2023.genbench-1.0/), the slides of the invited speakers can be found on the [workshop programme page](https://genbench.org/workshop_programme/) stay tuned for the videos!
- GenBench workshop 1 is a wrap, but good news: we'll be back next year at EMNLP!
- The programme is online, and the papers for the poster sessions will soon be announced: [https://genbench.org/workshop_programme](https://genbench.org/workshop_programme)
- Deadline now passed ~~The camera-ready deadline is coming up: October 26. You can use 1 extra page (max. 9) to integrate the reviewers' comments.~~
- Closed: ~~We are accepting EMNLP Findings papers with a good fit, please reach out via email (genbench@googlegroups.com) for instructions.~~
- After technical difficulties with the ARR submission, we extended the submission deadline to October 11! Submissions can now be made via [this Openreview page](https://openreview.net/group?id=GenBench.org/2023/ARR_Commitment).
- Would you like to submit to the Collaborative Benchmark Task, but you missed the August 1 sample deadline? Get in contact with us, you can still submit to the September 1 deadline!
- The [CoNLL conference](https://conll.org/2023) now allows dual submissions with GenBench, and vice versa! Is your CoNLL submission a good fit with the GenBench mission but are you still waiting for your reviews? Also submit to GenBench! See our information about [dual submissions](https://genbench.org/workshop/#dual-submissions).
- The Collaborative Benchmarking Task is now accepting submissions, see [genbench.org/cbt](https://genbench.org/cbt)!
- Exciting news: thanks to our sponsor Amazon, we can now offer [scholarships](https://genbench.org/workshop/#scholarships)! -->
- Our [call for papers](../cfp.txt) is online! 

# Best paper and data awards

We granted both a best paper and best data data award.

- **Best paper**: Andor Diera, Abdelhalim Dahou, Lukas Galke, Fabian Karl, Florian Sihler, Ansgar Scherp. *GenCodeSearchNet: A benchmark test suite for evaluating generalization in programming language understanding.*
- **Best data**: Jirui Qi, Raquel Fernández, Arianna Bisazza. *Cross-lingual consistency of factual knowledge in multilingual language models*

# Venue

The First GenBench workshop was be held at [EMNLP 2023](https://2023.emnlp.org/) in Singapore on December 6.

# Important dates

- ~~**August 1, 2023** – Sample data submission deadline~~
- ~~**September 1, 2023** – Paper submission deadline, submission link: [https://openreview.net/group?id=GenBench.org/2023/Workshop](https://openreview.net/group?id=GenBench.org/2023/Workshop)~~
- ~~**September 15, 2023**~~ extended to **October 11, 2023** – ARR commitment deadline, submission link: [https://openreview.net/group?id=GenBench.org/2023/ARR_Commitment](https://openreview.net/group?id=GenBench.org/2023/ARR_Commitment)
- ~~**October 6, 2023** extended to **October 11, 2023** – Notification deadline for direct submissions~~
- ~~**October 13, 2023** - Notification deadline for ARR submissions~~
- ~~**October 26, 2023** – Camera-ready deadline (you can use up to 9 pages for your camera-ready paper!)~~
- **December 6, 2023** – Workshop

*Note: all deadlines are 11:59PM UTC-12:00*


# Workshop description

The ability to generalise well is often mentioned as one of the primary desiderata for models of natural language processing (e.g. [Marcus, 1998](https://arxiv.org/abs/1801.00631); [Schmidhuber, 1990](https://www.semanticscholar.org/paper/Towards-Compositional-Learning-in-Dynamic-Report-Schmidhuber/550e406b84e46cf8c77baa70a61704e93fd963bc); [Wong and Wang, 2007](https://ieeexplore.ieee.org/abstract/document/4227538); [Lake et al., 2017](https://www.cambridge.org/core/journals/behavioral-and-brain-sciences/article/building-machines-that-learn-and-think-like-people/A9535B1D745A0377E16C590E14B94993); [Yogatama et al., 2019](https://arxiv.org/abs/1901.11373); [Linzen, 2020](https://aclanthology.org/2020.acl-main.465/); [Elangovan et al., 2021](https://aclanthology.org/2021.eacl-main.113/); [Marcus, 2018](https://arxiv.org/pdf/1801.00631.pdf?u)).
Generalisation is crucial to ensure that models behave robustly, reliably and fairly when making predictions about data that is different from the data that they were trained on and is also important when NLP models are considered from a cognitive perspective, as models of human language.
Yet, what good generalisation entails and how it should be evaluated is not well understood, nor are there any common standards to evaluate it ([Hupkes et al., 2022](https://arxiv.org/abs/2210.03050)).
As a result, it is difficult to understand what the current state of the field is when it comes to generalisation.
It is difficult to understand how results in this area relate to each other, what sorts of generalisation are being addressed and which are neglected, which forms of generalisation testing we should prioritise in which types of scenarios, and how we can adequately assess generalisation in the first place.
Missing answers to all of those questions are standing in the way of better model development: what we cannot measure, we cannot improve.
The GenBench workshop on (benchmarking) generalisation in NLP aims to serve as a cornerstone to catalyse research on generalisation in the NLP community.
The workshop has two concrete goals:
* Bring together different expert communities to discuss challenging questions relating to generalisation in NLP.
* Establish a shared platform for state-of-the-art generalisation testing in NLP, with a leaderboard for a selection of tests that are created and selected not by one group, but by a larger community.

# Call for papers

To reach out workshop goals, we welcome two different types of submissions: regular workshop submissions and collaborative benchmarking task submissions. 
The latter will consist of a data/task artefact and a companion paper motivating and evaluating the submission. 
In both cases, we accept archival papers and extended abstracts. 

<!-- Closed: ~~We accept all papers from the Findings of EMNLP related to our topics of interest below. Contact us via genbench@googlegroups.com if you would like to present your EMNLP Findings paper at GenBench 2023!~~ -->

## Submission types

### Submission type 1: generalisation and opinion papers 
Towards our first goal, we invite paper submissions on a topics related to generalisation in NLP.
Such submissions present work on the topic of generalisation (see examples listed below), but are not intended to be included on the GenBench evaluation platform. Regular workshop papers may be submitted as an archival paper, when they report on completed, original and unpublished research; or as a shorter extended abstract. More details on this category can be found below.

Topics of interest include, but are not limited to:
- Opinion or position papers about generalisation and how it should be evaluated;
- Analyses of how existing or new models generalise;
- Empirical studies that propose new paradigms to evaluate generalisation;
- Meta analyses that compare how results from different generalisation studies compare;
- Meta analyses that study how different types of generalisation are related;
- Papers that discuss how generalisation of LLMs can be evaluated without access to training data;
- Papers that discuss why generalisation is (not) important in the era of LLMs.
- Studies on the relationship between generalisation and fairness or robustness;

If you are unsure whether a specific topic is well-suited for submission, feel free to reach out to the organisers of the workshop at genbench@googlegroups.com.
### Submission type 2: Collaborative Benchmarking Task (CBT) submissions
To achieve the second goal of our workshop, we organise a collaborative benchmarking task (CBT), in similar spirits to the [BIG-Bench](https://github.com/google/BIG-bench) challenge, but focusing specifically on non-i.i.d. generalisation. 
We invite researchers to submit challenging and diverse generalisation tests to the GenBench CBT.

Collaborative benchmarking task submissions consist of a data/task artefact and a paper describing and motivating the submission and showcasing it on a select number of models.
We accept submissions that introduce new datasets, resplits of existing datasets along particular dimensions, or in-context learning tasks, with the goal of measuring generalisation of NLP models. 
We especially encourage papers that attack one of the challenges presented in [Hupkes et al. (2022)](https://arxiv.org/abs/2210.03050):
- Generalisation in LLMs, where we have no control over the training data
- Generalisation in the context of fairness and inclusivity
- Multilingual generalisation

Each submission should contain information about the data (URIs, format, preprocessing), model preparation (finetuning loss, ICL prompt templates), and evaluation metrics. 
These will be defined either in a configuration file or in code. 
More details about the collaborative benchmark submissions and example submissions can be found on [genbench.org/cbt](https://genbench.org/cbt) as well as the [cbt submission page](https://github.com/GenBench/genbench_cbt).

Participants proposing previously unpublished datasets or splits may choose to submit an archival paper or an extended abstract. Generalisation evaluation datasets that have already been published elsewhere (or will be published at EMNLP 2023) can be submitted to the platform, as well, but only through an extended abstract, citing the original publication. We allow dual submissions with EMNLP, for more information, see below.

If you are in doubt whether a particular type of dataset is suitable for submission, please consult the information page on our website, or reach out to the organisers of the workshop at genbench@googlegroups.com.

All accepted generalisation test submissions will be included in the proceedings of the workshop, and we will feature a top-selection, which will be included also in the GenBench 1.0 leaderboard, on the GenBench platform.
Following Big-Bench, after the workshop is finished, we aim to do a larger-scale testing with the top tests with a range of different models ([Srivastava et al., 2022](https://arxiv.org/abs/2206.04615)).

## Archival vs extended abstract
Archival papers are up to 8 pages excluding references and report on completed, original and unpublished research. They follow the requirements of regular EMNLP 2023 submissions. Accepted papers will be published in the workshop proceedings and are expected to be presented at the workshop. The papers will undergo double-blind peer-review and should thus be anonymised. Extended abstracts can be up to 2 pages excluding references, and may report on work in progress or be cross submissions of work that has already appeared in another venue. Abstract titles will be posted on the workshop website, but will not be included in the proceedings.

## Submission instructions
For both archival papers and extended abstracts, we refer to the EMNLP 2023 website for [paper templates](https://2024.emnlp.org/calls/main_conference_papers/#paper-submission-details). 
Collaborative benchmarking tasks should be submitted on the [cbt submission page](https://github.com/GenBench/genbench_cbt), an accompanying paper should be submitted through OpenReview.
Regular workshop papers are submitted through OpenReview.

<!-- ~~Submission link: [https://openreview.net/group?id=GenBench.org/2023/Workshop](https://openreview.net/group?id=GenBench.org/2023/Workshop)~~ Submissions are now closed, except for ARR commitment submissions. Submit via [https://openreview.net/group?id=GenBench.org/2023/ARR_Commitment](https://openreview.net/group?id=GenBench.org/2023/ARR_Commitment) by October 1st. -->

## Dual submissions
We allow dual submissions with both EMNLP and CoNLL, and we encourage relevant papers that were dual-submitted and accepted at EMNLP to redirect to a non-archival extended abstract submission. We furthermore welcome submissions of extended abstracts that describe work already presented at an earlier venue, both in the collaborative benchmarking and in the regular submission tracks.

## Preprints
We do not have an anonymity deadline, preprints are allowed, both before the submission deadline as well as after.

# Programme 
Our intended workshop programme consists of different elements:
- invited presentations
- spotlight presentation of type 1 submissions
- oral presentations of a selection of type 2 submissions 
- poster presentations of all submissions 
- a panel on generalisation, bringing together experts from different communities

In the panel, we will discuss topics such as how to best involve domain experts in the design of generalisation tests, the future of generalisation testing and when generalisation testing is important and when it is not.
Furthermore, we will add topics drawn from the workshop submissions, as well as questions solicited through an online poll prior to the workshop.

<!-- The timetable can now be found here: [https://genbench.org/workshop_programme](https://genbench.org/workshop_programme) -->

<!-- # Invited speakers

<b>Adina Williams</b>

![Adina Williams Speaker](/img/speakers/adina.jpg){:width="300px"}

Adina is a Research Scientist at Meta on the Fundamental AI Research (FAIR) team in NYC. Her research spans several topics in NLP and computational linguistics, with a focus on dataset creation and model evaluation for humanlikeness, fairness, generalization and robustness.

<b>Tatsunori Hashimoto</b>

![Tatsunori Hashimoto Speaker](/img/speakers/thashim.jpg){:width="300px"}

Tatsunori Hashimoto is an Assistant Professor in the Computer Science Department at Stanford University. He is a member of the statistical machine learning and natural language processing groups at Stanford, and his research uses tools from statistics to make machine learning systems more robust and trustworthy — especially in complex systems such as large language models. He is a Kavli fellow, a Sony and Amazon research award winner, and his work has been recognized with best paper awards at ICML and CHI. Before becoming an Assistant Professor, he was a postdoctoral researcher at Stanford with Percy Liang and John Duchi and received his Ph.D. from MIT under the supervision of Tommi Jaakkola and David Gifford.

<b>Anna Rogers</b>

![Anna Rogers Speaker](/img/speakers/anna.jpg){:width="300px"}

Dr. Anna Rogers is an assistant professor at IT University of Copenhagen working on analysis, interpretability, and evaluation of NLP models, their societal impact, and NLP research methodology.

# Sponsors
We would like to thank Amazon for sponsoring our workshop. 

![Amazon Sponsor](/img/sponsor/amazon_logo_RGB.png){:width="400px"}

## Scholarships
With the support of our workshop sponsor Amazon, we are offering 6 scholarships, each covering up to $500 of travel expenses and/or (virtual) registration fees.
We strongly encourage students from developing countries and marginalized communities to apply.
To submit your application, please send us an email (genbench@googlegroups.com) with the following information (the deadline is *September 1*):
- your CV
- A few motivational sentences: why do you want to attend the workshop, and how would the funds help you with that? -->

# Organisers

<b>Dieuwke Hupkes</b> is a research scientist at FAIR. Her primary research interest is better understanding models for NLP and how that relates to (linguistic, philosophical) knowledge about language. 

<b>Verna Dankers</b> is a PhD student at the Centre for Doctoral Training in NLP, University of Edinburgh. Her primary research interests lie at the intersection of compositional generalisation for natural language tasks and interpretability.  

<b>Khuyagbaatar Batsuren</b> is an Associate Professor at the National University of Mongolia. His research interest focuses on computational morphology and multilingual NLP. 

<!-- <b>Koustuv Sinha</b> is a Research Scientist at Meta AI Research (Fundamental AI Research team). His research focuses on investigating systematicity and generalisation in natural language understanding (NLU) models, especially the state-of-the-art large language models, and developing methods to alleviate generalisation issues in production.  -->

<b>Amirhossein Kazemnejad</b> is a master's student at McGill University and Mila, where he studies the generalisation capabilities of Transformers.

<b>Christos Christodoulopoulos</b> is a Senior Applied Scientist at Amazon Research Cambridge, working on knowledge extraction and verification.

<b>Ryan Cotterell</b> is an assistant professor of computer science at ETH Zurich where he is affiliated with the Institute for Machine Learning, the AI Center, and the Media Technology Center. He primarily researches topics in natural language publishing and machine learning.

<!-- <b>Elia Bruni</b> is a professor of Natural Language Processing at the University of Osnabrück. 
His research focuses on deep learning for natural language processing and he is particularly interested in assessing the ability of neural networks to process language compositionally. 
 -->
 
# Program Committee

Lisa Beinborn, Vrije Universiteit Amsterdam <br/>
Jonathan Brophy, University of Oregon <br/>
Lisa Bylinina, University of Groningen<br/> 
Benoit Crabbé, Université de Paris<br/>
Ghazi Felhi, University Paris 13<br/>
Robert Frank, Yale University<br/>
Mario Giulianelli, University of Amsterdam<br/>
Yangfeng Ji, University of Virginia<br/>
Robin Jia, University of Southern California<br/>
Richard Johansson, Chalmers University<br/>
Jenny Kunz, Linköping University<br/>
Carolin Lawrence, NEC Laboratories Europe<br/>
Alessandro Lenci, University of Pisa<br/>
Sheng Liang, Ludwig-Maximilians-Universität München<br/>
Tomasz Limisiewicz, Charles University Prague<br/>
Matthias Lindemann, University of Edinburgh<br/>
R. Thomas McCoy, Princeton University<br/>
William Merrill, New York University<br/>
Anmol Nayak, Bosch<br/>
Joakim Nivre, Uppsala University<br/>
Maria Ryskina, Massachusetts Institute of Technology<br/>
Niladri S. Chatterji, Stanford University<br/>
Hendrik Schuff, Technische Universität Darmstadt<br/>
Rico Sennrich, University of Zurich<br/>
Mattia Setzu, University of Pisa<br/>
Sanchit Sinha, University of Virginia<br/>
Shane Steinert-Threlkeld, University of Washington<br/>
Aarne Talman, Basement AI<br/>
Oskar van der Wal, University of Amsterdam<br/>
Alex Warstadt, New York University<br/>
Hao Yang, Beijing University of Post and Telecommunication<br/>
Naoki Yoshinaga, the University of Tokyo<br/>
Dylan Z Slack, University of California, Irvine<br/>
Sheng Zhang, Amazon<br/>
Yichu Zhou, Yahoo<br/>

# Anti-Harassment Policy
GenBench adheres to the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/sphp?title=Anti-Harassment_Policy).

<script type="text/javascript">
var links = document.links;
for (var i = 0, linksLength = links.length; i < linksLength; i++)
	if (links[i].hostname != window.location.hostname)
	    links[i].target = '_blank';
</script>
