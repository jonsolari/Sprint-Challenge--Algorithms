#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(log n) -- The function isn't quite linear following n, but makes considerable leaps and bounds (via n^2) to approach n^3.


b) O(n^2) -- Follows n in a for loop, but also contains a nested while loop following j which progresses a bit faster-- perhaps not quite O(n^2) but close to it.


c) O(c^n) -- About as much time taken as a linear iteration (only backwards and via recursion) and with a branching tree of recursive calls.

## Exercise II

I would run an egg up to any floor above ground level and drop it, noting the first drop with a breakage as the lowest/first unsafe floor to drop eggs from. I would be an O(n) as it follows the number of floors one by one until meeting the broken-egg requirement.

