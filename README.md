# Spotify Streamed Songs Analysis

This repository contains a Python notebook that analyzes a dataset of the most streamed songs on Spotify. The dataset includes various attributes such as track names, artist(s), and detailed audio features.

## Project Overview

The goal of this project is to analyze the most streamed songs on Spotify, identify trends, and perform an exploratory data analysis (EDA) using Python. This notebook provides insights into popular songs, artist statistics, and various song features like liveness, speechiness, and more.

### Key Features

- **Data Cleaning**: Removes duplicates and handles missing values.
- **Exploratory Data Analysis (EDA)**: Provides statistical summaries and visualizations of the most popular songs and their features.
- **Song Attributes**: Analysis of song characteristics like key, liveness, and speechiness.
- **Visualizations**: Interactive plots to explore trends in Spotify’s most streamed songs.

## Dataset

The dataset consists of 953 songs with the following key attributes:

- `track_name`: Name of the song
- `artist(s)_name`: Name of the artist(s)
- `key`: Musical key of the song
- `liveness_%`: Liveness score of the track
- `speechiness_%`: Speechiness score of the track
- `cover_url`: URL of the song’s cover image
- ...and more (25 total columns)

## Installation

To run this project locally, you need the following libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

You can clone this repository and run the notebook in any Jupyter environment:

```bash
git clone https://github.com/username/Spotify-Streamed-Songs-Analysis.git
cd Spotify-Streamed-Songs-Analysis
```

Open the notebook:

```bash
jupyter notebook 0925_DA1.ipynb
```

## Usage

The notebook is structured as follows:

1. **Data Import & Cleaning**: Load the Spotify dataset, handle duplicates, and clean the data.
2. **Exploratory Data Analysis (EDA)**: Visualizations and statistical analyses of the dataset’s attributes.
3. **Insights & Observations**: Key takeaways from the analysis of Spotify's most streamed songs, including artist trends and song features.

## Contributing

Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, feel free to contact me via Github or Linkedin!!
