# Wordle Game

This is a web-based implementation of the classic word-guessing game, Wordle, built using ReactJS. In this game, players are presented with a randomly generated five-letter word, and have six attempts to correctly guess the word by entering five-letter words.

## Getting Started

To play the game, simply visit the deployed web application [here](https://aydenjahola.github.io/Wordle). Alternatively, you can clone this repository and run the game locally on your machine.

### Prerequisites

To run the game locally, you will need to have [Node.js](https://nodejs.org/en/) and [yarn](https://yarnpkg.com/) installed on your machine.

### Installing

1. Clone this repository to your machine using the following command:

```sh
git clone git@github.com:aydenjahola/Wordle.git
```

2. Navigate into the cloned directory:

```sh
cd Wordle
```

3. Install the necessary dependencies using yarn:

```sh
yarn install
```

## Words

the words are stored in `src/wordle-bank.txt`, please feel free to add more words or change them. the app only checks if the words exists in that file.

please make sure that words dont already exist if you want to add more words.

### Running the Game

To run the game, simply run the following command from within the cloned directory:

```sh
yarn start
```

This will start the development server and launch the game in your default web browser.

## Contributing

We welcome contributions from anyone! To contribute to this project, please follow these steps:

1.  Fork this repository
2.  Create a new branch (git checkout -b new-feature)
3.  Make your changes and commit them (git commit -am 'Add new feature')
4.  Push to the branch (git push origin new-feature)
5.  Create a new pull request and describe your changes in detail

## How to Play

1. The game will generate a random five-letter word for the player to guess.

2. The player has six attempts to guess the word by entering a five-letter word into the input field and clicking the "ENTER" button.

3. After each guess, the game will display feedback indicating which letters in the player's guess are correct and in the correct position (marked with green), and which letters are correct but in the wrong position (marked with orange).

4. If the player correctly guesses the word within six attempts, they win the game. Otherwise, they lose.

## Built With

- ReactJS - The web framework used

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/aydenjahola/Wordle/blob/main/LICENSE) file for details.
