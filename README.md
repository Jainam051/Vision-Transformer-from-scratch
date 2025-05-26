# Vision Transformer (ViT) – Built from Scratch

A deep learning project where I implemented a Vision Transformer (ViT) architecture **entirely from scratch** using PyTorch — without relying on pre-built attention or transformer modules.

> 📅 Developed in February 2025 as a hands-on deep learning and model-building exercise.

---

## 🚀 Project Highlights

- ✅ Built a working Vision Transformer (ViT) model from the ground up using **pure PyTorch**.
- 🧠 Implemented key components manually:
  - Multi-Head Self-Attention (MHSA)
  - Positional Encoding
  - Patch Embedding
  - Transformer Encoder Blocks
- 🔬 Gained deep insight into:
  - Transformer mechanics in computer vision
  - Low-level tensor operations in PyTorch
  - End-to-end model training workflows

---

## 🛠️ Components

### 🔹 Patch Embedding
Splits input images into patches and flattens them into vectors, simulating "tokens" for the transformer.

### 🔹 Positional Encoding
Adds positional information to patch embeddings to preserve spatial relationships.

### 🔹 Multi-Head Self-Attention (MHSA)
Manually implemented attention mechanism with query/key/value projections and attention weights.

### 🔹 Transformer Encoder
Stacked encoder blocks, each containing:
- LayerNorm
- Multi-head attention
- MLP feed-forward network
- Residual connections

---

## 📂 Project Structure

