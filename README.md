# 🖋️ Handwritten Digit Recognition using MNIST Dataset

![Repo Size](https://img.shields.io/github/repo-size/shxdabb/Handwritten-Digit-Recognition-using-MNIST-Dataset?style=flat-square)
![Contributors](https://img.shields.io/github/contributors/shxdabb/Handwritten-Digit-Recognition-using-MNIST-Dataset?style=flat-square)
![Stars](https://img.shields.io/github/stars/shxdabb/Handwritten-Digit-Recognition-using-MNIST-Dataset?style=flat-square)
![Forks](https://img.shields.io/github/forks/shxdabb/Handwritten-Digit-Recognition-using-MNIST-Dataset?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/shxdabb/Handwritten-Digit-Recognition-using-MNIST-Dataset?style=flat-square)
![License](https://img.shields.io/github/license/shxdabb/Handwritten-Digit-Recognition-using-MNIST-Dataset?style=flat-square)

This project uses a deep learning model built with TensorFlow/Keras to recognize handwritten digits (0–9) from the MNIST dataset. The model is trained on grayscale 28x28 pixel images and achieves high accuracy using a simple feedforward neural network (ANN).

## 🧠 Model Architecture

- **Input Layer**: 784 neurons (flattened 28x28 image)
- **Hidden Layer**: 128 neurons, ReLU activation
- **Output Layer**: 10 neurons, Softmax activation

## 📦 Libraries Used

- TensorFlow
- Keras
- NumPy
- Matplotlib

## 🖥️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/shxdabb/Handwritten-Digit-Recognition-using-MNIST-Dataset.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook mnist_digit_recognition.ipynb
```

## 📊 Training Results

- ✅ Test Accuracy: ~98%
- 📈 Training Visuals:

![Accuracy](accuracy_plot.png)
![Loss](loss_plot.png)

## 📁 File Summary

| File Name                 | Description                                  |
|--------------------------|----------------------------------------------|
| `mnist_digit_recognition.ipynb` | Jupyter Notebook with full implementation |
| `requirements.txt`       | Required Python libraries                     |
| `accuracy_plot.png`      | Training accuracy plot                        |
| `loss_plot.png`          | Training loss plot                            |
| `model.h5`               | (Optional) Saved model file                   |

## 📜 License

MIT License

## 👤 Author

shadab perwez
