#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) 0(n), this is because the while loop runs O(n) and there is operation inside of this throughout which gives us 0(1) and when combined we get the runtime complexity of 0(n).

b) 0(log(n)), because we have two loops that are multiplied by each other. Loop 1 being n, and loop 2 being log(n), which gives us n * log(n). The nested while loop is log(n) is because the runtime complexity of this loop get cut in half whenever we get to it because of the j*=2 line.

c) 0(n), this is because the whole algorithm behaves similarly to a simple for loop. in that it begins with n and the value decreases by 1 until n reaches zero. Whenever the algorithm calls itself again the remaining number of loops decreases by 1.

## Exercise II

If the egg breaks on the first drop, return the floor it was dropped from. Start with the first floor possible (floor zero, or floor 'a' if it goes in alphabetical order). For each floor starting at zero until we reach n, if dropping the egg breaks it, return the floor it was dropped from. This should only break one egg, because dropping the egg up until floor f would not break it, and breaking it by dropping the egg from floor f will end/restart the loop. This should result in a runtime complexity of 0(n). 