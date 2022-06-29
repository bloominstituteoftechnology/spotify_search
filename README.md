# spotify_search

Startup Instructions

1) Clone the repository abd change directories to the outer project folder 

`cd spotify_search`

2) Ensure that all dependencies are properly installed:

 `pipenv install`
 
3) Activate the virtual enviroment with:

`pipenv shell`

4) Change directories to `spotify_app`:

 `cd spotify_app`

5) Start up the Flask app.

`FLASK_APP=app.py flask run`

The FLASK_APP environment variable **can** be indicated in the .env file, but we have chosen **not** to do that for this app so that the student's actions in starting up the app will better match the process they will be following on the Sprint Challenge.

6) Contrary to best practices, this solution app *does* include a `.env` file with active API Keys. This is to make it easier for the instructor to show the learners working version of the app. Learners will need to create their own `.env` file and obtain [API keys from Spotify.](https://developer.spotify.com/dashboard/login)  

