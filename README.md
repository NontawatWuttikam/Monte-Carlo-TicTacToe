# Monte-Carlo-TicTacToe
Monte Carlo Simulated AI for playing against real player.

1. Create TicTacToe class

  - ox = TickTacToe()

2. You play as X. call move(location) to play your turn.

  - ox.move((0,0));

3. Call Display(); to show the current board state.

  - ox.display();

4. result of display() will be.
  - Probability Dic. Display all possible way for AI movement in that state. It will select the highest probability and move.
  - The board in current state.
  
{0: 0.666, 1: 1.0, 2: 0.314, 3: 0.6625}

[['X' '_' 'O']

 ['X' 'O' '_']
 
 ['O' '_' 'X']]
