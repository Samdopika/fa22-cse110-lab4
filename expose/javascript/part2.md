## Q1

At line 9, it's just gonna print the value of i after the loop is done doing its thing. In this case, it's gonna print "3" 'cause the loop ran 3 times for the 3 items in the prices array. Once the loop's finished, i is 3, and that's what gets printed on line 9.


## Q2

At line 9, you'll run into a ReferenceError. That's 'cause discountedPrice is declared with var inside the loop, which means it's only available in that loop. When you try to print discountedPrice on line 9, which is outside the loop, the code can't find the variable, and you'll get an error.

## Q3

At line 9, there's no error, and it's just gonna print the value of finalPrice after the loop's done. In this case, it'll print "150" 'cause finalPrice gets updated each time the loop runs, and after the loop, it has the last discounted price. With a 50% discount, the last price in the array (300) becomes 150, so that's what line 9 prints.

## Q4


So, this function returns an array with discounted prices. In this case, it gives back [50, 100, 150]. Here's the lowdown:

The function loops through the prices and finds the discounted price for each item using prices[i] * (1 - discount). Then, it rounds the result to 2 decimal places using Math.round(discountedPrice * 100) / 100. The discounted price is added to the discounted array, and when the loop is done, the function returns the discounted array with all the sweet discounted prices from the original prices array.


## Q5

At line 9, you're gonna run into a ReferenceError. It's 'cause i is declared with let in the loop, so it's only available within that loop. When you try to print i on line 9, which is outside the loop, the code can't find the variable, and you'll get the error.


## Q6


So, at line 9, you'll run into a ReferenceError. That's 'cause discountedPrice is declared using let inside the loop, and it's only chillin' within that loop. When you're tryin' to print discountedPrice on line 9, which is outside the loop, the code can't find the variable, and boom! You get the error.



## Q7


