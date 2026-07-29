# Movie Recommender System

## Overview

This project is a **Movie Recommender System** that processes data in a Jupyter Notebook and uses the processed data in a Python-based UI built with **Streamlit**. The recommendation system is based on **Cosine Similarity**, a technique commonly used to measure the similarity between two vectors (in this case, movie features). The workflow is split into two parts:

1. **Data Processing in Jupyter Notebook**: Data cleaning, processing, and model training are performed in the `MovieRecommender.ipynb`. Cosine similarity is used to calculate the similarity between movies based on their features. The results, including the recommendation model, are serialized into a binary file that the main program can load.
  
2. **User Interface using Streamlit**: The UI is developed using Streamlit (`app.py`), which provides an interactive interface where users can input their preferences and get movie recommendations.

You can access the live version of the project here: [Movie Recommender System]([https://movierecommendation-wgbzf6btctioktz9zj9rjv.streamlit.app/](https://movie-deploy-za23lmsb9v5udkypcrpmop.streamlit.app/))

