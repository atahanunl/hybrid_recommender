# Hybrid Recommender System

## Business Problem

The task is to make predictions for a user with a given ID using both user-based and item-based recommendation methods.
A total of 10 recommendations should be provided, with 5 coming from the user-based model and 5 from the item-based
model.

## Dataset Story

The dataset has been furnished by MovieLens, a movie recommendation service. It comprises movies accompanied by the
respective rating scores assigned to them. In total, the dataset incorporates 20,000,263 ratings spanning across 27,278
movies. The dataset was curated on October 17, 2016, capturing data from 138,493 users within the period from January 9,
1995, to March 31, 2015. The users were selected at random, and it is noted that each of the chosen users has provided
ratings for a minimum of 20 movies.

## Features

`movie.csv`

- `movieId` - Unique movie identifier
- `title` - Movie title
- `genres` - Genre

`rating.csv`

- `userid` - Unique user identifier
- `movieId` - Unique movie identifier
- `rating` - User-assigned rating for the film
- `timestamp` - Date of the rating