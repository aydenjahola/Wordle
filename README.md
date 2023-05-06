# Wordle Game

This is a web-based implementation of the classic word-guessing game, Wordle, built using ReactJS. In this game, players are presented with a randomly generated five-letter word, and have six attempts to correctly guess the word by entering five-letter words.

## Getting Started

To play the game, simply visit the deployed web application [here](https://example.com/wordle-game). Alternatively, you can clone this repository and run the game locally on your machine.

### Prerequisites

To run the game locally, you will need to have [Node.js](https://nodejs.org/en/) and [yarn](https://yarnpkg.com/) installed on your machine.

### Installing

1. Clone this repository to your machine using the following command:

```
git clone https://github.com/example/wordle-game.git
```

2. Navigate into the cloned directory:

```
cd wordle-game
```

3. Install the necessary dependencies using yarn:

```
yarn install
```

### Running the Game

To run the game, simply run the following command from within the cloned directory:

```
yarn start
```

This will start the development server and launch the game in your default web browser.

## How to Play

1. The game will generate a random five-letter word for the player to guess.

2. The player has six attempts to guess the word by entering a five-letter word into the input field and clicking the "Guess" button.

3. After each guess, the game will display feedback indicating which letters in the player's guess are correct and in the correct position (marked with a black dot), and which letters are correct but in the wrong position (marked with a white dot).

4. If the player correctly guesses the word within six attempts, they win the game. Otherwise, they lose.

## Built With

- ReactJS - The web framework used

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
