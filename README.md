# Self-Supervised Domain Adaptation for Skin Lesion Classification

### Group Members:
- Tran Nam Anh
- Nguyen Duc Hai

---

## Project Overview

This repository contains the source code for our IT159 Artificial Intelligence project. The project develops and evaluates a Self-Supervised Domain Adaptation (SSDA) framework for classifying skin lesions from the HAM10000 dataset. We compare our proposed method against a strong supervised baseline and an ablation study model to provide a comprehensive empirical analysis.

## Repository Contents

This repository includes two main Jupyter Notebooks:

1.  **`Training_and_Development.ipynb`**: This notebook documents the entire research and development process. It contains all experimental code, including data preparation, SimCLR pre-training, and the final training runs for the three comparative models (Baseline, SSDA, and SSL-FT).

2.  **`Demonstration.ipynb`**: This is a clean, executable notebook designed for verification and demonstration. It loads the final, pre-trained model checkpoints and evaluates them on the pre-defined "Golden Data Split" to reproduce the official results presented in our report.

## How to Reproduce Results

To run the `Demonstration.ipynb` and verify our findings, please follow these steps:

1.  **Environment:** Create a new Kaggle Notebook.
2.  **Add Code:** Upload the `Demonstration.ipynb` file to the new notebook.
3.  **Add Data:** Use the "+ Add Data" button in the Kaggle editor to add the following two public datasets:
    *   **Image Data:** `skin-cancer-mnist-ham10000`
    *   **Checkpoints & Data Split:** `it159-final-checkpoints` (or the name you gave your checkpoint dataset). The direct link is: `[PASTE THE LINK TO YOUR KAGGLE CHECKPOINT DATASET HERE]`
4.  **Run All:** Execute all cells in the notebook from top to bottom. The final accuracy and classification reports for all three models will be printed at the end.

## Testing Online
**Train**: https://www.kaggle.com/code/lineizumi/training-and-development

**Demo result**: https://www.kaggle.com/code/lineizumi/demonstration

**Checkpoints Dataset**: https://www.kaggle.com/datasets/lineizumi/it159-final-checkpoints

**HAM10000 Dataset**: https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000 (Original Data)
