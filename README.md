# Snake-Game
Classic Nokia snake game clone I made with the Scrimba crew.

Use the arrows to pursue the apples-- don't run into the sides, and don't run into yourself!



This is a grid based game built with Vanilla JS, CSS, and html. That's it!

//While making this game I was able to learn how to create a grid using a for loop, and document.createElement api. I then wrote a funciton to push the newly created individual "squares" into a new array, which is obviously an iterable. 

//This enabled me to make the snake "animate", by push, pop, shift, unshift each square based on the user's interaction with the arrow keys. (also learned about key codes!!) 

//As the snake grows (appendChild with 'snake' class used here), it increases in speed using setInterval and passing in an incrementing variable as its argument.

//In the moveSnake function, the logic makes sure the snake doesn't hit either side of the grid. If it does, game over. (clearInterval)
Bit of math using modulus, subtraction, and comparitive operators, to check what position the snake is.




//Shout out to Ania Kubow for the awesome lessons!


