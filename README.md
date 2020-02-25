# Generating-Mandelbrot-Set-Using-User-Dimensions
Write a program that makes use of functions, conditional execution, and looping to perform a repeated calculation and display the results.

# Problem: 
- Using python, write a program that will take two integer dimensions (width and height) from the user and then perform the necessary calculations to generate a Mandelbrot set of that dimension. 

# Use meaningful variable and function names in order to:
- Accept input from the user on the width and height of the image to be displayed.(Optional) Accept as input the four(4) float values that determine the placement of the display window. 
- Write a function to perform the iterations for a single point in the complex plane with a specified upper limit on the iterations (1000-10000 your choice). This function should return an Boolean indication of whether the given point is in or out of the Mandelbrot set.
- Write a function to iterate over the given width and height; determining the corresponding value of the point in the complex plane and call the iteration function for each point. 
- Output an “in” or “out” symbol for each point calculated in order to create an “image”.

# Additional Details: 
- In order to generate the Mandelbrot set, we will be using iteration at each point and looping over two dimensions. These two dimensions correspond to real and imaginary parts of the value at each point. In order to do so, we will be discretizing the space and computing a value representative of each discrete part. 
