# Spotify Songs Recommender

A project combining Exploratory Data Analysis and Machine Learning on Spotify track data to understand which audio features most influence a song's popularity.
It includes a recommendation system that suggests songs similar to a user-selected track, based on musical characteristics and weighted feature importance.


Project Features

- Exploratory Data Analysis of audio features and popularity
- Machine Learning models to evaluate feature impact on popularity
- A KNN-based recommendation system:
  Suggests similar songs based on audio characteristics
  Favors popular and tracks near in time
  Returns a list of recommended songs for a selected input


Repository Structure and File	Description

spotify_EDA_ML_reccomender.ipynb	Full notebook with data exploration, ML modeling, and recommendation system + example output
spotify_reccomender.ipynb	Clean version with just the code needed to run the recommender system


Dataset

The dataset used is available on Kaggle:
🔗 Spotify Tracks Dataset – by maharshipandya


How to Use

Clone the repository or download the notebook.
Install required packages:
pip install pandas numpy matplotlib seaborn scikit-learn
Load the dataset (tracks.csv from Kaggle).
Run spotify_EDA_ML_reccomender.ipynb to see full analysis and recommendations in action.


Contributions

Suggestions, forks, and pull requests are welcome!
Feel free to open an issue if you’d like to discuss improvements or ideas.



