---
permalink: /cbt/
title: "Collaborative benchmarking task (CBT)"
layout: single_wide

excerpt: "Submit to the GenBench Collaborative Benchmarking Task"
header:
  <!-- overlay_image: /assets/images/unsplash-image-1.jpg -->
  overlay_color: "#268"
---

The Genbench Collaborative Benchmarking Task (CBT) aims to develop a collaborative generalisation benchmark for NLP, hosted on a shared platform: GenBench.
Submissions to the CBT consist of a data/task artefact (submitted via the [GenBenchCBT github repository](https://github.com/GenBench/genbench_cbt)) and a paper (submitted via openreview), describing the submission. 
The paper will be reviewed via a regular paper review pipeline and included in the proceedings of the GenBench workshop. 
Tasks corresponding to accepted papers will be merged into the GenBench repository.
After the workshop, we will release a leaderboard for the top-reviewed tasks.
More details about both task and paper submissions can be found below.


## Important dates
- August 1, 2023 – Sample data submission deadline
- September 1, 2023 – Paper submission deadline
- September 15, 2023 – ARR submission deadline
- October 6, 2023 – Notification deadline
- October 18, 2023 – Camera ready deadline
- December 6/7, 2023 – Workshop

## Submit a task to the collaborative benchmark

As described above, CBT submissions consist of a data/task artefact and an accompanying paper.
The data/task artefacts are submitted via a pull request on the [GenBenchCBT github repository](https://github.com/GenBench/genbench_cbt), whereas the papers are submitted via openreview.

### Task / data submissions & sample submissions

To submit your data/task, head over to the [GenBenchCBT github repository](https://github.com/GenBench/genbench_cbt) and follow the instructions in the README to create your submission files. 
Before making your official submission, you will need to send a sample submission for validation by the GenBench team via a Pull Request to the repository.
The sample submission must include a minimal working version of your intended submission -- a `config.jsonnet` and (optionally) `task.py` file, and a small sample of the data -- and a minimal description of the task in the `doc.md` file. 

### CBT papers

CBT submissions to the Genbench CBT github repository should be accompanied by (anonymous) papers, that can be submitted via the paper submission page of the GenBench workshop.
In the submission form, please indicate that your paper describes a CBT submission, and add the number of your PR in the github repository.
The paper should motivate the development of your proposed task or test, describe the method you used to create the data, present an evaluation of some models of your choosing and contain a [GenBench evaluation card](https://genbench.org/eval_cards/) describing its values on the GenBench generalisation taxonomy.
You can submit both an archival paper or an extended abstract.
Reviewers will be instructed to assess your submission similarly to regular paper submissions, and acceptance of your task is based on the paper, provided that your artefact technically fits within the framework.
Tasks from accepted papers will be merged into the GenBench repository, and the paper will be included in the proceedings of the GenBench workshop. 
After the workshop, we will release a leaderboard for the top-reviewed tasks. For more details about the paper submission, we refer the reader to [genbench.org/workshop](https://genbench.org/workshop).

## FAQ
#### What is generalisation?
The answer to the question "what is generalisation" likely differs per person. In the CBT, we therefore do not maintain a strict definition, other than that what is evaluated should go beyond purely i.i.d. or random testing. It is up to the submitter to convince the reviewers that their submission targets generalisation and describe why and how it does so. If you are in doubt, feel free to reach out to the workshop organisers.

#### Why do I need to do a sample submission, and why is there an early deadline for that?
To make sure we can assess all CBT submissions in time, we ask that submitters send in a sample submission at least one month before the paper submission deadline. We will check whether the submission technically makes sense and provide some feedback if needed. The sample submission does not need to contain your complete submission, but should contain a working version of the functions you intend to overwrite, and contain at least a few samples to ensure that saliency checking is possible.

#### I have a published paper about a dataset that I would like to have on the platform, can I submit it?
Yes you can! We very much encourage submissions of existing generalisation evaluations, which can be submitted along with an extended abstract.

#### How can I evaluate generalisation for an LLM if I don't know anything about the training data?
Excellent question! We have no clear answer to this, but we hope that some of you will come up with creative solutions to do so!

#### I have an evaluation task that doesn't fit the existing protocols, can I propose a change?
Yes, reach out to us at genbench@googlegroups.com. 
We welcome proposals that extend our current implementation, but we cannot guarantee that we will implement any fixes or changes in time for the workshop.

#### Are there any minimal requirements for CBT papers?
Other than the inclusion of a [GenBench evaluation card](https://genbench.org/eval_cards/), there are no strict requirements for CBT papers.
