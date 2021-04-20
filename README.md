# MovieFlix
It is an Movie recommendation System which works on content base filtering with sentimental analysis of the reviews, recommends movies similar to the movies the user likes and analyses the sentiments on the reviews given by the user for that movie.

This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc.

All the details of the movies such as Titles, genre, runtime, rating, poster, etc are fetched using an API by **TMDB**.

The reviews given by the user is brought from IMDB by web scraping the IMDB site and sentiment analysis is performed on those reviews.

## How to get your own the API key?

- Create an account on TMDB, https://www.themoviedb.org/ .
- Go to your account settings.
- From the left hand sidebar select API.
- Create your own API by filling up the details.
- After completing You'll see your API in the API menu

Python Version : 3.8

## How to execute the project?

1. Clone this repository in your local system.
3. Install all the libraries mentioned in the [requirements.txt](https://github.com/kishan0725/The-Movie-Cinema/blob/master/requirements.txt) file with command `pip install -r requirements.txt` .
4. Replace YOUR_API_KEY in **both** the places (line no. 23 and 43) of `static/recommend.js` file.
5. Open your terminal/command prompt from your project directory and run the `main.py` file by executing the command `python main.py`.
6. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
7. Hurray! That's it.
  
  **Note**: Before running open **"The Movies Dataset"** link below and download **"Credits.csv"** and **"Movies_metadata.csv"** file and copy to the folder wherever you saved the repository in your system.
  
Because GitHub doesn't allow file larger than 25 Mb to be uploaded.
 
### Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_20

Please do ⭐ the repository, if it helped you in anyway.

