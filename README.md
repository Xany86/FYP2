===========================================
Hierarchical Clustering for ECG with XAI
===========================================

This project demonstrates how hierarchical clustering can be applied to ECG signals, with the integration of Explainable Artificial Intelligence (XAI) techniques to interpret clustering outcomes.

───────────────────────────────────────────

1. TOOLS & ENVIRONMENT

───────────────────────────────────────────

- **Python Version**: 3.9 or later
- **Recommended IDE**: Jupyter Notebook
- **Operating System**: Windows / Linux / macOS

Useful Tools (with download links):
- Anaconda (includes Jupyter) → https://www.anaconda.com/products/distribution
- Jupyter Notebook (standalone) → https://jupyter.org/install

───────────────────────────────────────────

2. REQUIRED PYTHON LIBRARIES

───────────────────────────────────────────

Install the following libraries before running the notebook:

pip install numpy

pip install pandas

pip install matplotlib

pip install seaborn

pip install scipy

pip install scikit-learn

pip install neurokit2

pip install eli5

pip install wfdb

───────────────────────────────────────────

3. DATASET INFORMATION

───────────────────────────────────────────

Dataset Used:
MIT-BIH Arrhythmia Database

Download from PhysioNet:
→ https://physionet.org/content/mitdb/1.0.0/

Steps:

1) Visit the link above.
2) Click “Download the entire database in WFDB format (35.6 MB)”.
3) Extract the files into a folder named data/ inside your project directory.
4) Ensure that .dat, .hea, and .atr files are included for the records used.

───────────────────────────────────────────

4. HOW TO RUN THE NOTEBOOK

───────────────────────────────────────────

Steps:
1) Open Jupyter Notebook.

2) Load the file:
final-hierarchical-clustering-for-ecg-with-xai.ipynb

3) Run all cells in order (Shift + Enter).

The notebook will:
-Load ECG data.
-Extract HRV and morphological features using NeuroKit2.
-Perform hierarchical clustering with SciPy and Scikit-learn.
-Explain results using ELI5 for model interpretability.

───────────────────────────────────────────

5. NOTES

───────────────────────────────────────────


Internet connection may be required when using NeuroKit2 for the first time.
Ensure all dataset files are correctly placed inside the data/ folder.
If WFDB reading errors occur, check that the wfdb package is installed.
