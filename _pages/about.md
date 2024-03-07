---
layout: about
title: about
permalink: /about/

news: true # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

We introduce **lmms-eval**, an evaluation framework meticulously crafted for consistent and efficient evaluation of Large-scale Multi-modality Models (LMMs).


This framework simplifies the evaluation process across a diverse array of evaluation datasets (over 50). You can evaluate the models on multiple datasets with a single command. We prepared all the evaluation datasets at [Huggingface Datasets](https://huggingface.co/lmms-lab). No preparation is needed, just one command line, few minutes, and get the results. Not just numbers, but also the detailed logs and samples, including the model args, input question, model response, and ground truth answer.
<!-- 

With its remarkable scalability, **lmms-eval** seamlessly integrates new models and evaluation datasets, requiring only a simple modification on interfaces. We provide handy documentation and examples to help you get started to integrate `lmms-eval` into your project.


To accelerate model development cycle, we leverage `accelerate` to wrap the model for distributed evaluation, supporting both multi-gpu and tensor parallelism. With **Task Grouping**, all instances from all tasks are grouped and evaluated in parallel, which significantly improves the throughput of the evaluation process. -->


Utilizing our framework in your model development cycle at [GitHub](https://github.com/EvolvingLMMs-Lab/lmms-eval/).
