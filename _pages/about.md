---
layout: about
title: about
permalink: /about/

news: true # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

We introduce **lmms-eval**, an evaluation framework meticulously crafted for consistent and efficient evaluation of Visual Language Models (VLMs). This framework simplifies the evaluation process across a diverse array of evaluation datasets, numbering over 50, while generating easily interpretable logs and samples using only one command. With its remarkable scalability, lmms-eval seamlessly integrates new evaluation datasets, requiring only a simple YAML file and a few helper functions to be effortlessly incorporated into the framework. By leveraging `accelerate` techniques for speed enhancement and supporting multi-GPU and tensor parallelism, it notably boosts evaluation throughput. Furthermore, by integrating with the HuggingFace dataset, researchers are relieved of the manual task of downloading and organizing datasets from various sources. Demonstrating robust stability, our experiments with [LLaVA](https://llava-vl.github.io/) using this framework consistently yielded identical results across all evaluations. The code is available at [GitHub](https://github.com/EvolvingLMMs-Lab/lmms-eval/).
