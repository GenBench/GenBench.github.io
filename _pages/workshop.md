---
permalink: /workshop/
title: "GenBench workshop"
toc: true
author_profile: false
layout: single_wide
toc_sticky: true
excerpt: "The first workshop on (benchmarking) generalisation in NLP"
header:
  overlay_color: "#268"
---

# Workshop description

The ability to generalise well is often mentioned as one of the primary desiderata for models of natural language processing (e.g. [Marcus, 1998](https://arxiv.org/abs/1801.00631); [Schmidhuber, 1990](); [Wong and Wang, 2007](); [Lake et al., 2017](); [Yogatama et al., 2019](); [Linzen, 2020](); [Elangovan et al., 2021](); [Marcus, 2018]())
Generalisation is crucial to ensure that models behave robustly, reliably and fairly when making predictions about data that is different from the data that they were trained on and is also important when NLP models are considered from a cognitive perspective, as models of human language.
Yet, what good generalisation entails and how it should be evaluated is not well understood, nor are there any common standards to evaluate it ([Hupkes et al., 2022](https://arxiv.org/abs/2210.03050)).
As a result, it is difficult to understand what the current state of the field is when it comes to generalisation.
It is difficult to understand how results in this area relate to each other, what sorts of generalisation are being addressed and which are neglected, which forms of generalisation testing we should prioritise in which types of scenarios, and how we can adequately assess generalisation in the first place.
Missing answers to all of those questions are standing in the way of better model development: what we cannot measure, we cannot improve.
The GenBench workshop on (benchmarking) generalisation in NLP aims to serve as a cornerstone to catalyse research on generalisation in the NLP community.
The workshop has two concrete goals:
* Establish a shared platform for sota generalisation testing in NLP, with a leaderboard for a selection of tests that are created and selected not by one group, but by a larger community.
* Bring together different expert communities to discuss challenging questions relating to generalisation in NLP.

# Programme 
Our intended workshop programme consists of five different elements: i) invited presentations ii) spotlight presentation of type 1 submissions iii) oral presentations of a selection of type 2 submissions iv) poster presentations of all submissions v) a panel on generalisation, bringing together experts from different communities.
In this panel, we will discuss topics such as how to best involve domain experts in the design of generalisation tests, the future of generalisation testing and when generalisation testing is important and when it is not.
Furthermore, we will add topics drawn from the workshop submissions, as well as questions solicited through an online poll prior to the workshop.

# Submission types

To reach out workshop goals, we welcome two different types of submissions.

