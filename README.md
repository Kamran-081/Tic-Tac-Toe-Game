**Tic Tac Toe Game**

A simple and interactive Tic Tac Toe web game built using HTML, CSS, and JavaScript. It allows two players to play on the same device with instant winner and draw detection.

**Features**

-Two-player gameplay (X vs O)

-Real-time winner detection

-Draw detection when board is full

-Reset Game and New Game functionality

-Clean and responsive UI

-Lightweight and fast (no external libraries)

**Technologies Used**

HTML – structure

CSS – styling

JavaScript – game logic

**Project Structure**
```
Tic Tac Toe/
│── index.html
│── style.css
│── app.js
```


**How to Play**

The game is played between two players:

Player 1 → O

Player 2 → X

Players take turns clicking on empty boxes.

*A player wins if they form:*

A row

A column

A diagonal

If all 9 boxes are filled and no player wins, the game ends in a draw.


**Game Logic**

Uses a boolean variable to switch turns between players

Stores all winning patterns in an array

Tracks total moves to detect draw

Disables boxes after a win or draw

Displays the result message dynamically



**Controls**

Reset Game → clears the board and restarts

New Game → starts a fresh game after result
