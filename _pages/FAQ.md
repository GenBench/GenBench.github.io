---
permalink: /FAQ/
title: "Frequently Asked Annotation Questions"
layout: single_wide
toc: true
toc_sticky: true

header:
  <!-- overlay_image: /assets/images/unsplash-image-1.jpg -->
  overlay_color: "#268"
---

On this page, we record frequently asked questions that come up when characterising papers with our taxonomy.
If you have a question that is not on this page, please reach out to us (you can email us at <a href="mailto:genbench@googlegroups.com">genbench@googlegroups.com</a>).

## Questions about the motivation

**Should I submit a paper two times if I think it has two motivations?**

_No.
It is not always to find the main motivation of a study, but we nevertheless register only one motivation per experiment.
An exception to this might be if a paper contains multiple experiments, with different motivations (we have not encountered that ourselves; it is probably rare)._


## Questions about the generalisation type

**What if a paper is unclear about its generalisation type?**
_Unfortunately, papers are not always clear about what exactly they are aiming to evaluate.
If you are unsure if the paper fits into the six categories we have defined, please reach out!
You can email us at <a href="mailto:genbench@googlegroups.com">genbench@googlegroups.com</a>._

## Questions about the shift type

**Does using masked language modeling as the pretraining objective imply that there is a covariate shift from pretraining to finetuning, given that all pretraining inputs contain special masked tokens and finetuning inputs do not?**
_Strictly speaking, this indeed constitutes a covariate shift, but we do not mark it as such in our taxonomy.
In our taxonomy, we aim to make distinctions that are useful for categorise different types of generalisation studies.
Marking every study that uses a masked language modelling objective as a covariate shift would not allow us to distinguish cases in which the training data of the model is distributionally different from the finetuning data from the cases in which it is not.
Therefore, in this case, we consider that pretraining phase consisted of learning to represent the input sentences, and we focus on whether those sentences were different in finetuning, rather than on whether the objective was different._

**Isn't there always a covariate shift between pretraining and finetuning? The opposite would imply that random samples from the pretraining corpus would be indistinguishable from those from the downstream task. Even if there is data leakage this will never be the case in practice, as the leaked data will be mixed with other content in the pretraining corpus and their distribution will therefore not be strictly the same.**
_There probably is.
In our taxonomy, we aim to make distinctions that are useful to categorise different types of generalisation studies.
Considering every pretrain-finetune a covariate shift would go against that philosohpy, and would prevent us from distinguishing more interesting cases, where there are deliberate differences between the pretraining and finetuning data._

**If no new parameters are added for finetuning, does that imply that there is no label shift? How should we annotate T5 and similar approaches?**
_When task-specific parameters are added during finetuning, they are virtually always learning new labels, which is why we mark this as a label shift in our taxonomy.
If there are no new parameters, there might still be a label shift, but establishing this requires some more explicit checking (to ensure, e.g. that questions in task form did not occur in the pretraining corpus)._

## Questions about the data source

**If an author preprocesses their corpus, can I still mark it a natural occurring corpus?**
_Yes.
Very often, author apply some preprocessing steps on their training or testing corpora, for instance to remove samples that are incorrect or noisy, or to create a corpus that is computationally feasible for them to process.
Unless the preprocessing is related to the generalisation experiment (e.g., the authors remove all sentences with a negation), we still consider these naturally occurring corpora._

## Questions about the shift locus

**When a pretrained language model is evaluated on language modeling itself, is the locus pretrain-test or train-test?**
_When the evaluation task is the same as the pretraining task, we say that the locus is train-test._

## Other questions

**What if a paper has multiple experiments that have different values on the axes?**
_If there are multiple experiments that have different values on the axes (e.g. one experiment with natural data, and one with generated data), you can submit the entry twice.
Make sure to indicate in your submission which experiments in the paper your submission is describing!_

**Why do you also ask to annotate the task that the paper is looking at?**
_The tasks that generalisation studies are considering are an interesting piece of meta-information, that we would like to track over time._

**Should I submit a paper two times if there are multiple tasks?**
_No, you can add all the tasks in the form, you do not need to submit multiple forms._
