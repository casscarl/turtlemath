# turtlemath

This function takes 2 inputs, a turtle object and number of steps. 

There is a variable determining step length and step angle
the angle variable is responsible for the complex pattern of the drawings
using triginometric functions, especially incorporating tangent into this variable creates interesting and complex drawing.

the variables are used to create lists of the step length and angle with values for each step.

these lists then determine the movement of the turtle 

The of the work in this project was the search for interesting patterns from mathematical functions. 
Arriving at my final drawings took hours of testing different inputs and waiting to see what the turtle would do. 
The majority of functions I tried inputting resulted in various types of inward spirals and were for the most part uninteresting. 
Using tangent in the angle determinent function gave the best results but even after finding this, it took many iterations to find a good functions. 

The primary difficulty I encountered in my exploration was the time required to render my drawings using turtle in google colab.
to adress this issue, I set up an IDE using visual studio code and adjusted my initial code to run in regular turtle instead of ColabTurtlePlus. 
Even using VS Code however, test drawings were taking hours to render just for them to not be what I was looking for. 
I was having issues saving my turtle drawing as an image as well and the best method I could find online was to Pip Install SVGTurtle.
This solved my problem with saving images but also drastically sped up the time it took to render drawings and allowed me to run significantly larger drawings.
Using SVGturtle allowed a function with 1000000 steps to render in the time it took basic turtle to render 1000 steps.
I found the information about SVGTurtle at https://pypi.org/project/svg-turtle/ , https://www.youtube.com/watch?v=U0MdznoiCGY this youtube video was helpful in using pip install.

I would like to make this code more user freindly and easier to change inputs and variables. 
Finding a way tlo hide the code behind a website that has simple boxes for inputs and can output an svg woulod be really interesting. 
I am also excited to do more expirements with different functions and inputs when I have more time in the future.
