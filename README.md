---

# Movie Recommendation System 🎥🍿

## Overview
This project is a **Movie Recommendation System** built using **Scikit-learn** for content-based filtering. It recommends movies based on metadata similarity with **CountVectorization**, providing an interactive web UI using **Streamlit**. The trained model is serialized using **Pickle** for efficient use.

## Features
- Content-based recommendations
- **Streamlit** web interface for interactive user experience
- Model persistence with **Pickle**

## Technologies Used
- **Python**
- **Scikit-learn**
- **CountVectorizer**
- **Pickle**
- **Streamlit**
- **Pandas**

## Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/narendran-u/movie_prediction
   ```
2. Install dependencies:
   ```bash
   pip install scikit-learn pandas numpy streamlit
   ```

## Usage
1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Input a movie, and the system will suggest similar movies through the web interface.

---
