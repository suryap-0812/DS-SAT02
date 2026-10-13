# Machine Maintenance Insight — Use Case 25

This submission implements the requested Data Science assessment work starting at Round 2. Round 1 quiz is excluded.

## Contents
- `datasets/`: the five input CSV files required by the assignment:
  - `sensor.csv`
  - `machines.csv`
  - `usage.csv`
  - `alarms.csv`
  - `maintenance.csv`
- `Machine_Maintenance_EDA_Feature_Engineering.ipynb`: complete notebook. It reads the five CSVs; it does not generate datasets.
- `Machine_Maintenance_Business_Insights.pptx`: presentation with exactly 6 slides.
- `outputs/`: audit report, cleaned datasets, machine-day features, analysis summaries, feature-selection scores, selected feature matrix, and charts.

## Run the notebook
1. Extract the ZIP.
2. Open a terminal in the extracted `Machine_Maintenance_Complete_Submission` folder.
3. Install dependencies:
   `python -m pip install -r requirements.txt`
4. Start Jupyter:
   `jupyter notebook`
5. Open `Machine_Maintenance_EDA_Feature_Engineering.ipynb` and choose **Run All**.

The notebook expects the `datasets/` directory to be beside the notebook. Run Jupyter from the project root so relative paths resolve correctly.

## Scope and limitations
- The data is synthetic and included as separate CSV files.
- Sensor limits and warning scores are illustrative, not manufacturer safety thresholds or validated failure probabilities.
- The five source datasets do not contain a confirmed failure label. Feature selection therefore ranks features against an engineered warning score; it does not establish predictive failure accuracy.
- Load/downtime comparisons are descriptive, not causal.
