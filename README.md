# Decision Tree Classification – Data Mining Project

This project demonstrates how to build and evaluate a decision tree classifier using Python and scikit-learn. It includes all necessary steps from data loading and preprocessing to model visualization and export.

## 📂 Repository Contents

- `Decision Tree.ipynb` – Main Jupyter Notebook performing classification, evaluation, and visualization.
- `D3.csv` – Input dataset.
- `dm_tools.py` – Python module containing helper functions used in the notebook.
- `DT.pickle` – Serialized trained decision tree model (via `pickle`).
- `dt_viz.png` – Visualization of the initial decision tree.
- `optimal_tree.png` – Visualization of the pruned or optimal decision tree.
- `requirements.txt` – List of Python dependencies.
- `README.md` – Project documentation (this file).

## 🎯 Objectives

- Load and preprocess structured data
- Train a decision tree model on the data
- Evaluate performance using classification metrics
- Visualize the decision tree structure using `pydot` and export graphics
- Save and reuse models with `pickle`
- Separate reusable functions into an external script (`dm_tools.py`)

## 🚀 How to Run This Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/decision-tree-project.git
cd decision-tree-project
```

### 2. Install required packages:

```bash
pip install -r requirements.txt
```

### Launch the notebook:

```bash
jupyter notebook "Decision Tree.ipynb"
```
