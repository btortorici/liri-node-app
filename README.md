LIRI Bot
Assignment
Create a CLI App "LIRI" bot which stands for Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

Solution
The solution was to use "backend" technologies only. Node.js was used along with NPM (Node Package Manager) libraries in order to accomplish the tasks. There is no front end to this application, therefore this is no html page to publish.

Technologies
JavaScript, Node.js, Request library, Spotify API, dateFormat library, File system library.

movie-this
node liri.js movie-this '<movie name here>'

This will search the OMDB API for a movie name and show the following information in the terminal and to the log.txt file:

  * Title of the movie.
  * Year the movie came out.
  * IMDB Rating of the movie.
  * Rotten Tomatoes Rating of the movie.
  * Country where the movie was produced.
  * Language of the movie.
  * Plot of the movie.
  * Actors in the movie.