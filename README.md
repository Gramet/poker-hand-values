# poker-hand-values
Gaétan Ramet

## Solution

For this one, I didn't implement any ML at all. I quickly designed a solution to check the value of a hand, starting from the best possible value going to the lower ones.

Checking for pairs and such is quite straightforward. Checking for Straight is the most difficult to implement as you need to check that the 5 values are different and in a range of 5, or that it's TJQKA which is an edge case.
