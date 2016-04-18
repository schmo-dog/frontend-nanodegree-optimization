# Frontend Nanodegree Website Optimization Project
### To run the application open pizza.html in a browser

####There are two optomizations made within main.js

#####Optomizing the Frames per Second (fps) when the user scrolls down the page and the pizzas move. The fps need to be 60 or higher.

How this was done: 
Reduced the amount of pizzas that were being made down to 24.

Took calulation of phase outside of for loop and placed the consistant 5 numbers to reference in an array.

Optimized by use of element lookup.

#####Optomize the time it takes to resize the pizzas. The target is under 5ms.

How this was done: 
Took calculation of dx and newWidth out of for loop and optimized by use of element lookup.
