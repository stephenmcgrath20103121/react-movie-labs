# Assignment 1 - ReactJS app.

Name: Stephen McGrath

## Overview.

This repository contains a React web application that serves as a TMDB client. It allows users to browse movies across multiple pages and categories, such as upcoming, popular and top rated movies. Users can favourite a movie which is then shown in a separate view. Movies can be searched and filtered according to a number of options, such as its rating, genre and popularity. Selecting a movie shows further information and details about it. Recommended movies are shown on these pages, along with the movie's cast. An actor can be selected for further information about them, including the movies they star in. Users can write and add reviews on movies and see other's reviews. 

### Features.
 
+ View Top Rated Movies
+ View Popular Movies
+ Recommendations shown in Movie Details
+ Movie Cast shown in Movie Details
+ Actor Details can be accessed from a Movie's Cast
+ Movie List Pages have Pagination implemented
+ Filter by Rating
+ Filter by Popularity

## Setup requirements.

1. Clone the app repository
``` 
git clone https://github.com/stephenmcgrath20103121/react-movie-labs.git
cd react-movie-labs/movies
```

2. Ensure Node.js is installed locally
```
npm install
```

3. Provide API Key
Create movies/.env with the following information, replacing < YOUR-API-KEY > with your own API key
```
REACT_APP_TMDB_KEY=< YOUR-API-KEY >
FAST_REFRESH=false
```

4. Start the app
```
npm start
```

## API endpoints.

+ List of popular movies - movie/popular
+ List of top rated movies - movie/top_rated
+ Movie recommendations - movie/:id/recommendations
+ Actor details - person/:id
+ Movies actor starred in - person/:id/movie_credits
+ Images of actor - person/:id/images
+ List of actors in movie - movie/:id/credits

## Routing.

+ /movies/popular - displays popular movies.
+ /movies/top_rated - displays top rated movies.
+ /person/:id - displays details of a particular actor.

## Independent learning.

<https://developer.themoviedb.org/reference/intro/getting-started>
<https://mui.com/material-ui/getting-started/>