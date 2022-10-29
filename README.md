# data-and-code-assignment

## Contents 

This directory includes four jupyter python files:

- squares.ipynb
- circles.ipynb
- RingedCircles.ipynb
- generate100.ipynb

## File Details 

#### squares.ipynb 

Represents my implementation of code that was available from a youtube tutorial. It was useful to see how PIL could be used to create an image and draw squares on the image. This tutorial also helped me to understand how to use the module random to allow for the generation of random integers within a range that can be defined. So for example:

`number_of_squares = random.randint(10, 550)`
 
means that each time the code runs that a different integer (a whole number) is selected randomly between 10 and 550. Selecting these random numbers allow for the creative process as it each time the code run it changes:
- the number of squares are drawn on the image
- the coordinates of each of the squares on the image
- the colour of each square on the image


#### circles.ipynb 

Code that captures more learning and experimentation with PIL. This code included learning to draw more types of shapes using the ImageDraw module. It also helped me to learn more about loops in python to repeat the same code running many times - such as the loops to get drawing many objects. It also helped me to understand how loops can be used in various ways, e.g. 

`for x in range(-100, 600, 70):`

means that you start at -100 and then for each loop add 70 until the number reaches 600. So the sequence would go -100, -30, 40, 110, 180 … etc. I also learnt how to use python functions. I found the algorithm for how to find the points of a triangle if you want to draw an equilateral triangle. I was able to put this code into a function so that I could call the same code from multiple places.  Finally, using maths found in another example I learnt how to find points that fit within a circle shape


#### RingedCircles.ipynb

Code that tries different things. Here, based on some other code in a different language I tried to create circles with rings. These are created by drawing smaller and smaller circles on top of each other. Each loop the diameter of the circles is reduced leading to an interesting pattern. I was also helped to understand a conditional expression in python. In the 2nd piece of code in this file a conditional expression is used to switch the colour of the circles between red and black fill colours. 


#### generate100.ipynb

Takes one part of the code in RingedCircles and puts it into another loop which means the art can automatically be generated many times.  This code also used the Image save function to create PNG files as outputs. 


## Usage

To run these files go to SWAN and use 

'git clone https://github.com/loischandler/data-and-code-assignment'


