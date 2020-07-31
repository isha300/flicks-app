
# Flicks
Flicks is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flicks Part 2

### User Stories

- [x] Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] Allow video posts to be played in full-screen using the YouTubePlayerView
   - [x] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
   - [x] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.

### Video Walkthrough

<img src="https://media.giphy.com/media/ZBiE9Ttunu2H2pZptQ/giphy.gif" width=250><br>
<img src='https://media.giphy.com/media/j0v6Tty2AL78iDlJPZ/giphy.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

### Notes
Implementing the trailer to be played and working out how to display the popularity number for each movie were challenges encountered in developing this app. I used the YouTubePlayerView with an API key to show the trailer as well as a progress bar to indicate the popularity on a scale of 1-500.

## Open-source libraries used
- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## Flicks Part 1

### User Stories
- [x] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [x] Views should be responsive for both landscape/portrait mode.
   - [x] In portrait mode, the poster image, title, and movie overview is shown.
   - [x] In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

### Video Walkthrough

<img src="https://media.giphy.com/media/ZBiE9Ttunu2H2pZptQ/giphy.gif" width=250><br>

### Notes
Being able to insert and track Logcat messages as well as syncing the Gradle files after entering file dependencies were
some of the challenges encountered and overcome while building the app through trial-and-error and an in-depth exploration of CodePath resources. 
