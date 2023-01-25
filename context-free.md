# Context Free

##  Who is this programming language for?
This programming language is for people who want to make art that can have 
randomness yet also be well segmented into components.

## What is easy to do in this language? Why is it easy?
It is easy to understand how art is randomly generated in this language 
because you can write rules and see how it either follows one rule or another.

## What is hard to do in this language? Why is it hard?
It is hard to find out how to do new things in this language because it does 
not seem like there is much available information. Like an example would be 
coloring shapes, I only found out how to do this because I found documentation 
on how to color a background and I implied how we could apply that to a shape.

## How did you learn how to program in this language?
I learned to program in this language primarily by watching a Youtube video: 
https://www.youtube.com/watch?v=rV7dpvS_Gi4 and I found our how to color based 
off this documentation: 
https://github.com/MtnViewJohn/context-free/wiki#variables .

## What is the underlying _computational model_ for this programming language? 
_We don't yet have a great definition of the term "computational model". 
For now, try to come up with the clearest, most concise explanation of what 
happens when a ContextFree program runs._

It seems like when a ContextFree program runs, it begins at the startshape 
command which tells the computer what shape it wants made, and in order to 
find out what that shape name means, it looks deeper in the file to where 
that shape is assigned rules and in that set of rules if it references 
other shapes then the computer repeats the process of seeking shapes 
until it reaches the basic shapes like circle, triangle, and square, which 
are commands telling the computer to display an arrangement of pixels with 
their location and color being based on the parameters placed inside the 
square brackets associated with the respective shape.


## What do you think is interesting about the ContextFree program you wrote?
I think the ContextFree program I wrote is interesting because it uses 
recursion and rules to demonstrate how ContextFree can be useful for making 
a large number of shapes appear in a random arrangement.
