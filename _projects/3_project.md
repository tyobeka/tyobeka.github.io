---
layout: page
title: Tuning Meta LLMs for African Language Machine Translation 
description: Can you translate English to Twi using Meta LLM?
img: assets/img/zindi_hackathon.png

importance: 1
category: fun
---
{% include figure.liquid loading="eager" path="assets/img/zindi_hackathon.png" title="image of woman analysing data by @diversifysketch on canva" class="img-fluid rounded z-depth-1" %}

### Task:

Fine-tune any one of Meta's open-source language models for the translation of English to Twi using an English-to-Twi parallel corpus that was developed by <a href="https://ghananlp.org">GhanaNLP.</a> 

<b>Link to the challenge:</b> <a href="https://zindi.africa/competitions/tuning-meta-llms-for-african-language-machine-translation">zindi-hackathon</a>

### Summary:

For this hackathon, I chose to make use of the <a href="https://ai.meta.com/research/no-language-left-behind/">No Language Left Behind</a> (NLLB) machine translation model which supports translations between 200 languages, including English and Twi. Because the training parallel corpus was so small, there were only 4 800 sentence pairs, my decision to use the NLLB model was as a result of the fine-tuning process benefitting from using a model that had  been pre-trained not only for translation, but also the translation of text from English to Twi. 

From Meta's HuggingFace <a href="https://huggingface.co/facebook">repository</a>, one can access derivatives of their open-source models. The original NLLB model is composed of 3.3B parameters. I used the distilled variant of the model, that is composed 600M parameters, because it requires fewer computational resources to train while still being able to efficiently approximate the performance of the original model. 


Low-Rank Adaptation (LoRA) was used for fine-tuning. It allows a user to reduce the number of parameters that are updated during training to minimise the storage requirements for fine-tuning these massive language models. 

<b>Link to certificate:</b> <a href="https://drive.google.com/file/d/1qPMzo7vC60FvybAgs1v6M3dch-nj3jkR/view?usp=sharing">certificate-of-participation</a>

### Tools:

All models were trained in Python.

<b>Link to model checkpoints:</b> <a href="https://huggingface.co/nails-tyobs">hugging-face-repo</a>