# 2Player1ColorOtrioSolver

I've been playing a lot of Otrio and kicking everyone's ass. My friend built a [RNN](https://en.wikipedia.org/wiki/Recurrent_neural_network) to play the game and trained it. I wanted to take a different approach at the game and this is my attempt at it. This is 2 player version where each player gets 1 color. This version of the game is solved and this is more of a practice for myself. This is going to generate like 4 billion game states and then all of the moves between them so it really needs to be somewhat efficient.

The final objective of the project is as follows.

1) Efficiently Generate all possible board states for the game.
2) Efficiently store all possible board states in a database (SQL Server or Postgres?)
3) Generate the moves that moves from board state to board state
4) Efficiently save the moves in a database
5) Save the moves and tables as nodes and edges in database as a cyclical? directed graph
6) Be able to take any board state and query to find the best move for the player that is up. Must take into account if player can not win then get moves that move towards a draw.
7) Get better a programming and learn?

