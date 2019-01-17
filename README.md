## Liri-Bot Overview

LIRI is like SIRI.

Liri-bot is a node application that takes a set of command and use API to get and display what is found. LIRI will display

from Spofity API:

command: $node liri.js spotify-this-song '<song name here>'

 *Artist(s)
 *The song's name
 *A preview link of the song from Spotify 
 *The album that the song is from 
If no song is provided then your program will default to "The Sign" by Ace of Base.

from OMDb API (The Open Movie Database):

command: node liri.js movie-this '<movie name here>'

 * Title of the movie.
 * Year the movie came out.
 * IMDB Rating of the movie.
 * Rotten Tomatoes Rating of the movie.
 * Country where the movie was produced.
 * Language of the movie.
 * Plot of the movie.
 * Actors in the movie.
Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.

command: node liri.js do-what-it-says

    *It runs spotify-this-song for "I Want it That Way," as follows the text in random.txt.
Liri also keep log of the output in log.txt.

