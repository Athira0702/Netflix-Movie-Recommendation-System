# Netflix-Movie-Recommendation-System

## Overview

This project implements a content-based recommendation system for Netflix movies. The system suggests movies similar to a given input based on textual features such as movie descriptions, genres, cast and directors.

## Features

- Content-based recommendation using text data .
- TF-IDF text vectorization for feature extraction.
- Cosine similarity for calculating movie similarities.
- Easily customizable for different datasets and additional features.

## Data
The dataset used for this recommendation system includes information about Netflix movies. It consists of the following columns:

- show_id: A unique identifier for each show or movie.

- type: The type of content, either "Movie" or "TV Show."

- title: The title of the movie or TV show.

- director: The director of the movie or TV show.

- cast: The cast or actors in the movie or TV show.

- country: The country where the movie or TV show was produced or is associated with.

- date_added: The date when the content was added to the streaming platform, in the format "Month Day, Year."

- release_year: The year the movie or TV show was originally released.

- rating: The content's rating, which indicates the recommended audience age or maturity level (e.g., "PG-13" or "TV-MA").

- duration: The duration of the movie or TV show. 

- listed_in: The genre or category of the content (e.g., "Documentaries," "International TV Shows," "Crime TV Shows").

- description: A brief description or synopsis of the movie or TV show, providing an overview of the plot or subject matter.
