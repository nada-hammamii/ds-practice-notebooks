# Naïve Bees: predict species from images

- **Goal:** tell honey bees from bumble bees in photos.
- **Data:** `images.zip` (bee photos) and `labels.csv` (species per image).
- **Method:** classic computer vision — HOG features and colour histograms with scikit-image, scaling and PCA, then an SVM classifier evaluated with accuracy and ROC AUC.

Notebook: [`naive-bees-predict-species.ipynb`](naive-bees-predict-species.ipynb) · based on a DataCamp guided project.
