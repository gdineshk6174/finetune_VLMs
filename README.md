 
# Fine-Tuning Vision-Language Model 

With Vision-Language Models (VLMs), you can ask questions about an image and receive answers. <br>
We'll do it on images with visual data representations, such as graphs and charts. We'll use HuggingFaceM4/ChartQA as the dataset.

In this case, we'll fine-tune SmolVLM (https://huggingface.co/blog/smolvlm) using a LoRA adapter and 4-bit quantization.
## Overview

This Jupyter Notebook demonstrates fine-tuning a vision-language model. It provides a step-by-step guide that includes data loading, model training, and evaluation.

## Features

- The model used to fine-tune is SmolVLM (MODELID:"HuggingFaceTB/SmolVLM-Instruct")
- Fine-tuned on the HuggingFaceM4/ChartQA dataset
- Quantized using the LoRA technique for efficient parameter usage
- Trained on 1% of the available data due to GPU constraints
- Designed for visual question-answering. 
