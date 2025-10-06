# Keynesian Beauty Contest Game

The Keynesian Beauty Contest is a concept created by John Maynard Keynes. It that describes a beauty contest in which judges are rewarded for selecting the most popular faces among all judges instead of the ones they may actually find the most attractive. It is frequently used in economics to analyze and predict how investors may think. 

This concept was used in a TV show called Alice in Borderland. It was made into a game played with 5 players, in which there are the following rules:

- All players start with 0 points.
- Each round, players choose a number between 0 and 100.
- The average of the numbers everyone selected is multiplied by $p$. By default, $p = \frac{4}{5}$.
- The player (or players, if they both choose the same number) whose number is the closest to that result wins the round. All other players lose a point.
- A player is eliminated if they reach -10 points. 
- The last remaining player wins.

There are also rules added each time a player is eliminated:

- **4 players left**: If two or more players choose the same number, they both lose one point, even if it was the closest to the value.
- **3 players left**: Choosing the exact correct number doubles the penalty for that round only (other players lose 2 points instead of 1).
- **2 players left**: If a player chooses 0, the other player wins if they choose 100.

**Goal:** From a list of possible strategies (ex. always picking high numbers, or low, or random, etc.), if we were to simulate the game, which strategy wins the most often?

## Possible questions

- What is a strategy? (game theory)
- What counts as the 'best strategy'?
- Does the best strategy change if $p$ changes?
- Does the best strategy change when the other rules are added?
- How does the best strategy change depending on the other player's strategy?
- Can this be related to the initial concept of economics?


## Concepts

- Discount factors (@vibingmath in ig).
- Payoff matrix.