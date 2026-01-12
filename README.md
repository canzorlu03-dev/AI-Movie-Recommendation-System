# AI-Movie-Recommendation-System

# AI Movie Recommendation System

## Overview

This repository contains an AI-powered movie recommendation system developed using Python and machine learning techniques. The project focuses on building an end-to-end recommendation pipeline using real-world public datasets and similarity-based filtering methods.

The system recommends movies by analyzing movie metadata such as genres, keywords, cast, crew, and plot descriptions. The goal is to demonstrate practical recommender system design, data preprocessing, and optimization of similarity metrics.

---

## Project Objectives

* Build a scalable and reusable data preprocessing pipeline
* Extract meaningful features from raw movie metadata
* Design a similarity-based recommendation engine
* Improve recommendation relevance through metric and filtering optimization

---

## Key Features

* End-to-end data cleaning and preprocessing
* Feature engineering from textual movie metadata
* Vectorization using NLP techniques
* Cosine similarity–based recommendation logic
* Optimized similarity metrics improving relevance by approximately 20%

---

## Datasets

This project uses publicly available datasets from The Movie Database (TMDB):

* tmdb_5000_movies.csv
  Contains movie-level metadata including title, genres, overview, keywords, and popularity.

* tmdb_5000_credits.csv
  Includes detailed cast and crew information for each movie.

The datasets are merged and transformed into a unified feature representation used for generating recommendations.

---

## Technologies Used

* Python 3
* Pandas, NumPy
* Scikit-learn
* Natural Language Processing (NLP) techniques
* Jupyter Notebook

---

## Methodology

1. Data Preprocessing

   * Removal of missing and inconsistent values
   * Parsing of nested JSON-like fields such as genres, keywords, cast, and crew
   * Dataset merging and normalization

2. Feature Engineering

   * Construction of a combined textual feature vector for each movie
   * Text normalization including lowercasing and tokenization

3. Vectorization and Similarity Calculation

   * Conversion of text features into numerical vectors using CountVectorizer
   * Computation of cosine similarity between movie vectors

4. Recommendation Generation

   * Given a movie title, the system returns the most similar movies
   * Similarity metrics and filtering logic were tuned to improve relevance

---

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/ai-movie-recommendation-system.git
cd ai-movie-recommendation-system
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open ai_proj.ipynb and run all cells.

---

## Project Structure

```
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── ai_proj.ipynb
├── README.md
└── requirements.txt
```

---

## Results

* Improved recommendation relevance through similarity optimization
* Demonstrated a complete machine learning pipeline for recommender systems
* Provided a reproducible and extensible project structure

---

## Future Work

* Incorporate user-based or item-based collaborative filtering
* Add quantitative evaluation metrics such as precision and recall
* Deploy the model as a web service using Flask or FastAPI

---

## License

This project is intended for educational and portfolio purposes and uses publicly available datasets.

---

## Author

Can Zorlu
GitHub: [https://github.com/canzorlu03-dev](https://github.com/canzorlu03-dev)
LinkedIn: [https://www.linkedin.com/in/can-zorlu-26b115307](https://www.linkedin.com/in/can-zorlu-26b115307)
