# cmpt120-assignment-2-automatic-crowds-solved
**TO GET THIS SOLUTION VISIT:** [CMPT120 Assignment 2-Automatic Crowds Solved](https://www.ankitcodinghub.com/product/cmpt120-assignment-2-automatic-crowds-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120410&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;6&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (6 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPT120 Assignment 2-Automatic Crowds Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (6 votes)    </div>
    </div>
Nobody goes there anymore. It’s too crowded.

Yogi Berra

You’ve probably seen movies with huge crowds of people. While they might sometimes have real people, nowadays crowds are often computergenerated. This gives the film-makers more control over their size and behaviour, and probably saves them money as well.

So in this assignment, we’ll explore how to make a simple crowd scene using turtle graphics.

Answer the questions below in order: later questions depend upon earlier ones. Use exactly the function name and parameters as given in the question, put all your functions into a single Python file named a2.py. Please include your name and email at the top of a2.py formatted like this: “`python

Full Name:

SFU Email:

“`

When you’re done, submit your finished a2.py file on Canvas.

Question 1: Regular Polygons

Write a function called polygon(n, size) that uses turtle graphics to draw an $n$-sided regular polygon with each side of length size.

Use this algorithm:

Set the turning $mathit{angle}$ to be $rac{360}{n}$.

Do the following $n$ times:

draw a line of length size turn left $mathit{angle}$ degrees

For example, here is a pentagon (a 5-sided polygon):

Question 2: Jumping

Write a function called jump_to(x, y) that moves the turtle to position (x, y) without drawing a line. After the turtle has jumped to (x, y) its pen should be down, ready to draw.

turtle.goto(x, y) will move the turtle to (x, y), but if the pen is down it will draw an unwanted line.

In the following functions, use jump_to to move the turtle to its correct starting point.

These four pentagons are one example of something you can draw using polygon and jump_to. You don’t need to submit it with your assignment. But a good way to test jump_to is to write a function called test_jump_to() that draws theses 4 pentagons, or some other picture.

Question 3: Circles

Write a function called circle(radius) that draws a circle whose radius is radius. To draw a circle in turtle graphics, just draw a polygon with lots of sides, say 50 – 100.

Important Don’t call the turtle.circle(r) to draw this circle. Use just your polygon function.

To calculate the size (length) of the polygon edges, use this formula inside your circle function:

$$mathit{size} = 2 mathit{r} sin rac{pi}{n}$$

Here, $r$ is the radius passed to circle, and $n$ is the number sides of the polygon.

The sin function, and pi, are in Python’s math module.

Question 4: Eyes

Write a function called eye(radius) that draws one (cartoon) eye using two circles: a big circle, and a filled-in smaller circle inside the big one (representing the pupil).

Use the turtle.begin_fill() and turtle.end_fill() functions to fill-in the smaller circle.

Here’s an example:

Question 5: Noses

Write a function called nose(size) that draws a (cartoon) nose that consists of, at least, two different shapes. The exact style and look of the nose is up to you. It could be as simple as an upside-down 7.

As with mouth, what exactly size means is up to you. Make it so that the bigger size is, the bigger the nose.

Question 6: Mouths

Write a function called mouth(size, style) that draws a (cartoon) mouth as follows:

If style == ‘happy’, the mouth is drawn smiling.

If style == ‘sad’, the mouth is drawn frowning.

If style == surprised, the mouth is drawn as a circle.

For any other value of style, the mouth is drawn as a neutral expression, e.g. a straight line.

What exactly size means is up to you. Make it so that the bigger size is, the bigger the mouth.

Here are examples of the four mouths:

Question 7: Heads

Write a function called head(size) that draws a (cartoon) head that consists of, at least, two eyes, a random mouth, a nose, and a head (e.g. a circle) all around it. Use the functions you wrote above to draw the eyes, mouth, and nose.

Choose the mouth style at random to be one of the 4 mouth shapes.

The size of the head should be controllable using size, e.g. a small value of size should draw a small head, and a big value should draw a big head. Make sure all the eyes, nose, and mouth fit into it snugly and are proportional to the size.

For instance, a head with a surprised face could look like this:

Question 8: Stick Figures

Write a function called stick_figure(size) that adds a head (using head), and a body underneath it. It should have, at least, a torso (maybe just a line), arms, and legs. They can be simple stick figures if you like, or more elaborate.

Include some randomness in the body beyond just the mouth randomness. For example, you could chose the color at random, or make the arms point in random directions, or draw the body with different thicknesses, etc.

Question 9: Crowds

Write a function called crowd(n, min_size, max_size) that draws n stick figures (using your stick_figure function) at random locations on the screen. The size of each stick figure should be chosen at random in the range min_size to max_size.

Marking Scheme

1 mark overall: consistent indentation and spacing (all blank lines and spaces should have a good reason for being there) 1 mark overall: all variable names are self-descriptive

1 mark overall: the length of all lines are less than, or equal to, 100 characters

Hints

In addition to calling turtle.speed(‘fastest’) or turtle.hideturtle(), you can speed up drawing quite a bit with this code: “`python turtle.Screen().tracer(0) # don’t show any drawing on the screen

… draw stuff here …

turtle.Screen().update() # refresh the screen to see what was drawn “`

If you want to save a turtle position to come back to later, you can do this: “`python x, y = turtle.position()

# … do stuff …

jump_to(x, y) # go back to location (x, y) “`

To make the turtle face a particular direction, use one of these:

python turtle.setheading(0) # face east turtle.setheading(90) # face north turtle.setheading(180) # face west turtle.setheading(270) # face south
