# Monte_Carlo_Simulation_With_Coin_Toss
Introduction to Monte Carlo Simulation and using it with a game of coin toss


I have chosen 5,10,15,20,30,40,50 as amount used for each game to play, and I have played a series of 5,10,15,20,25,30,50 games. Each set of these games has been played using the MCS code which I have written in my own sense, generating random values and displaying the winnings of each game as well as total amount won in a set of games as well.

To answer the question of the reasonable amount to play, I am not mentioning the exact value, but after going through my data (and some common reasoning in me felt), no one should play this game for more than 20 pounds/game. Higher amounts have got a higher variation in each of the average games played, having high outliers in them, so winning those has a very small probability as well. So to be in a safer side, no more than 20 pounds should be fine.

While my code was doing a lot of the data collection, I was surprised how the MCS works. The way it was generating the random values, it did generate some fascinating outlies as well, as you might find in the data sheet. Sometimes it did generate same values in same series multiple times, but then it will generate completely different data in the next set. This unpredictability of MCS is something which kept me working on this till late of most recent days, and it felt it was worth it.
Also, while my data was changing both the amount payed for each game and the number of games played, I found that there was not much significant value of each parameter, as there were cases when the pay per game amount was low but then due to high number of games it won much value, and vice versa. But for some cases when the games played was 25, it has shown lower variance, meaning values were closer to mean, indicating higher chance of winning. But, again, this data being random, am not sure if it’s the case every time.

In conclusion, MCS with its randomness, can be useful in finding answers to things we haven’t applied the MCS yet as well.  As I have mentioned in the beginning, I was collecting and deleting the data, fearing it to be not perfect. But that’s what MCS does, its job is not to give us perfect data, but to give huge random ones, and then making them perfect.
