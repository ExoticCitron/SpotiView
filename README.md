# SpotiView
View the current song you're playing on spotify via console, if any

-------
Setting it up is pretty simple:
 - Fill out your spotify access token by visiting [here](https://developer.spotify.com/console/get-user-player/) and clicking 'GET TOKEN', sign in the copy your token and paste it.
 - Fill it out on the `SPOTIFY_ACCESS_TOKEN = ''` field on the main file, be careful to not show this to anyone else.
 - Your token is valuable as with any other api key, use it carefully.

---
When running the code, your current playing song will be shown on your console. Please do not that it will return a json object with the song information.

# Troubleshoot
Getting a `KeyError`?:
> Either your Oauth Spotify token is invalid [needs to be refreshed so get the token again] or you're not playing anything on spotify yet, so the error would be raised. To get your access token again, visit the link again https://developer.spotify.com/console/get-user-player/ and click `Get Token`
