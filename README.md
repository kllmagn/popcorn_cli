# popcorn_cli
Thin "Popcorn Time" client

# Usage

Show list of avalible resolutions for the movie "Mr.Nobody":

`>popcorn movie tt0485947`

Initiate download by opening magnet-link in browser:

`>popcorn movie tt0485947 --resolution 1080p`

Show list of avalible resolutions for the first episode in first season of "Loki" series:

`>popcorn show tt9140554 --season 1 --episode 1`

Initiate download by opening magnet-link in browser:

`>popcorn show tt9140554 --season 1 --episode 1 --resolution 1080p`

Тоже самое, только видео будет с русской озвучкой:

`>popcorn show tt9140554 --season 1 --episode 1 --resolution 1080p --lang ru`

# How to find imdb id for movie/show 
tt0485947, tt9140554, etc

Google name of movie/show and add `imdb` to search request like `Rick and Morty imdb`. First link will lead to IMDB.com and you should follow it. 
You will see something like this in your url bar:

![Url](https://i.imgur.com/ZwFmLhW.png)

`tt2861424` part is what you need.