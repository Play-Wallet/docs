# Game example with distribution of profit

Here's an example of a pari-mutuel system with five participants for event "Is Trump go to jail?" and their prediction on whether an event occurs or not.

| Participant | Event Outcome | Amount (ARB) |
| ----------- | ------------- | ------------ |
| Player 1    | No            | 10,000       |
| Player 2    | No            | 10,000       |
| Player 3    | Yes           | 1,000        |
| Player 4    | Yes           | 100          |
| Player 5    | Yes           | 10           |

In this example, the total amount on "No" is 20,000 ARB, while the total amount on "Yes" is 1,110 ARB.

Assuming that the event occurs (the "Yes" outcome wins), we can calculate the payouts for participants 3, 4, and 5 using the pari-mutuel system.

| Participant | Event Outcome | Amount (ARB) | Payout (ARB) |
| ----------- | ------------- | ------------ | ------------ |
| Player 3    | Yes           | 1,000        | 18,000       |
| Player 4    | Yes           | 100          | 1,800        |
| Player 5    | Yes           | 10           | 180          |

To calculate the payouts, we first determine the total pool of funds for the winning outcome, which is the sum of placed amount on the losing outcome (20,000 ARB in this case). Then, we divide the total pool by the sum of placed amount on the winning outcome (1,110 ARB) to obtain the payout multiplier (20,000 / 1,110 ≈ 18). Finally, we multiply each participant's placed amount by the payout multiplier to determine their respective payouts.

For example, for participant 3, the payout is 1,000 ARB \* 18 = 18,000 ARB. Similarly, the payouts for participants 4 and 5 are 1,800 ARB and 180 ARB, respectively.
