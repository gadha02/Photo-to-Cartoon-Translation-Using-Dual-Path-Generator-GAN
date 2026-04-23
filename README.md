# Dual Path Generator GAN for Image Cartoonization

## Overview
This project implements a Generative Adversarial Network (GAN) for image cartoonization using a Dual Path Generator and multiple discriminators. The generator separates content and style learning to preserve structural details while enhancing cartoon features, while multiple discriminators improve texture, consistency, and overall visual quality.

---

## Features
- Dual Path Generator (content + style separation)  
- Multiple Discriminators for improved realism  
- Better structure preservation and stylization  
- Reduced artifacts compared to basic GANs  

---

## Architecture

### Generator
- Encoder → Shared Feature Map → Residual Blocks  
- Dual Path:
  - Content Path (structure preservation)  
  - Style Path (cartoon enhancement)  
- Decoder → Output Image  

### Discriminators
- Multiple discriminators used to guide training  
- Improve texture, style consistency, and realism  

---

## Dataset
This project uses a cartoonization dataset consisting of real-world images and cartoon-style images.

🔗 Dataset Link:  
[https://www.kaggle.com/datasets/arnaud58/landscape-pictures  ](https://huggingface.co/datasets/dqymaggie/cartoonizer-dataset)

---

## ⚙️ Tech Stack
- Python  
- PyTorch  
- OpenCV  
- NumPy  

---

## 🔧 Installation

```bash
git clone https://github.com/gadha02/Photo-to-Cartoon-Translation-Using-Dual-Path-Generator-GAN.git
cd Photo-to-Cartoon-Translation-Using-Dual-Path-Generator-GAN
