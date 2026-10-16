# Network analysis of Game of Thrones

- **Goal:** find the most important characters in *A Song of Ice and Fire* and see how their importance shifts across the five books.
- **Data:** `book1.csv` … `book5.csv` — character co-occurrence edges (two names within 15 words of each other), weighted by frequency.
- **Method:** NetworkX graphs per book; degree, betweenness and PageRank centralities, their correlation, and the evolution of key characters over time.

Notebook: [`network-analysis-game-of-thrones.ipynb`](network-analysis-game-of-thrones.ipynb) · based on a DataCamp guided project.
