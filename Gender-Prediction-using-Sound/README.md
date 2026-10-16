# Gender prediction using sound

- **Goal:** infer the gender of children's-book authors from their first names to study representation in the NYT best-seller list.
- **Data:** `nytkids_yearly.csv` (NYT children's best sellers), `babynames_ssa.csv` (US Social Security baby names) and the phonetic index `babynames_nysiis.csv`.
- **Method:** NYSIIS phonetic encoding with the `fuzzy` library to match names that sound alike, then pandas aggregation and matplotlib plots by year.

Notebook: [`gender-prediction-using-sound.ipynb`](gender-prediction-using-sound.ipynb) · based on a DataCamp guided project.