## Submission type 1: Collaborative Benchmarking Task
To achieve the first goal of our workshop, we organise a collaborative benchmarking task, in similar spirits to the [BIG-Bench](https://github.com/google/BIG-bench) challenge, but focusing specifically on generalisation. 
We will invite researchers to submit challenging and diverse generalisation tests, within a relatively wide yet well-defined scope.
Submitters of splits will be asked to characterise their splits using the generalisation taxonomy presented by [Hupkes et al., 2022](https://arxiv.org/abs/2210.03050), and we specifically encourage submissions focussing on generalisation to underrepresented languages, with a fairness motivation, or any of the other challenges in generalisation research discussed by [Hupkes et al., 2022](https://arxiv.org/abs/2210.03050).
Generalisation test submissions need to be motivated and described in a paper submission, accompanied with results for selected models and an analysis of the results.
We also welcome submissions of existing generalisation datasets, which can be submitted through extended abstracts.
Accepted generalisation test submissions will be included in the proceedings of the workshop, and we will feature a top-selection, which will be included also in the GenBench 1.0 leaderboard, on the GenBench platform.
Following Big-Bench, after the workshop is finished, we aim to do a larger-scale testing with the top tests with a range of different models ([Srivastava et al., 2022]()).

## Submission type 2: generalisation and opinion papers 
Towards our second goal, we invite paper submissions on a specific set of topics related to generalisation in NLP.
More specifically, we welcome opinion papers (similar to, for instance [Linzen, 2020](); [Baroni, 2021](); [Marcus, 2018]()), meta- analyses that bring together different existing studies on generalisation (e.g. [Liu et al., 2022](); [Chaabouni et al., 2021]()), and papers that present state-of-the-art analyses of generalisation in modern NLP models (e.g. [McCoy et al., 2019](); [Lazaridou et al., 2021]()). 
We specifically encourage papers that attack one of the challenges presented in [Hupkes et al. (2022)]().

# Invited speakers

While we have to still confirm our final line-up, and availability will depend on the workshop venue, we have a confirmed interest of several exciting invited speakers and panelists.

* Anna Rogers
* Gary Marcus
* Percy Liang
* Susan Zhang

# Organisers

## Dieuwke Hupkes
Dieuwke Hupkes is a research scientist at Meta AI Research.
Before that, she did her PhD and postdoc at the University of Amsterdam.
She authored several articles directly relevant to the workshop, two of them published in a top AI journal (Journal of Artificial Intelligence), has co-organised a workshop on compositionality, neural networks, and the brain held at the Lorentz Center in the summer of 2019, and co-organised the past three editions of BlackboxNLP, some of which were organised either entirely virtually or in a hybrid fashion.
She is also the lead of the GenBench project. 

## Verna Dankers 
Verna Dankers is a PhD student at the Centre for Doctoral Training in NLP, University of Edinburgh. Her primary research interests lie at the intersection of compositional generalisation for natural language tasks and interpretability.  Three years into her PhD, she already has more than 5 publications relevant to the workshop, published in ACL conferences, workshops and the journal JAIR. She is furthermore one of the founders of the larger GenBench project, to which she has made substantial contributions, has interned at FAIR Labs, Meta AI, and has served on the program committees of ACL, EMNLP, CoNLL, the BlackboxNLP and the Figlang workshops.

## Khuyagbaatar Batsuren
Khuyagbaatar Batsuren is an Associate Professor at the National University of Mongolia. His research interest focuses on computational morphology and multilingual NLP. He got his Ph.D. at the University of Trento, where he studied a universal structure of human lexical semantics. He was part of the shared task organisers and program commitee of the SIGMORPHON 2022 Workshop. 

## Koustuv Sinha 
Koustuv Sinha is a Research Scientist at Meta AI Research (Fundamental AI Research team). He did his PhD from McGill University and Mila Quebec AI Institute. His research focuses on investigating systematicity and generalisation in natural language understanding (NLU) models, especially the state-of-the-art large language models, and develop methods to alleviate generalisation issues in production. He is the lead organizer of the annual ML Reproducibility Challenge, which has had six iterations since 2018 (2018-2022). He serves as a Journal Chair at NeurIPS 2022, and also an associate editor of ReScience, a journal promoting reproducibility reports in various fields of science. He has co-organized several workshops in the past, including NILLI (2021, 2022) at EMNLP, and ML Retrospectives at NeurIPS 2019. 

## Amirhossein Kazemnejad
Amirhossein Kazemnejad is a master's student at McGill University and Mila, where he studies the generalisation capabilities of Transformers. The work he has done has been presented at ACL conferences and workshops. As well as serving on the program committees of EMNLP and ARR, he was a member of the organizing committee for EACL 2021 and the virtual website team for EMNLP 2020. Furthermore, he has been closely involved in the development of the GenBench project.

## Christos Christodoulopoulos
Christos Christodoulopoulos is a Senior Applied Scientist at Amazon Research Cambridge, working on knowledge extraction and verification. He got his PhD at the University of Edinburgh, where he studied the underlying structure of syntactic categories across languages. Before joining Amazon, he was a postdoctoral researcher at the University of Illinois working on semantic role labeling and psycholinguistic models of language acquisition. He is part of the organising committee of the FEVER series of workshops and shared tasks, an area co-chair for NAACL 2019, ACL 2020, and the general chair for the 2021 Truth and Trust Online conference.

## Ryan Cotterell 
Ryan Cotterell is an assistant professor of computer science at ETH Zurich where he is affiliated with the Institute for Machine Learning, the AI Center, and the Media Technology Center. He primarily researches topics in natural language publishing and machine learning.

## Elia Bruni
Elia Bruni is a professor of Natural Language Processing at the University of Osnabrück. 
Previously, he was a Marie Sklodowska-Curie Fellow at the Computational Linguistics and Linguistic Theory (COLT) research group, University of Pompeu Fabra (Barcelona, Spain).
He obtained his PhD at the Language, Interaction and Computation Lab (CLIC) at the University of Trento. 
His research focuses on deep learning for natural language processing and he is particularly interested in assessing the ability of neural networks to process language compositionally. 
Elia has served on the program committees of ACL, EMNLP, CoNLL,NAACL among others. 
He was also part of the management committee of the European Network on Integrating Vision and Language.

# Anti-Harassment Policy
GenBench adheres to the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/sphp?title=Anti-Harassment_Policy).
