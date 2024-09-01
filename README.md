# AI for the Game of Amazons

The Game of the Amazons is a two-player strategy board game invented by Walter Zamkauskas in 1988. This game is played on a 10x10 square board with 100 squares, and every player starts with four Amazons (Black or White queen pieces in Chess) that are placed in the corners of the board. The objective of the game is to be the last player with a legal move. A legal move involves moving an Amazon in a straight line (horizontally, vertically, or diagonally), and stopping before a square that is blocked or is occupied by another Amazon. After the move, the player fires an arrow to block a square in a straight line from the arrow's landing position to the edge of the board or a blocked square. The player cannot move through a blocked square or Amazon. If a player cannot make a legal move, then they lose the game. This strategy game requires careful strategic thinking to control the board and they must choose their moves and arrow shots wisely in order to avoid getting trapped and losing their ability to make a legal move.


# OUR GOAL 
We decided to implement the AI bot in the Game of Amazon with a minimax search and
Alpha-Beta pruning to improve its decision-making capability for choosing the best move.
The bot infers the current state of the board and tries to predict moves that would put our
opponent at a disadvantage while, at the same time, benefiting our side. It does this by
simulating possible board states from legal moves from a given position and then evaluating a
heuristic score of this position.. Since the complete number of moves when analyzing a single
state of the game board can be a large number, we use Alpha-Beta pruning to reduce the
number of suboptimal branches that our algorithm searches when analyzing the game tree of
moves. Our bot will attempt to place arrows and produce and move the amazons in such a
way as to force the enemy’s play space down to a single or few deadly spots, anticipating any
moves the enemy bot might make and responding to them.




