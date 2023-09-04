# Game example with distribution of profit

Here's a table to represent the participants and their placed amounts:

| Participant | Amount ($PLAYW) | Closest to Forecast |
| ----------- | --------------- | ------------------- |
| Player 1    | 15              | Yes                 |
| Player 2    | 15              | No                  |
| Player 3    | 5               | Yes                 |
| Player 4    | 5               | No                  |
| Player 5    | 5               | No                  |

In this scenario, Player 1 and Player 3 were the closest to the forecasted price. To calculate the reward distribution, we'll first determine the total amount of $PLAYW placed by all players:

* Total $PLAYW: 15 + 15 + 5 + 5 + 5 = 45 $PLAYW

Next, we'll sum up the tokens of the winners (Player 1 and Player 3):

* Total winning amount: 15 + 5 = 20 PLAYW

Now we can calculate the proportion of each winner relative to the total winning:

* Player 1 proportion: 15 / 20 = 0.75&#x20;
* Player 3 proportion: 5 / 20 = 0.25

Finally, we'll distribute the rewards based on these proportions. The rewards pool consists of the losing amount:

* Rewards pool: 15 (Player 2) + 5 (Player 4) + 5 (Player 5) = 25 PLAYW
* Player 1 reward: 0.75 \* 25 = 18.75 PLAYW&#x20;
* Player 3 reward: 0.25 \* 25 = 6.25 PLAYW

In summary, Player 1 receives 18.75 PLAYW, and Player 3 receives 6.25 PLAYW as rewards for their accurate predictions.
