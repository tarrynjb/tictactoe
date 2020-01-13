# Tic-Tac-Toe Project

### Gitpod Preview in Browser: python3 -m http.server 3000

## Overview:
In this unit, coders will create the classic game of tic tac toe in their browser! The user will input moves as player X or O on a tic tac toe board. When a player wins, the game will end and a message will display the winner.

## Day 1

#### Planning
- [ ] Complete the project planning document.
#### Set-Up
- [x] Go to the repository
- [ ] Fork this repository to your github account and clone to a new workspace
- [ ] Add, commit, and push your changes
- [ ] Make your site live on gh-pages
- [ ] Submit your website using the link on the Agenda

### JavaScript
- [X] Create a variable that keeps track of the current player and set it equal to either a string of "X" or "O"
- [X] Create a variable that keeps track of the total number of turns taken and set it equal to 0
- [X] Create a variable of a boolean type that will signal whether or not the game has ended and set it equal to false
- [ ] Implement behavior to place pieces on the board. Do this by creating a function called performLogic with parameters buttonId and tileId that removes the button of the corresponding buttonId, and changes the text of the div that is the tileId to the player variable.
- [ ] Implement behavior that will change the turns of the player. Do this by writing a function that will change the current player to either "X" or "O" depending on the current player. Decide where to put this function.
- [ ] Implement behavior that will change the title to "It's a draw!" and end the game by changing the boolean variable to true after 9 pieces are placed. Do this by writing a function that will add 1 to the current turns, and check if that counter has reached 9.

#### Wrap
- [ ] Push your changes!

## Day 2

## Project Extensions:
- [ ] Add in your own css to personalize your project
- [ ] Create a button that will reset the game back to the original (this requires clearing the Xs and Os, and putting the "move" buttons back)
- [ ] Keep track of the score between the two players: X wins, O wins, and draws
- [ ] Change the 9 button functions to instead be one generic function on the button selector
- [ ] Change the board to be 4x4 and end the game when there is a 4 in a row

## References/Tools
* [Advanced Reference Table](https://docs.google.com/document/d/1SElvLDvtVOoYZJyR5XbCQJWbSTxyChDiQkz7n3c63Go/preview)
* [How Jquery Works](http://learn.jquery.com/about-jquery/how-jquery-works/)
* [JQuery Events](http://api.jquery.com/category/events/)
