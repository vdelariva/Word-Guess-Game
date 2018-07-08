# Word Guess Game

Word Guess Game is a simple version of a hangman style game. The purpose of this assignment was to create a word guess game using Javascript.

Link to [game](https://vdelariva.github.io/Word-Guess-Game/)

**How to Play:**

Press any Alpha key (A-Z, a-z) to start game. Non alpha keys are ignored. The theme of the game is 'World Cities'. The game will randomly select a world city form its internal list. It will then display a blank word using underscores to represent the letters in the word. It is possible to have a multi-word city such as Los Angeles.

If a correct letter is guessed, the game will reveal the letter in its correct location. If an incorrect letter is selected, then it will add the letter to a list on incorrectly guessed letters and decrement the remaining guesses count.

If the user guesses the correct city name before remaining guesses equal zero, then the game increments the number of wins and restarts the game by selecting a new random city name and reseting the game parameters.

If the user does not guess the correct city name within the allocated number of guesses, then the game resets.

**Assets used:**

Background image from https://www.nasa.gov/feature/goddard/2017/new-night-lights-maps-open-up-possible-real-time-applications

Sounds: https://notificationsounds.com Creative Commons Public License

**Side notes:**

I spent some time trying to get a modal to work when either the user guessed the correct city or ran out of guesses. I was able to get something partially working, but I wasn't happy with its implementation and chose not to include it in the final version. I also didn't spend much time enhancing the website with more CSS. My thought was to enhance its functionality using more Javascript functions (i.e. modals for 'You Win' or 'You Lose'), but went down a rabbit hole and wasn't happy with the result (as already stated above). As I gain more experience, I would like to revisit this exercise and improve both the JS functions (I'm sure there is a more effecient and elegant way to code the game) and the styling (like incorporating the letter buttons that were used in the Fridge class example and other fancy elements.)
