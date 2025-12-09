# CLIP Image Classification

## Overview
Classifies images using OpenAI's CLIP model for zero-shot vision-language tasks, allowing flexible classification via textual prompts.

## Features
- Asynchronous image processing for faster batch handling  
- Dynamic prompt generation for flexible queries  
- Confidence thresholding to filter uncertain predictions  
- Multi-modal retrieval: image-to-text and text-to-image  
- GPU acceleration if available  

## Requirements
Python 3.7+, PyTorch, Transformers, Pillow, Matplotlib, Asyncio  
```bash
pip install torch torchvision torchaudio transformers pillow matplotlib
