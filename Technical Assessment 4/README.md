# Rule-Based Reasoning (RBR) and Case-Based Reasoning (CBR) Systems

This project implements a Python-based intelligent system demonstrating Knowledge Representation (KR), a Rule-Based Reasoning (RBR) inference engine using IF-THEN logic, and a Case-Based Reasoning (CBR) system utilizing similarity matching and the 4R cycle.

## Files
- `TA4_Cruz.ipynb` - Python script containing the complete RBR and CBR implementations.
- `TA4_Cruz.pdf` - Documentation compiling python code, program outputs, and comparative reflections.

## RBR Steps Implemented
- **Knowledge Base Setup** - Organizing facts and categories using Python dictionaries.
- **Rule Definition** - Creating modularized functions using IF-THEN logical checks.
- **Inference Engine** - Looping through the rule base against working memory facts to output inferred actions.

## CBR Cycle Steps Implemented
- **Retrieve** - Matching current problem features against past cases using overlap similarity.
- **Reuse** - Fetching and applying the solution of the most similar past case.
- **Revise** - Providing options to manually adjust or keep the retrieved solution.
- **Retain** - Saving the newly solved case back into the case base.

## How to Run
1. Open Google Colab your preferred Python environment.
2. Copy and paste the code from `TA4_Cruz.py`.
3. Run the script to view the inferred RBR actions and interactive CBR cycle outputs.

## Author & Course Details
* **Student Name:** Krista Mari Emilia Cruz
* **Course:** CS0065 (Intelligent Systems)
* **Institution:** Far Eastern University (FEU) Alabang