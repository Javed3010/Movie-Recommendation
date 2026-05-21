# Movie Recommendation System

A Machine Learning project that recommends movies to users based on similarity, preferences, and movie features. This project demonstrates recommendation system concepts such as content-based filtering, similarity calculation, and movie suggestion generation.

---

## Project Overview

The goal of this project is to build a movie recommendation system that suggests similar movies based on user-selected input. By analyzing movie metadata such as genres, cast, keywords, and overview, the system recommends movies that are most relevant to the selected movie.

This project covers:

- Data Cleaning & Preprocessing
- Feature Engineering
- Text Processing
- Similarity Calculation
- Movie Recommendation Generation

---

## Features

- Recommends similar movies based on selected movie
- Uses content-based recommendation techniques
- Processes movie metadata for better suggestions
- Calculates similarity between movies
- Beginner-friendly machine learning project

---

## Tech Stack

### Languages & Tools

- Python
- Jupyter Notebook

### Libraries Used

- Pandas
- NumPy
- Scikit-learn
- NLTK / NLP tools
- Pickle

---

## Project Structure

```bash
Movie-Recommendation/
│
├── data/                     # Dataset files
├── notebooks/                # Jupyter notebooks
├── models/                   # Saved model/vector files
├── app.py                    # Main application file
├── requirements.txt          # Dependencies
└── README.md                 # Project documentation
```

---

## Recommendation Workflow

### 1. Data Collection

Collected movie-related datasets containing features such as:

- Movie title
- Genres
- Cast
- Crew
- Keywords
- Overview

### 2. Data Preprocessing

- Removed missing values
- Cleaned text data
- Converted JSON-like columns into readable format
- Combined important features into a single column

### 3. Feature Engineering

Created meaningful tags using movie metadata such as:

- Genres
- Cast
- Director
- Keywords
- Overview

### 4. Text Vectorization

Converted text data into numerical vectors using:

- Count Vectorizer
- Bag of Words

### 5. Similarity Calculation

Calculated similarity between movies using:

- Cosine Similarity

### 6. Recommendation Generation

When a movie is selected, the system returns the most similar movies based on calculated similarity scores.

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Javed3010/Movie-Recommendation.git
cd Movie-Recommendation
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Project

### Using Python Script

```bash
python app.py
```

### Using Jupyter Notebook

```bash
jupyter notebook
```

---

## Sample Output

```bash
Input Movie:
Avatar

Recommended Movies:
1. Guardians of the Galaxy
2. Star Trek
3. John Carter
4. The Avengers
5. The Fifth Element
```

---

## Future Improvements

- Add Streamlit or Flask web interface
- Include movie posters using TMDB API
- Add collaborative filtering
- Improve recommendations using hybrid filtering
- Deploy the project on Render / Heroku / Streamlit Cloud
- Add user login and personalized recommendations

---

## Contributing

Contributions are welcome.

1. Fork the repository  
2. Create a new branch  
3. Commit your changes  
4. Push to the branch  
5. Open a Pull Request  

---

## License

This project is licensed under the MIT License.

---

## Author

Mohamed Javed Khan

- GitHub: https://github.com/Javed3010  
- Project Repository: https://github.com/Javed3010/Movie-Recommendation  

---
