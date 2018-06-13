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

## Production score
Calculate for a vertex by adding the probability of hexes' probability of being rolled.
> Example 1
> 
> The vertex is comprised of a wheat 2, brick 5, and rock 8.
> 
> x + 4x + 5x = 10x
![Example-1](https://drive.google.com/uc?id=1bgcE2kW4AV2s3iiL-F6_-YUNlRUQHK8E)

## Scarcity score
Calculate for a resource type by adding the probability of each of the resource type's hexes.
> Example 2
> 
> Wheat has hexes with 3, 6, 8, and 8
> 
> 2x + 5x + 5x + 5x = 17x
![Example-2](https://drive.google.com/uc?id=1oqOurhQaDejQ9L-PJJCtilefZsEHDLhn)

## Spread score
Calculate for a resource type by finding the mean distance from the mean probability of the hexes of that resource type.
> Example 3
> 
> Wheat has hexes with 3, 6, 8, and 8 (same as the previous example)
> 
> 17x/4 = 17/4x
> |17/4x - 2x| = 9/4x
> |17/4x - 5x| = 3/4x
> |17/4x - 5x| = 3/4x
> |17/4x - 5x| = 3/4x
> (9/4 + 3/4 + 3/4 + 3/4) * x / 4 = 9/8x

## Actualized supply score
Calculate for a resource by adding the probability of each instance of that resource being worked by a player.
> Example 4
>
> Two settlements have been placed on rock hexes with 4 and 5.
>
> 3x + 4x = 7x

## Expected supply score
Calculate for a resource by multiplying the scarcity of that resource by the number of settlements that still need to be placed.
> Example 5
>
> Rock has hexes with 4, 5, and 12 and 4 settlements still need to be placed.
>
> 3x + 4x + x = 8x
> 8x * 4 = 32x

## Machine learning black 

## Next step
If the bot is the last player picking where to place its first settlement then go to [Double settlement](#double-settlement). Otherwise, go to [First settlement](#first-settlement).

# First settlement

# Double settlement



> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5Mzc1Mzc2MzYsLTEyMzU5MzYwNTQsMT
A3NTQzMDA0NiwxNTExNjUwNzU2LDE4NzE3MjI5NTMsLTk4MDg4
ODc2NiwtMTEzNzA5NjQxOSwyMDQ5MDI4MDg2LDE2NzYyMzIzOT
YsNzI3MDM3NjY1LC05OTYzMDQxNjksLTE1NDM2OTI2MTMsMTUz
Mzg2MDUwMSwtMTk5NDU3MjEzOSwxMTkzNzk5NjM2LDE0ODI0ND
U2NywtMTM3MzIyOTMzNV19
-->