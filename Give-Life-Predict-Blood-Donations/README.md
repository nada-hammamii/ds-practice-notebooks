# Predict blood donations

- **Goal:** predict whether a donor will give blood again, to help a mobile blood-donation service plan its campaigns.
- **Data:** `transfusion.data` — the UCI blood transfusion dataset (recency, frequency, monetary volume, time since first donation, target).
- **Method:** train/test split, automated model search with TPOT, then a logistic regression with log-normalised features, compared on AUC.

Notebook: [`predict-blood-donations.ipynb`](predict-blood-donations.ipynb) · based on a DataCamp guided project.
