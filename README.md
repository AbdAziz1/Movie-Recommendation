# Movie-Recommendation
#### A movie recommendation system built using Python, Streamlit, and machine learning techniques like cosine similarity. This project helps users discover new movies similar to their favorites based on their descriptions, genres, cast, and crew.

## Introduction
#### The Movie Recommendation System is a Streamlit web application that leverages machine learning to suggest similar movies to users based on their selected preferences. It utilizes a dataset of movies, including information such as titles, overviews, genres, cast, and crew. The system employs cosine similarity to calculate the similarity between movies and recommends the top 5 closest matches.

## Features
### 
* User-Friendly Interface: Simple dropdown menu for selecting a movie and a button to trigger recommendations.
* Visual Representation: Displays recommended movies along with their posters for a visually appealing experience.
* Customizable: Users can easily extend the system by adding more features or integrating additional data sources.

## Demo
## Setup

1. Clone the repository:
```bash
git clone https://github.com/AbdAziz1/Movie-Recommendation.git
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Obtain API key:
* Register on The Movie Database (TMDb) to get an API key.
* Replace 'YOUR_API_KEY' in fetch_poster() function with your actual API key.

## Usage
1. Run the Streamlit app:
```bash
streamlit run app.py
```
2. Open the URL displayed in the terminal in your web browser.
3. Select a movie from the dropdown menu and click the "Recommend" button to get suggestions.

## Technologies
* Python
* Streamlit
* Pandas
* Requests
* Scikit-learn

## Dataset
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

## Contributing
#### Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or new features you'd like to see.





