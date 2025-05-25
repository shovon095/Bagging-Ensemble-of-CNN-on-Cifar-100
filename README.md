# 🧠 Bagging CNN Classifier for Text Classification

This repository contains a notebook implementation of a **bagging ensemble of CNN models** for text classification. The model is trained and evaluated using majority voting across multiple CNN classifiers to improve robustness and generalization.

---

## 📂 File

- `Bagging_CNN.ipynb` — Main notebook that implements:
  - Preprocessing and tokenization
  - Individual CNN model architecture
  - Training multiple CNN models with varied seeds
  - Aggregated prediction via majority vote
  - Accuracy and loss evaluation across folds

---

## ⚙️ Features

- **Ensemble learning**: Combines multiple CNN models to reduce variance
- **Stratified K-Fold cross-validation**
- **Majority vote aggregation** for final prediction
- Compatible with standard text classification datasets (e.g., sentiment analysis)

---

## How to Run

1. Launch Jupyter or VS Code
2. Open `Bagging_CNN.ipynb`
3. Run all cells sequentially

Optional: Modify hyperparameters such as:
- Number of models in the ensemble
- Epochs, learning rate, dropout
- Tokenizer or embedding settings

---

## Output

- Per-model training accuracy/loss
- Cross-validated ensemble accuracy
- Confusion matrix (if enabled)
- Majority voting results

---

## Dependencies

```bash
pip install torch numpy pandas scikit-learn matplotlib
```

Optional (for custom datasets):

```bash
pip install transformers datasets
```
---

📬 Questions? Contact via GitHub or open an issue.
