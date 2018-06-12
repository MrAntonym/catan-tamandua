# DECISIONTREE
The English text version of the decision tree for the bot.

# Reused Constants and Math
The following are constants which are used throughout the document and their values:
>x = 1/36

The following is some math and probabilities that are assumed to be known offhand:
>Probability of two dice rolling:
>2 ⟹ 1/36 = x
>3 ⟹ 2/36 = 2x
>4 ⟹ 3/36 = 3x
>5 ⟹ 4/36 = 4x
>6 ⟹ 5/36 = 5x
>7 ⟹ 6/36 = 6x
>8 ⟹ 5/36 = 5x
>9 ⟹ 4/36 = 4x
>10 ⟹ 3/36 = 3x
>11 ⟹ 2/36 = 2x
>12 ⟹ 1/36 = x

# Start of the game
If the bot is the picking settlement placement last then go to [Double settlement](#double-settlement). Otherwise, go to [First settlement](#first-settlement).

# First settlement
## Production Score
For each available vertex (those not too close to other settlements), add the probability of each of the hexes' numbers being rolled.
> Example 1
> x + 4x + 5x = 10x
![Forest](https://drive.google.com/uc?id=1CpnCd98VNFQSrKjeulwiR4AymNAAqxdr)

# Double settlement



> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjEyODAyMjc5NCw3MjcwMzc2NjUsLTk5Nj
MwNDE2OSwtMTU0MzY5MjYxMywxNTMzODYwNTAxLC0xOTk0NTcy
MTM5LDExOTM3OTk2MzYsMTQ4MjQ0NTY3LC0xMzczMjI5MzM1XX
0=
-->