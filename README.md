# 🧠 MLP Fine-Tuning for Handwritten Digit and Fashion Image Classification

This repository presents an end-to-end implementation of **Multi-Layer Perceptron (MLP)** fine-tuning using TensorFlow and Keras across multiple benchmark datasets. The project evaluates the generalization capability of a simple neural network on handwritten digit recognition and fashion image classification tasks.

The repository includes experiments on:

* **MNIST** – Handwritten digit recognition
* **Fashion-MNIST** – Fashion item classification
* **HODA** – Persian handwritten digit recognition

---

# 📌 Project Overview

The project demonstrates:

* Loading and preprocessing benchmark datasets
* Building and training an MLP classifier
* Fine-tuning across different datasets
* Model evaluation
* Saving and loading trained models
* Prediction visualization

---

# 📂 Repository Structure

```text
.
├── MNIST_FineTuning.ipynb
├── FashionMNIST_FineTuning.ipynb
├── HODA_FineTuning.ipynb
├── figures/
│   ├── mnist_results.png
│   ├── fashion_results.png
│   ├── hoda_results.png
│   └── training_curves.png
├── requirements.txt
└── README.md
```

---

# 🚀 Features

* ✅ MLP implementation using TensorFlow/Keras
* ✅ Handwritten digit recognition
* ✅ Persian handwritten digit classification
* ✅ Fashion image classification
* ✅ Fine-tuning workflow
* ✅ Model saving and loading
* ✅ Prediction visualization
* ✅ Modular and reusable implementation

---

# 🧠 Model Architecture

* Input: 28 × 28 grayscale images
* Hidden Layers: Fully Connected (Dense) + ReLU
* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Output Layer: 10 classes (Softmax)

---

# 📊 Experimental Results

| Dataset           | Classes | Training Accuracy | Validation / Test Accuracy |
| ----------------- | ------: | ----------------: | -------------------------: |
| **MNIST**         |      10 |        **97.99%** |                 **97.96%** |
| **Fashion-MNIST** |      10 |        **74.57%** |                 **78.14%** |
| **HODA**          |      10 |        **99.66%** |                 **85.10%** |

---

# 📈 Dataset Comparison

| Dataset       | Task                          | Difficulty  |
| ------------- | ----------------------------- | ----------- |
| MNIST         | Handwritten English digits    | Easy        |
| Fashion-MNIST | Fashion object classification | Medium      |
| HODA          | Persian handwritten digits    | Challenging |

---

# 💻 Technologies

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/roghayefazli/mlp-fine-tuning-handwritten-recognition.git
cd mlp-fine-tuning-handwritten-recognition
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

Run the notebooks individually:

1. `MNIST_FineTuning.ipynb`
2. `FashionMNIST_FineTuning.ipynb`
3. `HODA_FineTuning.ipynb`

---

# 🔬 Future Improvements

* Compare MLP with CNN architectures
* Hyperparameter optimization
* Data augmentation
* Persian handwritten character recognition
* Cross-dataset transfer learning

---

# 📄 License

This project is released under the MIT License.

---

# 👩‍💻 Author

**Roghayeh Fazli**

M.Sc. Student in Artificial Intelligence

GitHub: https://github.com/roghayefazli
