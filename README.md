# 🧠 My CNN Model

This project implements a **Convolutional Neural Network (CNN)** for image classification.  
It is developed and tested inside a single **Jupyter Notebook** for simplicity and easy experimentation.  
The model can be trained on datasets like **MNIST** or **CIFAR-10**.

---

## 📂 Project Structure
```

├─ my\_cnn\_model.ipynb     # main notebook (training + evaluation)
└─ requirements.txt       # dependencies

````

---

## ⚙️ Setup

Clone the repository:
```bash
git clone https://github.com/SamaNawar964/my-cnn-model.git
cd my-cnn-model
````

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook my_cnn_model.ipynb
```

---

## 📊 Results

* **Validation Accuracy**: \~98% on MNIST
* **Test Accuracy**: \~97%

Sample predictions:

* Digit "7" → 0.99 confidence
* Digit "3" → 0.97 confidence

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

---

## 🚀 Future Improvements

* Extend to more complex datasets (CIFAR-10, CIFAR-100).
* Add data augmentation for better generalization.
* Experiment with different CNN architectures (VGG, ResNet, EfficientNet).

---

## 📌 Acknowledgements

* Dataset: [MNIST](http://yann.lecun.com/exdb/mnist/) / [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
* CNN concepts inspired by Deep Learning best practices.
