# Final Project - Alzheimer's Disease Abstract Analysis

## Project Overview
This project applies machine learning techniques to automatically identify:
- Cognitive symptoms (e.g., memory loss, forgetfulness, cognitive decline)
- Environmental risk factors (e.g., air pollution, obesity, smoking)

from PubMed abstracts related to Alzheimer's disease.

---

## Folder Structure

| File | Description |
|:---|:---|
| `Symptom_Forgetfulness.ipynb` | Symptom identification using TF-IDF + Logistic Regression and DistilBERT |
| `Symptom_Forgetfulness.pdf` | PDF export of the Symptom_Forgetfulness notebook |
| `Symptom_Forgetfulness_Datasets.zip` | Datasets used for symptom recognition |
| `Risks.ipynb` | Risk factor identification using TF-IDF + Logistic Regression and DistilBERT |
| `Risks.pdf` | PDF export of the Risks notebook |
| `Risks_Datasets.zip` | Datasets used for risk factor recognition |
| `Symptom_Selection.ipynb` | Keyword selection and symptom definition process |
| `Symptom_Selection.pdf` | PDF export of the Symptom_Selection notebook |
| `Symptom_Selection_Datasets.zip` | Datasets related to symptom keyword exploration |
| `alzheimers_abstracts.csv` | PubMed abstracts dataset for Alzheimer's disease |

---

## Important Note about `.ipynb` Files

Some of the Jupyter Notebooks (`.ipynb`) in this repository may not render properly in the GitHub web interface due to metadata inconsistencies.

✅ However, the notebooks are fully functional and can be viewed and executed locally using:
- **VS Code** with Jupyter extension
- **Google Colab** (Upload manually)
- **Jupyter Notebook / JupyterLab**

**Recommended:**
- Download the `.ipynb` file
- Open locally in your preferred notebook environment
- Execute all cells to view outputs

---

## How to Run

1. Clone this repository or download the files manually.
2. Open the desired notebook in VS Code, Jupyter, or Colab.
3. Install required Python packages:
   ```bash
   pip install pandas scikit-learn transformers datasets

## Important Notes about the Files

- `.ipynb` (Jupyter Notebooks): 
  - Contain the full code for symptom identification, risk factor identification, and keyword selection.
  - Some notebooks may not render properly on GitHub due to metadata issues, but they can be opened locally without problems.

- `.pdf` Files:
  - Each `.pdf` file is a static export of the corresponding `.ipynb` notebook.
  - **The PDFs preserve the original outputs/results** generated when the notebooks were first executed, including:
    - Model evaluation metrics (accuracy, precision, recall, F1-score)
    - Confusion matrices
    - Sample predictions
  - If you cannot open the `.ipynb` correctly online, you can directly check the `.pdf` to review the results.

- `.zip` Files:
  - Each `.zip` archive contains the datasets used for model training and evaluation.
  - These datasets were derived from PubMed abstracts and labeled based on specific keyword rules for symptoms and environmental risk factors.

---

## Quick Overview

| File Type | Content Description |
|:---|:---|
| `.ipynb` | Full code (symptom/risk factor identification) |
| `.pdf` | Final results (saved outputs of original runs) |
| `.zip` | Datasets for training and testing |

---
