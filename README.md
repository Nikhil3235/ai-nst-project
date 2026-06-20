---
title: AI NST Project
emoji: 🎨
colorFrom: purple
colorTo: blue
sdk: docker
pinned: false
---

# 🎨 AI Neural Style Transfer

> **Created by: Nikhil Mali**

**Transform any photo into a beautiful artwork using the power of Deep Learning!**

---

## 🌐 Live Demo

- 🚀 **Hugging Face:** [https://nikhil3235-ai-nst-project.hf.space](https://nikhil3235-ai-nst-project.hf.space)
- 💻 **GitHub:** [https://github.com/Nikhil3235/ai-nst-project](https://github.com/Nikhil3235/ai-nst-project)

---

## 📌 About

This project uses **AdaIN (Adaptive Instance Normalization)** algorithm to transfer the style of any painting onto your photo in real-time.

Upload your photo + any art style image → Get a stylized artwork! 🖼️

---

## 🛠️ Tech Stack

**| Technology | Purpose |**
**|-----------|---------|**
**| Python 3.11 | Core Language |**
**| PyTorch | Deep Learning Framework |**
**| VGG19 | Feature Extraction (Encoder) |**
**| AdaIN | Style Transfer Algorithm |**
**| Flask | Web Framework |**
**| Gunicorn | Production Server |**
**| HTML/CSS/JS | Frontend UI |**
**| Docker | Containerization |**
**| Git LFS | Large File Storage |**

---

## ⚙️ How It Works

1. Upload a **Content Image** (your photo)
2. Upload a **Style Image** (any painting/artwork)
3. Click **Transfer Style**
4. AI generates your stylized image! ✨

---

## 🚀 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/Nikhil3235/ai-nst-project.git
cd ai-nst-project

# Create virtual environment
python -m venv venv
venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
cd NST_Code
python app.py
```

Open 👉 http://localhost:5000

---

## 📁 Project Structure

ai-nst-project/

│

├── NST_Code/

│   ├── app.py              ← Flask Web App

│   ├── train.py            ← Model Training

│   ├── vgg_normalised.pth  ← VGG19 Encoder

│   ├── utils/

│   │   ├── models.py       ← Neural Network

│   │   └── utils.py        ← AdaIN Algorithm

│   ├── templates/

│   │   └── index.html      ← Frontend

│   ├── static/             ← Uploads

│   ├── content_data/       ← Sample Content Images

│   └── style_data/         ← Sample Style Images

│

├── Dockerfile              ← Docker Config

├── requirements.txt        ← Dependencies

└── README.md

---

## 👨‍💻 Developer

**Nikhil Mali**
- GitHub: [@Nikhil3235](https://github.com/Nikhil3235)
- Live App: [nikhil3235-ai-nst-project.hf.space](https://nikhil3235-ai-nst-project.hf.space)