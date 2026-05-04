# 🚀 Offroad Semantic Segmentation Model

## 👥 Team Details

**Team Name:** QUANTUM CODER
**Members:** Ankush Rao, Ayush Gupta, Aditi, Aman

---

## 📌 Project Overview

This project focuses on building a robust **semantic segmentation model** for off-road desert environments using synthetic data generated from Duality AI's Falcon platform.

The goal is to classify each pixel in an image into categories such as trees, bushes, rocks, sky, and ground. The model is trained on synthetic images and evaluated on unseen desert environments to test its generalization capability.

---

## 🎯 Objectives

* Train an accurate segmentation model using provided dataset
* Achieve high performance on unseen test images
* Optimize model for better generalization and efficiency

---

## 🧠 Methodology

### 1. Data Preparation

* Used provided dataset (Train, Validation, Test)
* Applied preprocessing and normalization
* Performed data augmentation (if any)

### 2. Model Used

* Model Architecture: (e.g., UNet / DeepLabV3 / Custom CNN)
* Framework: PyTorch / TensorFlow

### 3. Training

* Trained using `train.py`
* Optimized using loss functions and hyperparameters
* Saved checkpoints and logs

### 4. Testing

* Evaluated using `test.py`
* Generated predictions on unseen images

---

## 📊 Performance Metrics

* **IoU Score:** (mention your value)
* **mAP50 Score:** 0.9834
* Loss graphs and performance trends included in report

---

## ⚙️ Setup Instructions

### 🔹 Requirements

* Python 3.x
* Anaconda / Miniconda (recommended)
* Required libraries (see requirements.txt)

### 🔹 Installation

```bash
conda create -n EDU python=3.8
conda activate EDU
pip install -r requirements.txt
```

---

## ▶️ How to Run

### Train Model

```bash
python train.py
```

### Test Model

```bash
python test.py
```

---

## 📁 Project Structure

```
├── train.py
├── test.py
├── dataset/
├── runs/
├── models/
├── README.md
```

---

## 🚧 Challenges Faced

* Generalization on unseen environments
* Class imbalance in dataset
* Misclassification of similar objects

---

## 💡 Improvements

* Advanced data augmentation
* Better model architecture
* Hyperparameter tuning

---

## 📌 Conclusion

The project successfully demonstrates how synthetic data can be used to train robust AI models for real-world applications like autonomous navigation. The model performs well on unseen data, showing good generalization capability.

---

## 🔗 Repository Link

https://github.com/sfayush2029/HACK-gfg.git
