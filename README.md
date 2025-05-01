# Emoji Detection and Localization with TensorFlow 2.4

This project trains a deep learning model to **classify** and **localize** emoji images using a simple synthetic dataset. It detects which emoji is present in the image and predicts its location using bounding box coordinates.

---

## 🧠 Features

- 9 different emoji classes (e.g. happy, laughing, sad, crying, etc.)
- Random placement of emojis on a white canvas (144x144 pixels)
- Multi-output model:
  - Classification (Softmax over 9 emoji classes)
  - Bounding box regression (center coordinates)
- Custom IoU metric to evaluate bounding box accuracy
- Synthetic data generation pipeline (no dataset download required)
- Training visualized with predictions after each epoch

---
