# 🩺 Chest X-ray Pneumonia Classification

This project uses **transfer learning** with pre-trained CNN models to classify chest X-ray images into **Normal** or **Pneumonia** categories.
It was built and trained using **TensorFlow/Keras** and evaluated with **Test-Time Augmentation (TTA)**.

---

## 📂 Project Structure

```
📦 chest-xray-pneumonia-classification
 ┣ 📜 Chest_Xray_Pneumonia_Dataset.ipynb   # Main notebook (training + evaluation)
 ┣ 📜 README.md                            # Project documentation
 ┗ 📂 (optional: models/, data/, notebooks/ if you add later)
```

---

## 📊 Dataset

The dataset used is the **Chest X-ray (Pneumonia) dataset**.
You can download it from:
👉 [Kaggle Dataset Link](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

Dataset contains:

* `train/` : Training images
* `val/`   : Validation images
* `test/`  : Testing images

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/BarbodRE/chest-xray-pneumonia-classification.git
cd chest-xray-pneumonia-classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Or if running in **Google Colab**, just open the notebook directly.

---

## 🚀 Training & Evaluation

Open the notebook:

```bash
Chest_Xray_Pneumonia_Dataset.ipynb
```

Steps inside:

1. Load and preprocess dataset.
2. Train base model with frozen layers.
3. Fine-tune last layers.
4. Evaluate model performance.
5. Apply **Test-Time Augmentation (TTA)** for robust accuracy.

---

## 📈 Results

* **Validation Accuracy**: \~95%
* **Test Accuracy**: \~93%
* **TTA Accuracy**: \~94%

---

## 📌 Future Work

* Add more pre-trained backbones (DenseNet, EfficientNet, etc.)
* Deploy the model as a web app (Streamlit/Gradio).
* Improve dataset balance and augmentation.

---

## 👨‍💻 Author

* Barbod Rostami– [GitHub Profile](https://github.com/BarbodRE)

