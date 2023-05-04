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
Submissions to the CBT consist of a data/task artefact (submitted via the [GenBenchCBT github repository](https://github.com/GenBench/genbench_cbt)) and a paper (submitted via openreview), describing the submission. Tasks will be reviewed via their paper submission, accepted papers tasks will be merged into the GenBench repository, and included in the proceedings of the GenBench workshop. After the workshop, we will release a leaderboard for the top-reviewed tasks.

## Important dates
- August 1, 2023 – Sample data submission deadline
- September 1, 2023 – Paper submission deadline
- September 15, 2023 – ARR submission deadline
- October 6, 2023 – Notification deadline
- October 18, 2023 – Camera ready deadline
- December 6/7, 2023 – Workshop

## Submit a task to the collaborative benchmark
Head over to the [GenBenchCBT github repository](https://github.com/GenBench/genbench_cbt) and following the instructions in the README to create your submission files. Before making your official submission, you will need to send a sample submission for validation by the GenBench team via a Pull Request to the repository.

Once we have approved the sample, and you have finalised your submission, you can create a new Pull Request.

### Sample submissions
The sample submission must include a fully specified `config.jsonnet` (and optionally `task.py`) file, as well as a minimal description of the task in the `doc.md` file. Samples should also include at least one example per dataset split. If the datasets are hosted on HuggingFace, the sample must include at least one example index (per split). If the datasets are hosted by the participants, a `jsonl` file with at least one line must be provided in a publicly accessible URI.

Once a sample sumbission PR is received, the GenBench team will perform a series of validation checks and confirm that the submission fits the criteria of the benchmark. Participants will be notified about any changes they need to make and once the sample PR has been approved, they will be invited to submit the full task and paper for review.

### GenBench Collaborative Benchmark Task submission workflow
![GenBench Collaborative Benchmark Task submission workflow!](/assets/images/cbt-flowchart.png "CBT submission workflow")


## FAQ
#### What is generalisation?
The answer to the question "what is generalisation" likely differs per person. In the CBT, we therefore do not maintain a strict definition, other than that what is evaluated should go beyond purely i.i.d. or random testing. It is up to the submitter to convince the reviewers that their submission targets generalisation and describe why and how it does so. If you are in doubt, feel free to reach out to the workshop organisers.

#### Why do I need to do a sample submission, and why is there an early deadline for that?
To make sure we can assess all CBT submissions in time, we ask that submitters send in a sample submission at least one month before the paper submission deadline. We will check if the submission technically makes sense and provide some feedback if needed. The sample submission does not need to contain your complete submission, but should contain a working version of the functions you intend to overwrite, and contain at least a few samples to ensure that saliency checking is possible.

#### I have a published paper about a dataset that I would like to have on the platform, can I submit it?
Yes you can! We very much encourage submissions of existing generalisation evaluations, which can be submitted along with an extended abstract.

#### How can I evaluate generalisation for an LLM if I don't know anything about the training data?
Excellent question! We have no clear answer to this, but we hope that some of you will come up with creative solutions to do so!
#TODO ADD: some suggestions? Point out that they can ask submitters to provide specific information about the training corpus, and refer to example?

#### I have an evaluation task that doesn't fit the existing protocols, can I propose a change?
Yes, reach out to us at genbench@googlegroups.com. We welcome proposals that extend our current benchmark, but we cannot guarantee that we will implement any fixes or changes in time for the workshop.
