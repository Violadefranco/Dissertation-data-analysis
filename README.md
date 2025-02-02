Regression Models

The models compare the following treatment groups:

Control vs. Treatment 1

Economic Growth Model: Agreement with "Immigrants can contribute to Italy’s economic growth"

National Duty Model: Agreement with "Assisting migrants is a national duty"

Control vs. Treatment 2

Economic Growth Model: Agreement with "Immigrants can contribute to Italy’s economic growth"

National Duty Model: Agreement with "Assisting migrants is a national duty"

Treatment 1 vs. Treatment 2

Economic Growth Model: Agreement with "Immigrants can contribute to Italy’s economic growth"

National Duty Model: Agreement with "Assisting migrants is a national duty"


Then, run the respective scripts:

python regression_model.py  # Control vs. Treatment 1
python regression_model_treatment2.py  # Control vs. Treatment 2
python regression_model_treatment1_vs_treatment2.py  # Treatment 1 vs. Treatment 2

Outputs

Each script provides:

Statistical summaries from statsmodels (R², coefficients, p-values, etc.)

Performance metrics from sklearn (Mean Squared Error, R²)

License

This project is for research purposes only.

