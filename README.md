# 📓 DS Practice Notebooks

A collection of Data Science practice notebooks covering various topics including machine learning, data analysis, and deep learning.

---

## 📁 Structure

| Folder | Description | Tools |
|--------|-------------|-------|
| [ASL-Recognition-with-Deep-Learning](./ASL-Recognition-with-Deep-Learning) | American Sign Language recognition using deep learning | Python, Keras |
| [Analyzing-TV-Data](./Analyzing-TV-Data) | Exploratory analysis of TV show data | Python, Pandas |
| [Clustering-Heart-Disease-Patients](./Clustering-Heart-Disease-Patients) | Unsupervised clustering of heart disease patient data | Python, Scikit-learn |
| [Exploring-the-Bitcoin-Cryptocurrency-Market](./Exploring-the-Bitcoin-Cryptocurrency-Market) | Analysis of Bitcoin and cryptocurrency market trends | Python, Pandas |
| [Gender-Prediction-using-Sound](./Gender-Prediction-using-Sound) | Predicting gender from name pronunciation | Python, Fuzzy matching |
| [Generating-Keywords-for-Google-Ads](./Generating-Keywords-for-Google-Ads) | Automatically generating keywords for ad campaigns | Python |
| [Give-Life-Predict-Blood-Donations](./Give-Life-Predict-Blood-Donations) | Predicting blood donation likelihood | Python, Scikit-learn |
| [Handwritten-Digit-Recognition](./Handwritten-Digit-Recognition) | Classifying handwritten digits using neural networks | Python, Keras |
| [Na-ve-Bees-Predict-Species-from-Images](./Na-ve-Bees-Predict-Species-from-Images) | Predicting bee species from images using ML | Python, Scikit-learn |
| [Network-Analysis-of-Game-of-Thrones](./Network-Analysis-of-Game-of-Thrones) | Network analysis of character relationships in GoT | Python, NetworkX |
| [Video-Topic-Extraction](./Video-Topic-Extraction) | Extracting topics from video content | Python, NLP |
| [Wrangling-and-Visualizing-Musical-Data](./Wrangling-and-Visualizing-Musical-Data) | Data wrangling and visualization of music datasets | Python, Matplotlib |

---

## ▶️ Run locally

```bash
git clone https://github.com/nada-hammamii/ds-practice-notebooks.git
cd ds-practice-notebooks
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

Each folder is self-contained: the notebook and the dataset it uses sit side by side, so any notebook can be opened and run on its own. Zipped image datasets (`ASL-Recognition-with-Deep-Learning/*.zip`, `Na-ve-Bees-Predict-Species-from-Images/images.zip`) are extracted by the notebook that uses them.

---

## 🛠️ Technologies Used

- **Python** — core language
- **Jupyter Notebook** — all projects
- **Pandas / NumPy** — data manipulation
- **Matplotlib / Seaborn** — data visualization
- **Scikit-learn** — machine learning 
- **Keras / TensorFlow** — deep learning (CNN, Sequential)
- **PyTorch / Torchvision** — deep learning (DataLoader, ToTensor)
- **TPOT** — automated machine learning
- **NetworkX** — network/graph analysis
- **NLTK / spaCy** — natural language processing
- **Gensim / pyLDAvis** — topic modeling (LDA)
- **WordCloud** — text visualization
- **Scikit-image (skimage)** — image processing
- **PIL (Pillow)** — image loading
- **Fuzzy** — phonetic matching
- **SymPy** — symbolic mathematics

