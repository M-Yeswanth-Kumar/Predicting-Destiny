# Predicting Destiny ✋🔮
*A computer vision pipeline for palm line detection and analysis*

## 📌 Overview
This project analyzes palm images to detect key hand landmarks, extract palm lines, and classify features for measurement and interpretation.  
It uses **Python, OpenCV, MediaPipe, and PyTorch**.  

I restructured and documented this project (with permission from the original author) so it’s easier to set up, run, and extend.  

---

## 🚀 Features
- Detect palm landmarks using MediaPipe  
- Extract and measure palm lines  
- Deep learning–based line detection  
- Easy CLI to run on your own images  

---

## ⚙️ Installation
Clone and set up a virtual environment:
```bash
git clone https://github.com/M-Yeswanth-Kumar/Predicting-Destiny.git
cd Predicting-Destiny

python -m venv .venv
source .venv/bin/activate    # Windows: .venv\Scripts\activate
pip install -r requirements.txt

