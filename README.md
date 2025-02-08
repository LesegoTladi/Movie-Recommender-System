# EA Movie Recommendation

## Overview

This project is part of the EA Movie Recommendation competition. The goal is to develop a recommendation algorithm that accurately predicts how users will rate movies they haven’t seen yet. Recommender systems play a crucial role in helping individuals make informed choices about the content they engage with daily, both socially and economically.

## Objectives

- **Content-Based Filtering**: Use metadata and user preferences to recommend movies.
- **Collaborative Filtering**: Leverage user interaction data to recommend movies based on similar user profiles.
- **Scalability**: Optimize the model to handle large datasets efficiently, ensuring fast performance even with millions of records.

## Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Evaluation](#evaluation)
- [Contribution](#contribution)
- [License](#license)
- [Conclusion](#conclusion)

## Features

- **Hybrid Model**: Combines content-based filtering and collaborative filtering approaches.
- **Large-Scale Data**: Handles datasets with over 10 million records efficiently.
- **Optimized Libraries**: Utilizes libraries like `scikit-learn` and `dask` to ensure high performance and scalability.
- **Movie Metadata**: Uses detailed movie information, such as genre and IMDb links, to enhance recommendations.

## Dataset

The dataset includes the following components:

- **Movie Metadata**: Information about the movies, such as titles, genres, and descriptions.
- **User Ratings**: Data on how users have rated various movies.
- **Movie Tags**: Tags describing the movies, helping in content-based filtering.
- **IMDb Links**: Links to IMDb for additional movie-related information.

## Installation

To set up the environment, ensure you have the following libraries installed:

```bash
pip install numpy pandas scikit-learn dask

Usage
Run the Jupyter Notebook to preprocess data and train the recommendation model:

jupyter notebook movie_recommendation.ipynb
File Structure

/
|-- movie_recommendation.ipynb  # Main Notebook
|-- data/
    |-- train.csv  # Training dataset
    |-- test.csv   # Test dataset
    |-- movies.csv # Movie metadata
    |-- links.csv  # IMDb links
Evaluation
The model is evaluated based on prediction accuracy using metrics such as RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error).

Contribution
Feel free to contribute to the project by submitting pull requests, reporting issues, or suggesting improvements.

License
This project is licensed under the MIT License.

Conclusion
This project aims to provide an efficient and scalable movie recommendation system capable of handling large datasets. By combining content-based and collaborative filtering techniques, we can improve prediction accuracy and enhance the user experience, helping users discover movies that match their preferences.
