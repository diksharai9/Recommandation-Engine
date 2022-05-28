# Movie- Recommendation Engine



[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 

This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc.
The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using `beautifulsoup4` and performed sentiment analysis on those reviews.

## How to run the project?

1. Clone this repository in your local system.
2. Install all the libraries mentioned in the [requirements.txt] file with the command `pip install -r requirements.txt`.
3. Replace YOUR_API_KEY in **both** the places (line no. 23 and 43) of `static/recommend.js` file.
4. Open your terminal/command prompt from your project directory and run the `main.py` file by executing the command `python main.py`, else run using the GUI.
5. Click on the link highlighted on your terminal, or open port 5000 else type http://127.0.0.1:5000/ in the browser.
6. There you go.



### Project Flow
- When you run the application on your localhost, you will be asked to enter a movie name.
- As soon as you start typing the movie name, some movies will name will be recommended, select one from them, if its there else type the whole movie name.
- Hit the search button and you will get all the details about the movie, including the star-cast, audience reviews and a lot more, below on the basis of your search query some movies will be recommended to you.
- The audience reviews have been scraped using beautiful soup4.
- The algorithm works on content-based filtering, so the movies recommended will have these similarities based on the tags, actors, genres, director so on and so forth.
- That's all, a simple demonstration of a movie recommendation system.




