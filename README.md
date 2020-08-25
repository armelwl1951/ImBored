## **Welcome to I'mBored Github Page!**

This app is an API Capstone project for the Thinkful.com bootcamp that I'm currently enrolled in.  

### **What is I'mBored?**

I'mBored is a random movie search engine that allows the user to input a variety of search preferences in order to find a movie that fits what the user is interested in watching.  The app uses two API services: TMDB & Utelly in order to obtain the random movie selection through a two-step process.

1.  First sending the search-form-request through TMDB, a movie-information resource, that can be searched using almost any parameter.  This request then gets the results from TMDB, numbers the total pages, and then obtains a random page number to choose for the results.  The results and information from TMDB are displayed on the screen.

2.  Using the TMDB ID for the resulting movie, the ID is ran through Utelly in order to see if the resulting movie is streaming on any networks, such as: AmazonPrimeVideo, Netflix, Hulu, etc.
If a result comes back, then links to the movies stream is listed.

## Built With

* HTML
* CSS
* JavaScript
* jQuery

## Sources
* [TMDB](https://www.themoviedb.org/documentation/api)
* [Utelly](https://rapidapi.com/utelly/api/utelly)
