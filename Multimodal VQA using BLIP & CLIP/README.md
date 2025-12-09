# Visual Question Answering (VQA) with CLIP & BLIP

## Overview
Implements a Visual Question Answering system that answers questions about images using CLIP and BLIP models, deployed via Gradio for interactive use.

## Features
- Understands image content and answers user prompts  
- CLIP-based model: concatenates image & text embeddings, predicts answers  
- BLIP-based model: uses ViT + cross-attention for better text-image alignment  
- Early stopping and model checkpoints for robust training  
- Evaluation metrics: Accuracy and Average Precision

## Dataset
Uses VizWiz 2023 VQA dataset with train, validation, and test sets.

## Installation
```bash
git clone <repo_link>
pip install -r requirements.txt
pip install git+https://github.com/openai/CLIP.git
pip install git+https://github.com/salesforce/BLIP.git
