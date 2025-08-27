# 🩺 Chest X-Ray Pneumonia Classification

This project fine-tunes **ResNet50** to classify chest X-rays into **Pneumonia** or **Normal** cases.  
It is implemented entirely in a single **Jupyter Notebook** for simplicity.  
The dataset used is the [Kaggle Chest X-ray Pneumonia dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).

---

## 📂 Project Structure
```

├─ chest\_xray\_pneumonia.ipynb   # main notebook (data, training, evaluation, predictions)
└─ requirements.txt             # dependencies

````

---

## ⚙️ Setup

Clone the repository:
```bash
git clone https://github.com/SamaNawar964/chest-xray-pneumonia.git
cd chest-xray-pneumonia
````

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook chest_xray_pneumonia.ipynb
```

---

## 📊 Results

* **Validation Accuracy**: \~75%
* **Test Accuracy**: \~81%

Sample predictions:

* Pneumonia → Confidence 0.87
* Normal → Confidence 0.91

---

## 📈 Training Curves

The notebook includes plots of training history:

* Accuracy (Train vs Validation)
* Loss (Train vs Validation)

---

## 🛠️ Tech Stack

* Python 3.x
* TensorFlow / Keras
* NumPy
* Matplotlib
* OpenCV

---

## 🚀 Future Improvements

* Try other CNN architectures (EfficientNet, InceptionV3).
* Add more aggressive data augmentation.
* Deploy model as a web app (Flask/FastAPI).

---

## 📌 Acknowledgements

* Dataset: [Chest X-ray Pneumonia (Kaggle)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
* Base Model: [ResNet50](https://arxiv.org/abs/1512.03385)
