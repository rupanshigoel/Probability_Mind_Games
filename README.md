# Probability_Mind_Games
Alice and Bob play a game of chess, but they can choose their style of playing each round. In each round, they
can choose to be aggressive, balanced or defensive. A win gets +1 point, a draw gets +0.5, and a loss gets 0
points. <br />
There is a probability matrix which describes the probability of winning, losing, or draw for each player. These probilities in the case of attack, depends on the previous wins of both the players.<br />
1) In the first case, Bob's form is susceptible to his performance in the previous round.<br />
• If he won the previous round, then he chooses to play defensively. <br />
• If the previous round resulted in a draw, then he plays balanced. <br />
• If he lost the previous round, then he plays aggressively. <br />
a. Here I have simulated the greedy strategy where Alice maximises her chance of winning the current round.<br />
b. Then I found the expectation of the number of rounds for Alice to get some T wins using monte carlo simulations.<br />
3) In the second case, Bob uniformly chooses his play style.<br />
a. I have simulated Alice's strategy to maximise the number of points gained in the current round.<br />
b. Found the optimal strategy for Alice to maximise the expected number of points in some T future rounds using dynamic programming and calculated that expectation.<br />
