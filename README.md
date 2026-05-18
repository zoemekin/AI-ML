# Beyond the Algorithm: A Multi-Perspective Machine Learning Study of Music

A machine learning project exploring whether Spotify audio features and textual metadata capture meaningful musical structure, and how this structure relates to genre, popularity, and latent musical groupings.

---

## Project Structure Overview

- **Block A — Music as Language (*21* by Adele)**  
  Text-based modeling and genre/popularity classification.

- **Block B — Music as Success (*Thriller* by Michael Jackson)**  
  Popularity prediction using audio, text, and combined features.

- **Block C — Music Beyond Genre Labels (*El Madrileño* by C. Tangana)**  
  Clustering and dimensionality reduction to study overlapping genre structure.

The project includes:
- classification models,
- NLP representations,
- PCA visualizations,
- clustering analysis,
- SHAP interpretation,
- and recommendation-oriented analysis.

---

# Key Features

- TF-IDF and sentence embedding representations for textual music metadata
- Genre classification using Logistic Regression and neural networks
- Popularity prediction using audio, text, and combined features
- Clustering analysis using K-Means, GMM, and DBSCAN
- PCA-based dimensionality reduction and visualization
- SHAP and Partial Dependence analysis for model interpretability
- Comparative evaluation across multiple ML paradigms
- Strong focus on interpretation and representation learning rather than pure prediction accuracy

---

# Repository Structure

```text
spotify_modelled.ipynb     # Main project notebook
spotify_songs.csv          # Dataset used throughout the analysis
README.md                  # Project documentation
```

---

# Dataset

Dataset source:

https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs

The dataset is already included in this repository as:

```text
spotify_songs.csv
```

---

# Installation & Running Instructions

## 1. Clone the repository

## 2. Launch Jupyter Notebook

## 3. Run the project

---

# Tech Stack / Dependencies

Main libraries and frameworks used:

- Python 3.13
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy
- sentence-transformers
- transformers
- torch
- shap
- Jupyter Notebook

External resources:
- Kaggle Spotify Songs Dataset
- Hugging Face Transformers ecosystem

---

# Notes on Reproducibility

Some embedding-based experiments rely on external NLP libraries such as:
- sentence-transformers
- transformers
- PyTorch

Due to package compatibility differences across systems and Python environments, some embedding outputs shown in the notebook were preserved from the original execution environment to ensure reproducibility of the reported results.

---

# Main Findings

- Genre is highly learnable from textual metadata.
- TF-IDF representations strongly captured genre-related lexical patterns.
- Popularity prediction remained substantially more difficult than genre prediction.
- Textual/contextual metadata outperformed audio-only features for popularity prediction.
- Modern music genres overlap heavily rather than forming perfectly separated clusters.
- Commercial success appears only partially explainable through Spotify features alone.

---

# Contributing Guidelines

This repository was developed as part of an academic machine learning project.

If contributing:
- keep notebook structure consistent,
- clearly document any new experiments,
- avoid modifying original outputs without explanation,
- preserve interpretability-focused analysis,
- and ensure any added code cells are reproducible.

---

# License

This repository is intended for educational and academic purposes only.

Dataset rights belong to the original Kaggle dataset creator.

---

# Credits

Project developed using:
- AI and Machine Learning Foundations lecture materials by Matteo Turilli
- *The Hundred-Page Machine Learning Book* by Andriy Burkov
- scikit-learn documentation
- Hugging Face Transformers documentation
- Kaggle Spotify Songs Dataset

Additional debugging and experimentation support during development was provided through the use of Claude large language models.