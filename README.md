# multimodal-vision-language-model
ViT-based Vision–Language Model for semantic image search using contrastive learning
# Multimodal Vision–Language Model (VLM)

This project implements a ViT-based Vision–Language Model trained using contrastive learning on the Flickr8k dataset.

## 🚀 Features
- Vision Transformer (ViT) image encoder
- Transformer-based text encoder (DistilBERT)
- Contrastive learning for image–text alignment
- Semantic image search
- Image–text matching

## 🧠 Architecture
- Image Encoder: ViT-Base (google/vit-base-patch16-224)
- Text Encoder: DistilBERT
- Shared embedding space using projection heads
- CLIP-style contrastive loss

## 📊 Dataset
- Flickr8k
- 8,092 images
- ~40,460 image–caption pairs

## 🔍 Applications
- Semantic image search using natural language queries
- Image–text similarity scoring

## 🛠 Tech Stack
- PyTorch
- HuggingFace Transformers
- Kaggle GPU

## 📌 Example Query
