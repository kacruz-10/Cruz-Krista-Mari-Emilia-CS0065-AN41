# MACHINE PROBLEM 1: Early Warning Tool Using KNIME

This project uses KNIME Analytics Platform to build a machine learning model that predicts student risk status (`At Risk` or `Not At Risk`) based on academic performance data.

## Files
- `DemoEarlyWarningTool.knwf` - Exported KNIME workflow
- `student_performance_knime.csv` - Dataset used by the workflow
- `Surname_FirstName_KNIME_GitHub_Evidence.pdf` - Step-by-step evidence documentation

## Algorithms Compared
- Logistic Regression
- Decision Tree
- Random Forest

## How to Run
1. Import the `.knwf` file into KNIME Analytics Platform.
2. Configure the CSV Reader node to point to the included dataset (`student_performance_knime.csv`).
3. Execute all nodes in the workflow.
4. Open the Scorer nodes to review and compare evaluation metrics (Accuracy, Precision, Recall, F1-Score).

## Author & Course Details
* **Student Name:** Krista Mari Emilia Abraham Cruz
* **Course & Section:** CS0065 (Intelligent Systems)
* **Institution:** Far Eastern University (FEU) Alabang