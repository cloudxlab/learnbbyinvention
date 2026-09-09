Create presentation for teaching a class 'line fitting' and curve fitting by the way of learn by inventing
The square brackets contain the instructions to claude:

1. Show a block diagram where input is x and output is y. And display the following question next to it:
when x was 1, y was 3 and when x was 2, y became 7, how much will be y when x will be 3?
[display the x, y as a table and put x=3, y=? as last row]

Display another questions on clicking next:
    * That right! It is y = 11
    * how much will be y when x will be 2.5? [add x=3, y= 11 and x=2.5, y=? in the table]
    * Yes! It is mid point between 7 and 11, that is 9.
    * And how how much will be y when x will be 2.1?
    * [After every step, show the answer and congratulate! and for next question put that in table]
    * How much will be y at x = 0?
    * How much will be y at x = 0.5?
    * How much will be y at x = x1?
    * Yes! That's right y = 4x - 1

--
Initial show the block diagram to be bigger. and display the text 'There's a mystery box. You feed it a number x and it gives back a number y. You tried it twice and got the table on the left. [data table]'

After you click next this appears 'How much will y be when x = 3?' and the block diagram reduces to a smaller size - the size it is now.

--
From now on, the things in square brackets are for the ende user i.e. it is part of the content.

put y = 4x − 1 in a the box diagram show x as input and y as input
[Now write a python function with name model that takes x as argument and returns y]
Show the outline:
    [
        def f(x):
            y = <write your code>
            return y
    ]
[That's right! The code looks like as follows:]
Show the full code.
[Now, test by calling f(2), f(3), f(0)]
[Now, try different values of x and check if value of y is correct as per the table!]
---

[Let's look back and embrace what we have done]
[We had data (two points) and we came up with a model (line) and with this model we are able to answer unseen questions]
[In machine learning, coming up with the model is called training and using the model to give output is called inference phase]
Display the two phases of machine learning in block diagram and show data and equations etc on this blocks.

Display an analogy of ChatGPT too

[Quick Question: can your equation of line give the output for a value that it has not seen before, say x = -100 ? ]
[Yes, of course.]

[Similarily, can ChatGPT or LLM answer questions that it has not seen before?]
[Yes, of course.]
---
Add new slides.

Show a block diagram same diagram again x is going in and y is coming out. 
[The other way to look at this  is - it is a linear relationship between input and output. y = a * x + b. Let's solve another problem to get a grasp of it]
Click to go to next.
[Do you know how does electronic thermometer work? When a metal is heated, it resistance changes and that changes the electric current through it. We can measure the current and estimate the temperature from it]
Click to go to next.
[We have the following data points for current I = 1 mA, the temperature was 10F and for I=1.2 mA, temperature was 50F. find the equation that can convert current into temperature - T = a*I + b, a =? and b = ?]
[Put the two values in the equation, you would would get two sets of equations in T and I. like this: ]
Create the two equations
[Now solve them.]
[So, the final equation is ....]

New Slide
[There could more inputs like x1, x2, y = a* x1 + b * x2 + c]
Show a block diagram with two inputs x1 and x2
[Quick question: to find a, b and c how many pairs of (x1, x2, y) are needed?
Click to go to next
[That's right to solve for a, b and c we need at least three equations. Hence, three instances minimum]

New Slide
[There could be a complex relationship between inputs and outputs, y = a * x ^2 + b * x + c]
Show a diagram with one input and output
[Or there could be a much more complex relationship between input and output: y = a*x1^2 + b*x1^2 + c*x1 + d*x2 + e*x1*x2 + f]
[Here we have a,b,c,d,e and f five params.]
[In case of LLMs, there are 100s of billions of such parameters and equation is much more complex!]

