# Image Captioning with ViT-GPT2 on Flickr8k

## Overview
Fine-tune the `nlpconnect/vit-gpt2-image-captioning` model on the Flickr8k dataset.  
- **Baseline**: run the pretrained model on a fixed set of images  
- **Fine-tuning**: adapt the model to Flickr8k (≥1 000 examples)  
- **Evaluation**: compare generated captions before and after fine-tuning  

## Installation
```bash
pip install --upgrade pip setuptools wheel
pip install transformers torch pillow datasets torchvision accelerate
