# Liri-Bot
HW 10: Node JSLIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

### Demos 
Using the following command line inputs, data is written to terminal & saved to log.txt
`node liri.js concert-this`
`node liri.js concert-this guster`
![concert-this demo](concert-this.gif)

`node liri.js movie-this`
`node liri.js movie-this baby mama`
![movie-this demo](movie-this.gif)

`node liri.js spotify-this-song`
`node liri.js spotify-this-song toxic`
![spotify-this-song demo](spotify-this-song.gif)

`node liri.js do-what-it-says`
![do-what-it-says demo](do-what-it-says.gif)

### How to Run
This app uses several apis [Spotify, Bands in Town, & OMDB] to create a topic-specific search engine for music, concerts, and movies.  It is empolyed using node in the terminal. To run this search engine: download files, open terminal and navigate to the downloaded folder. Once inside the folder, type the following commands into the terminal to:
- search for concerts [by a specific musician] `node liri.js concert-this [artist name]`
- search for a movie by name `node liri.js movie-this [movie title]`
- search for songs `node liri.js spotify-this-song [song title]`

## Built With
* Node.js
* Spotify API
* Bandsintown API
* OMDB API
* Axios
* Moment.js
* DotEnv (to keep my unique api keys secret) 

## Versioning & Author
This is the only version and is maintained by me, [sabomade](https://github.com/sabomade).

## Acknowledgements
Built & completed as part of the UCB Coding Bootcamp, Homework 10: Node.js
