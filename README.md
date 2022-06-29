# spotify_search

Startup Instructions

1) Clone the repository and then run:

 `pipenv install`
 
To make sure that all of the dependencies are installed correctly.
 
2) Activate the virtual enviroment with:

`pipenv shell`

3) Change directories to `spotify_app`:

 `cd spotify_app`

4) Start up the Flask app.

`FLASK_APP=app.py flask run`

5) Contrary to best practices, this solution app *does* include a `.env` file with active API Keys. This is to make it easier for the instructor to show the learners working version of the app. Learners will need to create their own `.env` file and obtain [API keys from Spotify.](https://developer.spotify.com/dashboard/login)  

