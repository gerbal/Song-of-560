---
layout: post
author: julie
title: Julie's Turtle Post
date: 2014-01-16
---

For my turtle  exercises, I wanted to play around with the different turtle shapes. I also wanted to practice using loops. Here is what I came up with:

```

import turtle
wn = turtle.Screen()
wn.bgcolor("magenta")
tess = turtle.Turtle()
tess.color("blue")
tess.shape("circle")

print(range(5,60,2))
tess.up()                   
for size in range(5,60,2):    
    tess.stamp()                
    tess.forward(size)          
    tess.right(24)              

alex = turtle.Turtle()
alex.color ("yellow")
alex.shape ("arrow")
for i in [1,2,3,4,5,6,7,8,9]:
    alex.stamp()
    alex.forward(50)
    alex.left(40)

jamal = turtle.Turtle()
jamal.color ("green")
jamal.shape ("turtle")
jamal.penup()

for i in [1,2,3,4,5,6,7,8,9,10]:
    jamal.stamp()
    jamal.forward(-50)
    jamal.right(45)
    jamal.forward(50)

carlos=turtle.Turtle()
carlos.shape ("classic")
carlos.pensize (15)

for aColor in ["white", "black", "green", "blue", "pink", "red", "orange", "purple"]:
   carlos.stamp
   carlos.color(aColor)
   carlos.forward(50)
   carlos.left(90)
   carlos.forward(-50)
   
wn.exitonclick()

```

![Turtle Image](https://lh6.googleusercontent.com/-3texUyEP0Fg/UtwxCbEsK_I/AAAAAAAAEBg/S6wqUCsSobc/s0-I/julie_turtle.png)


**Reflection**

Overall it was pretty fun. I especially enjoyed making the last one change different colors. I think I made a lot of mistakes that are probably typical for beginners, like forgetting to capitalize the second Turtle and not closing parentheses sometimes. I spent about 15 minutes trying to figure out why it wouldn't draw my second turtle, only to realize I had left the first set of parentheses open! But it was a good way to learn...
