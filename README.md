The project is a simulation of the prisoner's dilemma. It is a standard example of a game analyzed in game theory. Two prisoners A and B can either cooperate (C) or defect (D). If A and B both defect, each of them will serve 1 year. If A cooperate but B defect, A will be set free and B will serve 5 years in prison (and vice versa). If both A and B cooperate, each of them will serve 3 years in prison. I will run a simulation of A and B playing 200 times using different strategies (random, tit for tat, ...) to see which strategy would be better in the long run (better meaning serving less years in prison.)

Here are the strategies which are included in the worksheet: 
+ Random: Randomly cooperate or defect. 
+ Tit for Tat: Cooperate, then repeat the opponent's last move. 
+ Friedman: Cooperate until the opponent's defect, then defect until the end of the game.
+ Davis: Cooperate on the first ten moves, then if the opponent's defect then defect until the end of the game. 
+ Grofman: If the players did different things on the previous move, this rule cooperates with probability 2/7. Otherwise this rule always cooperates. 
+ Downing: Initially assume the that the probability of other other player defects/cooperates is 50/50. Each move, it updates its estimate of these two conditional probabilities and then selects the choice which will maximize its own long-term payoff under the assumption that it has correctly modeled the other players.

The worksheet let the user either play 1v1 between different strategies, or play a tournament between all the strategies against each other. The scores of each player with each of the others are displayed in the table. Noticed that some entries of the tables are 600. This is because there are some strategies that when play, they are sure to cooperate with each other until the end of the game (tit for tat vs tit for tat is one). 
