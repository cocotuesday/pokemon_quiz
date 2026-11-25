# Who's That Pokémon?

A small Mac-friendly Pokémon name quiz. Open `index.html` in Safari, Chrome, or Firefox. It loads the 1,025 Pokémon roster from PokéAPI and displays official-artwork sprites. An internet connection is needed.

For the ten-option version, open `multiple-choice.html` instead. Each question has a 15-second timer; points for a correct answer are the streak value (1, then 2, then 3, and so on) multiplied by the whole seconds remaining. It keeps an all-time top-ten leaderboard in this browser, separate from the typed-answer quiz.

## Rules

- Type the Pokémon's name and press Return or click **Guess**.
- Questions come in groups of five from each generation, cycling from Gen 1 through Gen 9 and then back to Gen 1.
- Close spellings are accepted; the quiz allows one typo for shorter names and up to two for longer names.
- In the typed-answer quiz, a correct answer reveals the Pokémon and earns the next number of points: 1, then 2, then 3, and so on.
- A wrong answer ends the run. Your score is the sum of the points earned in that run.
- The best score is saved in this browser on this Mac.

The requested [Pokémon Wiki list](https://pokemon.fandom.com/wiki/List_of_Pok%C3%A9mon) is linked in the app as the roster reference. Direct access to its image table was blocked while assembling the app, so live names and artwork are loaded from [PokéAPI](https://pokeapi.co/).
