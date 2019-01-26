
# Flicks
Flicks is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flicks Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView
   - [x] (1pt) When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
   - [x] (1pt) Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.

#### BONUS
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [ ] Apply the popular ButterKnife annotation library to reduce view boilerplate. (1 point)
- [ ] Add a rounded corners for the images using the Glide transformations. (1 point)

### App Walkthrough GIF
<img src="https://media.giphy.com/media/NlGdHdxLn0k8YdMcdO/giphy.gif" width=250><br>

### Notes
Implementing the trailer to be played and working out how to display the popularity number for each movie were challenges encountered in developing this app. I used the YouTubePlayerView with an API key to show the trailer as well as a progress bar to indicate the popularity on a scale of 1-500.

## Open-source libraries used
- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## Flicks Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [x] (2pts) Views should be responsive for both landscape/portrait mode.
   - [x] (1pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [x] (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [ ] (2pts) Display a nice default [placeholder graphic](https://guides.codepath.com/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [ ] (2pts) Improved the user interface by experimenting with styling and coloring.
- [ ] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthrough GIF

<img src="https://media.giphy.com/media/woZepdqgGH3zFdQzDK/giphy.gif" width=250><br>

### Notes
Being able to insert and track Logcat messages as well as syncing the Gradle files after entering file dependencies were
some of the challenges encountered and overcome while building the app through trial-and-error and an in-depth exploration of CodePath resources. 
