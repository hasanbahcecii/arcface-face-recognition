# Celebrity Face Recognition with CNN (LFW Dataset)

This project implements a **Convolutional Neural Network (CNN)** that detects and recognizes celebrity faces using the **LFW (Labeled Faces in the Wild)** dataset. It is built using **PyTorch** and includes custom modules like `ArcFace`, `SEResNet`, and a training/testing pipeline.

> ⚠️ Due to GitHub's file size limitations, this repository does **not** include the full dataset. Please follow the instructions below to get started.

---

## 📁 Project Structure

- `train.ipynb` — Main notebook for training the model
- `data/` — Contains dataset loading utilities
- `backbone/` — SEResNet-IR model definition
- `margin/` — ArcMargin loss module
- `util/` — Utility functions for saving and testing

---

## 📦 Dependencies

Before running the project, install the following Python packages:

```bash
!pip install torch
!pip install torchvision
!pip install easydict
!pip install opencv-python
```

---

## 🔗 Dataset Setup
Download the full dataset ZIP file from BTK Akademi:

Download Link
https://files.btkakademi.gov.tr/128_BILGISAYARLI_GORU_UYGULAMA_ALANLARI/Bolum_1_2_3_4_Yuz_Tanima.zip

Unzip the archive into your working directory. Make sure the folder structure is preserved.

Replace the train.ipynb file from the ZIP archive with the one in this repository.

💡 Make sure all ZIP files inside the downloaded archive are extracted in place. The data loader relies on the correct folder hierarchy.

---

## 📚 About the Project
This face recognition system was developed as part of the "Bilgisayarlı Görü Uygulama Alanları" course offered by BTK Akademi. The course covers practical applications of computer vision using deep learning tools like PyTorch.

---

## 🙏 Acknowledgments
Special thanks to BTK Akademi for providing the dataset and course materials used in this project.

---

## License
This project is licensed under the [MIT License](https://opensource.org/license/MIT).
