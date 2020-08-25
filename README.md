# **I'mBored**
## **Welcome to I'mBored Github Page!**

This app is an API Capstone project for the Thinkful.com bootcamp that I'm currently enrolled in.  
[I'mBored](https://armelwl1951.github.io/ImBored-Capstone/)

## **What is I'mBored?**

I'mBored is a random movie search engine that allows the user to input a variety of search preferences in order to find a movie that fits what the user is interested in watching.  The app uses two API services: TMDB & Utelly in order to obtain the random movie selection through a two-step process.

1.  First sending the search-form-request through TMDB, a movie-information resource, that can be searched using almost any parameter.  This request then gets the results from TMDB, numbers the total pages, and then obtains a random page number to choose for the results.  The results and information from TMDB are displayed on the screen.

2.  Using the TMDB ID for the resulting movie, the ID is ran through Utelly in order to see if the resulting movie is streaming on any networks, such as: AmazonPrimeVideo, Netflix, Hulu, etc.
If a result comes back, then links to the movies stream is listed.

![home screen](CapstoneScreenshots/HomePage.jfif)
![search results](CapstoneScreenshots/SearchResults.jfif)

## Built With

* HTML
* CSS
* JavaScript
* jQuery

## Sources
* [TMDB](https://www.themoviedb.org/documentation/api)
* [Utelly](https://rapidapi.com/utelly/api/utelly)

### Future Changes and Current Errors
Unfortunately my app is far from perfect.  There are a few things that in the future, hopefully after my experience increases and I become more skilled in this field, I hope to improve upon.

1. There is an error that pops up every so often with search results in regards to an undefined length.  I've tracked this error down to an issue within the API databases, as it seems to apply to forgein movies, B-movies, etc. As this error only occurs from a select source of movie results, regardless of the search input, and doesn't impact the results I have come to assume that it isn't a fault in my code.  

2. Some of the movie results don't have a resulting streaming service showcasing them and in the future I would like to fix the search algorithm to only fetch movie results that have a stream service.  I've tried to input an if/else response for the movies without a stream service, however, I can't get it to work at all.

3. And finally, the look of the app.  I spent so much time writing the code to get both API services to work, to get the search function to work, etc. I spent almost no time on the UX.  The resulting app is clean, simple, and minimalistic.  I'm happy that it works and isn't terrible to look at.  However, in the future I would definitely spend more time giving the app a much cleaner and professional appearance.
