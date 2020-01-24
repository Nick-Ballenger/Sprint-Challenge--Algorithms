#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)It looks like it would be O(n). It's reliant only on n. So as n gets bigger so too would the run time


b)Since there are two loops that are fully reliant on n, it would be O(n squared). Again, as n gets bigger, so would the run time


c)This would just run one time, so run time would be incredibly quick

## Exercise II

okay, so not to be completely pedantic, but first it would be dependent on how much surface area of the egg is hitting the ground (is it hitting on the side, top or bottom, or something else). If we had a way to determine exactly how it would fall, I'd use known physics equations to determine the force needed to break the egg.

All of that said, assuming that the 0th index of F was the bottom floor I'd give eggs a boolean value of broken=false and a value of 0 to the floor. While broken=false increment the floor by 1, and when broken=true exit the loop return the floor -1.

The time run time would be O(n).
