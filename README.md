# 🧠 XOR Decision Boundary Visualization (PyTorch)

> This notebook trains a neural network on the XOR problem and visualizes its decision boundary using PyTorch.

## 🎯 What this notebook covers:

- Defining the XOR dataset (4 points)
- Building a neural network with a hidden layer (2 → 4 → 1)
- Training the model for 500 epochs
- Visualizing the decision boundary as a heatmap
- Understanding how the model separates the 2D space

## 📊 Expected Results:

- ✅ 100% accuracy on XOR
- Clear non-linear decision boundary
- Red/Blue regions matching the correct classes

## 🏗️ TestModel Architecture

| Layer | Type | Input | Output |
|-------|------|-------|--------|
| 1 | Linear | 2 | 4 |
| 2 | ReLU | 4 | 4 |
| 3 | Linear | 4 | 1 |
| 4 | Sigmoid | 1 | 1 |

**Total Parameters:** 21

## 🎨 Visualization

The decision boundary shows:

- 🟦 **Blue region** → Model predicts 0
- 🟥 **Red region** → Model predicts 1
- ⬜ **Curved line** → Decision boundary (at 0.5)

## 🚀 How to Run

1. Open `xor-decision-boundary-visualization.ipynb`
2. Run all cells
3. Check the decision boundary plot

## 📦 Requirements

```bash
pip install torch numpy matplotlib
