# Building an E-Commerce FAQ Chatbot using Parameter Efficient Fine Tuning and LoRA Technique

## Overview

This repository presents the implementation of an E-Commerce FAQ Chatbot empowered by Parameter Efficient Fine Tuning (PEFT) with the LoRA (Low-Rank Adaptation) Technique. The project aims to streamline customer support processes by automating responses to frequently asked questions using advanced language models.

## Table of Contents

1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Related Work](#related-work)
4. [Dataset](#dataset)
5. [Methodology](#methodology)
6. [Results](#results)
7. [Conclusion](#conclusion)
8. [Deployment](#deployment)
9. [Code and Resources](#code-and-resources)
10. [References](#references)

## Introduction

Efficiently managing customer queries is crucial for e-commerce platforms. This project introduces a chatbot solution that leverages the Falcon-7B model fine-tuned with PEFT and LoRA to automate responses to common customer questions in the e-commerce domain.

## Objectives

1. **Enhanced Customer Support:** Automate responses to FAQs to provide swift and accurate customer assistance.
2. **Operational Efficiency:** Reduce operational costs by minimizing manual intervention in handling routine inquiries.
3. **Resource Optimization:** Enable customer service agents to focus on complex issues by automating responses to repetitive queries.

## Related Work

The project builds upon existing research using advanced language models such as OpenAI's GPT and META's LLAMA models. It compares the performance of fine-tuned models with retrieval-augmented generation approaches and explores applications like IBM Watson Assistant and Ada Healthcare Chatbot.

## Dataset

The dataset, sourced from Kaggle, consists of 79 question-answer pairs. It is split into 67 samples for training (85%) and 12 samples for testing (15%).

## Methodology

The methodology involves fine-tuning the Falcon-7B model using PEFT and LoRA adapters. It includes data preprocessing steps, configuration of LoRA adapters, and iterative model training using libraries like Transformers and Peft by Hugging Face.

## Results

During training, the model demonstrates a consistent decrease in loss values across epochs, indicating effective learning. Evaluation metrics such as Bleu score highlight the model's ability to generate responses that align well with expected outputs.

## Conclusion

This project showcases the potential of advanced language models to enhance customer support in e-commerce. While initial results are promising, ongoing refinement and experimentation with larger datasets are recommended for further improvements.

## Deployment

The fine-tuned model is available on the Hugging Face Model Hub for deployment and further experimentation: [Link to Hugging Face Model](https://huggingface.co/bnsapa/faq-llm)

## Code and Resources

Feel free to explore the code and resources provided in this repository for insights into building and fine-tuning advanced chatbot models for e-commerce customer support.

## References

1. [Language Models are Few-Shot Learners - Tom B. Brown et al (2020)](https://arxiv.org/abs/2005.14165)
2. [LLAMA 2: Open Foundation and Fine-Tuned Chat Models (2023)](https://arxiv.org/abs/2307.09288)
3. [Few-Shot Parameter-Efficient Fine-Tuning is Better and Cheaper than In-Context Learning - Haokun Liu et al (2022)](https://arxiv.org/abs/2205.05638)
4. [LoRA: Low-Rank Adaptation of Large Language Models - Edward J Hu et al (2021)](https://arxiv.org/abs/2106.09685)
5. [An overview of Bard: an early experiment with generative AI - James Manyika (2023)](https://ai.google/static/documents/google-about-bard.pdf)
6. [IBM Watson Assistant](https://www.ibm.com/products/watsonx-assistant)
7. [Hugging Face Blog on PEFT](https://huggingface.co/blog/peft)

This repository aims to contribute to advancing automated customer service capabilities in e-commerce through innovative application of state-of-the-art language models.