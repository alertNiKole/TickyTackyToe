# Tic Tac Toe Game

## Requirements Documentation

This is a game of Tic Tac Toe based on a challenge by Jane Phillips.
[Jane Phillps GitHub]("janephillps.github.io")

## Challenge:

Build a two player tic tac toe app where a game is played by alternating clicks until the game is won by X or O or is a tie.

## Description:

This is a game of Tic Tac Toe built on the normal functions of front end web development.  It will include the following:

    1. HTML
    2. CSS Grid
    3. JavaScript
    4. Maybe the canvas*
    5. Maybe built with Materialize*
    6. GitHub will be used for version control with commits frequently until complete.
    7. It will be developed mobile first.

### Javascript:

For JavaScript functionality will include 
- Objects,
- OOP
- For loops
- and "IF" statements

### Theme:

    X will be Green
    O will be Blue
    Grid inactive will be gray
    Grid current will be gold/yellow
    Grid Played will be the color of the player

### Fonts:

1.   Jura 
2.  Exo

## Gameplay:

### Players: 
This is a two player Tic Tac Toe game. The game can also be played solo vs the computer.
    - Player A
    - Computer
    - Player B

### Turns
The first player will be selected randomly and their "name" will be highlighted.

The active player will make their move and select a square.  

The square will become active and their avatar will move to the location from the starting position.

The next player will do the same once their name is active (if v. computer is selected the computer will go automatically.)

### Grid
Grid will be 9 squares, 3 up, 3 across

### Win

Winning requires obtaining 3 consecutive squares with your color.

        X   X   X
        X   X  
        X

Diagonal
Across
Down

### Loss 

If 9 turns have been taken and no player has acheived 3 in a row, then a loss will be declared

At 7 turns, a warning will alert in the message box


### Tie

TBD -- Holding off on the tie scenario until after creation.

A tie will be the players having the same number of plays with no clear winner.

Consider making a tie buster which randomly resets 2 blocks from the active grid.


## Reset
Reset will clear all moves and position the board back to its original state.

