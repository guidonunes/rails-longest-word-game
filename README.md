# Longest Word Game

## Overview

This project is a Rails-based web application where users participate in a game of forming the longest valid word possible from a random set of letters. The challenge focuses on generating a random grid of letters, accepting user input, and calculating the score based on the word's validity and length. This game is designed to sharpen skills in Rails, form handling, and routing.

## Features

* Random Letter Grid: A new grid of 10 random letters is generated on every game.
* Word Submission Form: Users can type a word based on the provided letters and submit it to be scored.
* Score Calculation: The word is checked for validity, and points are awarded based on its length and whether it can be formed using the available letters.

## User Stories

* As a user, I want to start a new game with random letters so I can challenge myself to find a valid word.
* As a user, I want to submit a word based on the letters displayed to check if it is valid and score points.
* As a user, I want to see the result of my word (score and validation feedback) after submission.

## Stack

* Ruby on Rails: Backend framework for handling routing, form submissions, and game logic.
* HTML/CSS: Basic front-end layout for displaying the letter grid, form, and results.
* Bootstrap (optional): For styling the layout and enhancing the user interface.

## Future Enhancements

* Dictionary API: Implement a third-party API (like the Oxford Dictionaries API) to validate the user’s word against a real dictionary.
* Leaderboard: Add a scoring leaderboard to display the top scores from multiple users.
* Styling: Enhance the UI with additional CSS/Bootstrap for a more engaging experience.

## How to Run the Project

1. Clone the repository:
```
git clone https://github.com/yourusername/longest-word-game.git
cd longest-word-game
```

2. Install the dependencies:

```
bundle install
```

3. Run the Rails server:

```
rails server
```

Open the browser and navigate to http://localhost:3000/new to start playing the game.

