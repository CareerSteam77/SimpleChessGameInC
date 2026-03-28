# SimpleChessGameInC
Proiect Pentru SO2

Made in colaboration with Andor Marius and Avram Ana

A fully functional multiplayer chess system implemented in C. This project uses TCP Sockets for network communication and the NCurses library to render a graphical interface directly in the terminal.
The architecture follows a strict Client-Server model where the Server is the "Source of Truth", handling the game state and move validation, while the Clients act as the interface for the players.

# How To Play

Execute all the files using the command: make all After that, you need at least 3 terminals runing:

In the first one you will run the command: ./server

In the other two terminals you will run the command: ./client to be a player
