# SCS4107 — Causal AI Emergency Fund & Bill-Pay Notebook

This repository contains the deliverable Jupyter notebook for the University of Toronto SCS4107 Advanced Artificial Intelligence: Probabilistic Programming and Causal AI final project.

## What is included

| File | Purpose |
|------|---------|
| `causal_ai_emergency_fund_notebook.ipynb` | Main Jupyter notebook with the full analysis, models, visualizations, and commentary |
| `causal_ai_emergency_fund_notebook.txt` | Plain-text export of the notebook for quick review or diffing |
| `module_labels_validation.txt` | Validation notes for module and cell labels |
| `notebook_summary.json` | Machine-readable summary metadata of the notebook structure |
| `reorder_validation.txt` | Validation log from notebook cell reordering |
| `data/raw/shed_2023.csv` | SHED 2023 public use data file used by the notebook |

## How to view or run the notebook

### Option 1 — Google Colab (recommended, no installation required)

Click the badge below to open the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rfiez/scs4107_final_project_rueen_saneem_causal_emerg_fund_bill_pay/blob/main/causal_ai_emergency_fund_notebook.ipynb)

Alternatively:

1. Go to [https://colab.research.google.com/github](https://colab.research.google.com/github)
2. Enter this repository URL: `https://github.com/rfiez/scs4107_final_project_rueen_saneem_causal_emerg_fund_bill_pay`
3. Select `causal_ai_emergency_fund_notebook.ipynb`
4. Run cells by clicking the ▶ button next to each cell

> **Note:** The notebook downloads the SHED 2023 CSV automatically from this repository's `data/raw/shed_2023.csv` file, so no manual upload is required in Colab.

### Option 2 — Run locally in VS Code

1. Clone this repository:
   ```bash
   git clone https://github.com/rfiez/scs4107_final_project_rueen_saneem_causal_emerg_fund_bill_pay.git
   cd scs4107_final_project_rueen_saneem_causal_emerg_fund_bill_pay
   ```
2. Open the folder in VS Code.
3. Open `causal_ai_emergency_fund_notebook.ipynb`.
4. Click **Select Kernel** (top-right) and choose your Python environment.
5. Run all cells with `Shift + Enter` or use the **Run All** button.

### Option 3 — Run locally with Jupyter

1. Clone this repository (same command as above).
2. Install Jupyter if it is not already installed:
   ```bash
   pip install notebook
   ```
3. Start Jupyter from this folder:
   ```bash
   jupyter notebook
   ```
4. Click `causal_ai_emergency_fund_notebook.ipynb` in the browser.

## Repository visibility

This repository is **public**. Anyone with the link can view and run the notebook.

## How to contribute

If you are a collaborator and want to push changes:

1. Accept the collaborator invite if one was sent.
2. Clone the repository (or pull the latest version):
   ```bash
   git clone https://github.com/rfiez/scs4107_final_project_rueen_saneem_causal_emerg_fund_bill_pay.git
   git pull
   ```
3. Make your edits.
4. Commit and push:
   ```bash
   git add .
   git commit -m "Describe your change"
   git push
   ```

## Questions

For questions about the analysis, methodology, or results, please refer to the notebook itself or contact the repository owner.
