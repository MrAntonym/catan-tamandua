# DECISIONTREE
The English text version of the decision tree for the bot.

# Reused Constants and Math
The following are constants which are used throughout the document and their values:
>x = 1/36

The following is some math and probabilities that are assumed to be known offhand:
>Probability of two dice rolling:
>
>2 ⟹ 1/36 = x
>
>3 ⟹ 2/36 = 2x
>
>4 ⟹ 3/36 = 3x
>
>5 ⟹ 4/36 = 4x
>
>6 ⟹ 5/36 = 5x
>
>7 ⟹ 6/36 = 6x
>
>8 ⟹ 5/36 = 5x
>
>9 ⟹ 4/36 = 4x
>
>10 ⟹ 3/36 = 3x
>
>11 ⟹ 2/36 = 2x
>
>12 ⟹ 1/36 = x

# Start of the game
If the bot is the picking settlement placement last then go to [Double settlement](#double-settlement). Otherwise, go to [First settlement](#first-settlement).

# First settlement
## Production score
Calculate by, for each available vertex (those not too close to other settlements), adding the probability of hexes' probability of being rolled.
> Example 1
> 
> The vertex is comprised of a wheat 2, brick 5, and rock 8.
> 
> x + 4x + 5x = 10x
![Example-1](https://drive.google.com/uc?id=1bgcE2kW4AV2s3iiL-F6_-YUNlRUQHK8E)

## Scarcity score
Calculate by adding the probability of each resource's hexes.
> Example 2
> 
> Wheat has hexes with 3, 6, 8, and 8
> 
> 2x + 5x + 5x + 5x = 17x
![Example-2]()

# Double settlement



> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExMzcwOTY0MTksMjA0OTAyODA4NiwxNj
c2MjMyMzk2LDcyNzAzNzY2NSwtOTk2MzA0MTY5LC0xNTQzNjky
NjEzLDE1MzM4NjA1MDEsLTE5OTQ1NzIxMzksMTE5Mzc5OTYzNi
wxNDgyNDQ1NjcsLTEzNzMyMjkzMzVdfQ==
-->