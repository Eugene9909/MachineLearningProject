================================================================================
README -  Machine Learning Project
================================================================================

STUDENT INFORMATION
-------------------
Course  : Integrated Machine Learning Systems
Date    : April 2026

================================================================================
PROJECT STRUCTURE
================================================================================

ML_Project/
│
├── Component_A.ipynb                          - RL & Ensemble Learning System
├── Component_B.ipynb                          - LLM & RAG System
├── South Africa Road Accidents Dataset - 2017.xlsx  - Traffic accident dataset
├── 01mfgh4v*.pdf (x15)                        - Hansard transcript PDFs
├── ML_Project_Report.pdf                      - Professional project report
└── README.txt                                 - This file

================================================================================
HOW TO RUN
================================================================================

STEP 1: Install dependencies
------------------------------
Open terminal or Anaconda Prompt and run:

    pip install pandas numpy matplotlib seaborn scikit-learn xgboost openpyxl
    pip install transformers sentence-transformers faiss-cpu torch pdfplumber

STEP 2: Place all files in one folder
--------------------------------------
Make sure the following are in the SAME folder:
- Component_A.ipynb
- Component_B.ipynb
- South Africa Road Accidents Dataset - 2017.xlsx
- All 15 Hansard PDF files

STEP 3: Open Jupyter Notebook
------------------------------
In terminal, navigate to the project folder and run:

    jupyter notebook

STEP 4: Run Component A
------------------------
1. Open Component_A.ipynb
2. Run all cells from top to bottom (Cell > Run All)
3. Expected runtime: 2-5 minutes

STEP 5: Run Component B
------------------------
1. Open Component_B.ipynb
2. Run all cells from top to bottom (Cell > Run All)
3. Expected runtime: 10-15 minutes (model download on first run: ~250MB)

================================================================================
PYTHON VERSION
================================================================================

Python 3.11 (Anaconda Distribution)

================================================================================
DEPENDENCIES
================================================================================

Package                 Version
----------------------  -------
pandas                  2.2.2
numpy                   1.26.4
matplotlib              3.9.2
seaborn                 latest
scikit-learn            1.5.1
xgboost                 latest
openpyxl                latest
transformers            5.6.2
sentence-transformers   5.4.1
faiss-cpu               1.13.2
torch                   2.11.0
pdfplumber              latest

================================================================================
EXPECTED RUNTIME
================================================================================

Component A : 2-5 minutes
Component B : 10-15 minutes (includes model loading)
              Note: First run downloads ~250MB of model weights.
              Subsequent runs are faster as models are cached.

================================================================================
HARDWARE REQUIREMENTS
================================================================================

Minimum:
- RAM    : 8 GB
- Storage: 2 GB free (for model cache)
- CPU    : Any modern multi-core processor
- GPU    : Not required (CPU inference used throughout)

Tested on:
- RAM    : 20 GB
- OS     : Windows 11
- CPU    : Intel/AMD (integrated graphics)

================================================================================
NOTES
================================================================================

- Internet connection required on first run to download transformer models.
- Widget display warnings in Jupyter are cosmetic and do not affect results.
- All random seeds are fixed (random_state=42) for reproducibility.
- Component B sentiment scores may vary slightly due to keyword heuristics.

================================================================================