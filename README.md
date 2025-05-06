# 🤖 Telegram_Bot_Multiple_Models_Image_Classification_Torch

## 📌 Overview

This repository contains a **Telegram Bot** that uses deep learning **image classification models** to recognize content in images sent by users.  
It supports **multiple models** such as:

- 🐶 Dog vs 🐱 Cat  
- 🌼 Dandelion vs Daisy  

Built with **PyTorch** and the **python-telegram-bot** library, this bot allows interactive model selection and image classification directly through Telegram.

---

## 📋 What's Inside?

- ✅ Model selection via inline buttons  
- ✅ Multiple PyTorch classification models (CNN-based)  
- ✅ Real-time image classification via Telegram  
- ✅ Modular and extensible codebase  
- ✅ Easy integration for adding new models

---

## 🛠 Tech Stack

- **Python** 🐍  
- **PyTorch** 🔥  
- **Torchvision** 🎯  
- **Pillow (PIL)** 🖼️  
- **Telegram Bot API** 🤖  
- **python-telegram-bot** 📬
  
---

## 📥 Weights File

🔗 **Download Pretrained Weights:**  
[📁 Google Drive Link](https://drive.google.com/drive/folders/1WzQKkPYrQSfiyuT0s7hogyfiE4Z2Up3A?usp=sharing)

---

## 🧠 Model Customization

To add new classification models:

1. Add the `.pth` file in the `Weights/` folder.
2. Update the `data` dictionary in `main.py` with:
   ```python
   data = {
       ...
       3: {
           "class_names": ["ClassA", "ClassB"],
           "weights_name": "your_model.pth",
       }
   }
