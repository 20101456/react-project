# Assignment 1 - ReactJS app.

Name: Jeremiah Casey

## Overview.

This repository contains a React Movie Application.

### Features.
 
+ Popular movies page (Static endpoint).
+ Now Playing movies page (Static endpoint).
+ Recommended Movies list added to Movie Details page ( Parameterised endpoint).
+ Toggle Dark/Light mode button added to Site Header.
+ Caching with react-query is done on all static and parameterised endpoints

## Setup requirements.

No non-standard setup steps necessary to run this app locally after cloning the repo.

## API endpoints.

+ Popular movies page - movie/popular
+ Now Playing movies page - movie/now_playing
+ Recommended Movies list - movie/${id}/recommendations

## Routing.

+ /movies/popular - displays all popular movies.
+ /movies/now_playing - displays all now playing movies.

## Independent learning (If relevant).

+ Toggle Dark/Light mode button added to Site Header.
  - ThemeContext.js (Took inspiration from moviesContext.js   
    implementation).
  - https://semaphoreci.com/blog/dark-mode-reactjs-material-ui
  - https://stackoverflow.com/questions/68382679/toggling-between-dark-light-mode-material-ui
  - https://surajsharma.net/blog/react-material-ui-dark-mode

