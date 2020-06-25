# Android-Movie-Music-App
Demo app which will show Current and MostPopular movies

1.This coding app has following instructions :
List horizontally currently playing movies. 
API: https://api.themoviedb.org/3/movie/now_playing?language=en-US&page=undefined&api_key=55957fcf3ba81b137f8fc01ac5a31fb5
Only display poster images in the horizontal scrolling list view, No pagination necessary.

2. Display the most popular movies in the vertical list view, as this list will contain multiple pages, Pagination support will be required.
API: https://api.themoviedb.org/3/movie/popular?api_key=55957fcf3ba81b137f8fc01ac5a31fb5&language=en-US&page=1
Each list item will contain the following:
    Poster image
    Title
    Rating
    Duration
    Release date

3. When a user clicks on any movie list item, it will navigate to a detailed screen, with more information about the movie.
API: https://api.themoviedb.org/3/movie/ {MOVIE_ID}?api_key={YOUR_KEY}
Detail screen should contain the following information:
Poster image: use the API as per described https://developers.themoviedb.org/3/getting-started/images
    Duration
    Title
    Overview
    Release date
    List of genres


Android componenents used in this app Implementation :
- Verified Internet connection before making Api call and displayed toast message to connect network.
- Displayed progress dialog until background api call completes execution .
- Written and verified Espresso UI unit test cases .
- Display the most popular movies in the vertical list view and Current playing list in HorizontalScrollview
- Used Zip Observable to make the API calls of CurrentMovie and PopularMovie in a single attempt.
- Used Retrofit for backend Api calls.
- Designed and Implemented UI in such a way to fit in all size android devices.
- All code was properly separated and placed in different packages .
- Added debug logs tased to debug if any issues comes in future
- All dimensions placed dimensions.xml, colors in colors.xml , strings in strings.xml
- App minimum support version set to Android 5.0+.
- Restricted application to display in portrait mode only.
- Used Picasa third party libraries to render/display images with the URL
- Displayed rating progressView with color Green if rating > 5 other displayed with yellow color


