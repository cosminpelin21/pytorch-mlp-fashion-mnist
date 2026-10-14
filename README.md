# Fashion-MNIST Classification with PyTorch (MLP)

A Multilayer Perceptron (MLP) built with **PyTorch** to classify the 10 clothing categories from the Fashion-MNIST dataset. Developed as a university project for an Artificial Intelligence / Deep Learning laboratory assignment.

---

## 📌 Project Overview
- **Task**: Multi-class image classification (10 classes: T-shirt, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot).
- **Model**: Fully-connected Multilayer Perceptron (Input: 784 -> Hidden: 512 -> Hidden: 512 -> Output: 10) with ReLU activations.
- **Loss Function**: `torch.nn.CrossEntropyLoss`
- **Optimizer**: `torch.optim.SGD`
- **Evaluation**: Per-epoch training & test accuracy curves, plus a Confusion Matrix (`scikit-learn` & `matplotlib`).

---

## 📁 Repository Structure
```text
├── data.zip                    # Compressed dataset (contains train & test CSVs)
├── fashion_mnist_mlp.ipynb     # Main Jupyter / Google Colab notebook
└── README.md                   # Project documentation
```

---

## 🚀 Getting Started

### In Google Colab (Recommended)
1. Upload `fashion_mnist_mlp.ipynb` and `data.zip` to your Colab session.
2. In the first cell of your notebook, unzip the dataset into the `./data/` folder:
   ```bash
   !unzip -o data.zip -d ./data
   ```
3. Run all cells sequentially.

---

## 📊 Results
- **Training Epochs**: 10
- **Test Accuracy**: ~79.6% (baseline SGD)
- **Visualizations**: Epoch accuracy comparison plot & Confusion Matrix heatmap.

---

## 🎓 Academic Context
Developed as part of the Artificial Intelligence curriculum (University Coursework).
