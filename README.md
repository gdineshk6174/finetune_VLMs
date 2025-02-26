 
# Fine-Tuning Vision-Language Model (VLM) for Chart-Based Question Answering

With Vision-Language Models (VLMs), you can ask questions about an image and receive answers. <br>
We'll do it on images with visual data representations, such as graphs and charts. We'll use HuggingFaceM4/ChartQA as the dataset.

 
## Overview

This repository provides a step-by-step guide to fine-tuning a Vision-Language Model (VLM) for answering questions about images containing visual data representations, such as graphs and charts. We will fine-tune SmolVLM using a LoRA adapter and 4-bit quantization, leveraging the HuggingFaceM4/ChartQA dataset.

## Features
 

Model: SmolVLM-Instruct

Dataset: HuggingFaceM4/ChartQA

Fine-tuning Method:

LoRA Adapter for efficient parameter tuning

4-bit quantization for optimized performance

Task: Visual Question Answering (VQA) on charts and graphs

## Results

The fine-tuned model improves performance on chart-based visual question answering.

LoRA and 4-bit quantization make the model efficient for training and inference.

##Acknowledgments

SmolVLM (https://huggingface.co/blog/smolvlm)

ChartQA  (HuggingFaceM4/ChartQA)
