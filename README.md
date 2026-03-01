# Universal-Ai-Image-Detector

## Overview
Universal detector for GAN and Diffusion-generated images using CLIP Vision Transformer and Digital Forensic Signal Analysis.

## Architecture
Image → Preprocessing → CLIP → Forensic Features → Classifier → Output

## Features
- Cross-model generalization
- PRNU-based analysis
- FFT frequency analysis
- Hybrid ViT architecture

## Installation
pip install -r requirements.txt

## Training
python src/training/train.py --config configs/hybrid_model.yaml

## Inference
python app/inference.py --image sample.jpg
