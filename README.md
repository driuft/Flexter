# Unit 1 Project: Flixter

Flixter is an android app that lets users view a list of movies sourced from the The Movie Database API.

Submitted by: Aldo Socarras

Time spent: **4** hours spent in total

## User Stories

The following **required** functionality is completed:

- [X] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API
- [X] Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity
- [X] Allow video posts to be played in full-screen using the YouTubePlayerView

The following **optional** features are implemented:

- [X] Views should be responsive for both landscape/portrait mode
- [ ] Display a nice default placeholder graphic for each image during loading
- [X] Improve the user interface through styling and coloring
- [ ] For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed
- [ ] Implement a shared element transition when user clicks into the details of a movie
- [ ] Trailers for popular movies are played automatically when the movie is selected
  - [ ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately
  - [ ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played
- [ ] Apply the popular ButterKnife annotation library to reduce view boilerplate
- [ ] Add a rounded corners for the images using the Glide transformations

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/driuft/Flixter/blob/master/walkthrough.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [ScreenToGif](https://www.screentogif.com/).

## Notes

No outstanding issues found.

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Aldo Socarras]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
