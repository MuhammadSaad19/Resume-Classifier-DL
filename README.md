# Resume Classifier — Deep Learning 📄🤖

A deep learning model that classifies resumes into **Good**, **Average**, or **Poor** categories using image-based classification with MobileNetV2 transfer learning.

---

## 📌 Overview

This project converts resume PDFs into images and trains a **MobileNetV2** model to classify resume quality into three categories:
- ✅ Good
- ➖ Average
- ❌ Poor

---

## 📊 Dataset

- **Source:** Custom dataset of real resume PDFs
- **Size:** ~500 resume PDFs converted to images
- **Format:** PDF → JPG (converted using pdf2image)
- **Classes:** Good / Average / Poor

---

## 🏗️ Model

- **Architecture:** MobileNetV2 (Transfer Learning)
- **Approach:** Pre-trained ImageNet weights + custom classification head
- **Training Epochs:** 10
- **Model File:** `.h5` format (excluded due to size — download link below)

📥 **[Download Trained Model from Google Drive](https://drive.google.com/file/d/1Cal6rC6e8GYid4SZ3lrs244jZlTtjunf/view?usp=drive_link)** 

---

## 🛠️ Libraries Used

| Library | Purpose |
|---|---|
| `tensorflow` / `keras` | Model building and training |
| `MobileNetV2` | Pre-trained base model |
| `pdf2image` | Converting PDF resumes to images |
| `numpy` | Numerical operations |
| `PIL` | Image processing |
| `ImageDataGenerator` | Data loading and augmentation |

---

## 🚀 How to Run

**Step 1 — Install dependencies:**
```bash
pip install tensorflow pdf2image pillow numpy
apt-get install poppler-utils
```

**Step 2 — Add your resume PDFs** to the `Resume folder` directory

**Step 3 — Run the notebook cell by cell:**
- Cell 1: Mount Google Drive
- Cell 2: Install libraries
- Cell 3: Import libraries
- Cell 4: Convert PDFs to images
- Cell 5: Distribute images into class folders
- Cell 6: Train the model
- Cell 7: Run predictions

---

## 📁 Project Structure

```
Resume-Classifier-DL/
│
├── AI_Resume_Classifier.ipynb   # Main training notebook
└── README.md
```

> **Note:** Dataset (PDF/images) and model file excluded due to size.
> Download the trained model from Google Drive link above.
> To regenerate — add your PDFs and run the notebook from Cell 1.



## 👨‍💻 Author

**Muhammad Saad Amir**
- GitHub: [MuhammadSaad19](https://github.com/MuhammadSaad19)
- LinkedIn: [muhammad-saad-amir](https://linkedin.com/in/muhammad-saad-amir)
