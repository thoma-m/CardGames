# CardGames

The cardGames is the first project in .net programming at Epitech. This project consists of create a games with multiples players.

This project is realized in C#.

## Details

In this project we created a server and a client that communicates with each other. 

We implemented a game like a battle but with more rules and specificity. To exemple, in this game a client play with a team mate to win the game.

## The Game

In this game, they are 2 teams of 2 players. At every handle, the team who posed the best card win. Every players have 8 card in her hand and the game finish when all the card are played.

## Commands

* The start
  
    At the beginning, the client must choose a name for the game and after he must enter the URL of the server he wants to join.

    When 4 players are connected, the game start and the teams are created

* The Games

    The game it's a **turn-based game**. The players play in the reverse order of the clock.

    They see they see their hands at their turn and he **must** select card in this form:  **Value Color**
    
    To exemple:  *King Pike* or *9 Heart*

    If they fails their commands, a message is print and he must re-select their card.

* The End
    
    The game is finish when a team win all the handle.
    
    The players can also leave the game anytime if they enter **exit** in the terminal.


## Contributors

DESEINE Clément

THOMAS  Maxime
