# Netflix Movie Recommendation System

## 📋 Overview

This project is a Netflix Movie Recommendation System built using Python and various data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The goal of this project is to analyze the Netflix dataset and provide insights into the types of movies and TV shows available on Netflix. The dataset includes information such as show titles, directors, cast, release years, ratings, and more.

## Dataset

The dataset used in this project is named `netflix_titles.csv`. It contains the following columns:

- `show_id`: Unique ID for each show.
- `type`: Type of the show (Movie or TV Show).
- `title`: Title of the show.
- `director`: Director of the show.
- `cast`: Cast members of the show.
- `country`: Country where the show was produced.
- `date_added`: Date when the show was added to Netflix.
- `release_year`: Year the show was released.
- `rating`: Rating of the show.
- `duration`: Duration of the show (in minutes for movies, seasons for TV shows).
- `listed_in`: Categories the show is listed under.
- `description`: Brief description of the show.

## 🛠️  Project Structure

The project is structured as follows:

1. **Data Loading and Initial Exploration**:
   - Load the dataset using Pandas.
   - Display the first and last few rows of the dataset.
   - Check the shape, size, and data types of the dataset.

2. **Data Cleaning**:
   - Handle missing values in the dataset.
   - Check for duplicate entries and remove them if necessary.

3. **Data Analysis**:
   - Analyze the distribution of movies and TV shows.
   - Explore the most common release years.
   - Visualize the data using Matplotlib and Seaborn.

4. **Recommendation System**:
   - Implement a basic recommendation system based on user preferences.
   - Provide recommendations based on genres and ratings.

## 📚 Libraries Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For data visualization.
- **Seaborn**: For advanced data visualization.
- **Sklearn**: For the process of building machine learning models.

## How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/netflix-movie-recommendation.git
   cd netflix-movie-recommendation
