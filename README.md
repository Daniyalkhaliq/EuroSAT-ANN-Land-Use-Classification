# Satellite Land-Use Classification using an ANN

Individual project for Artificial Neural Networks, SZABIST.
Student: Daniyal Khaliq (23108295)

## Summary
A baseline ANN trained on raw pixels is compared with an ANN trained on
39 engineered features (color, brightness, edge/texture).

| Model | Test Accuracy |
|---|---|
| Baseline ANN (raw pixels) | 74.76% |
| Feature-engineered ANN | 96.31% |

## Dataset
EuroSAT (RGB), using 5 classes: AnnualCrop, Forest, Residential,
River, SeaLake (14,500 images). The images are not included in this
repository. Download EuroSAT from Kaggle and place the five class
folders in a folder named `eurosat_image` next to the notebook.

## How to run
1. Install the libraries: pip install -r requirements.txt
2. Put the dataset in `eurosat_image/` as described above.
3. Open the notebook and run all cells from top to bottom.

## Files
- EuroSAT_ANN_Project.ipynb: full code and outputs
- ANN Mid Project report.docx: project report
- report_figures/: charts used in the report
- baseline_model.keras, feature_model.keras, feature_scaler.pkl: saved trained models and scaler
