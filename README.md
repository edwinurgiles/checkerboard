# checkerboard
import turtle

turtle.pensize(2)
turtle.penup()
turtle.speed(20)
turtle.goto(-160,-160)
turtle.color("black")

for i in range(4):
    turtle.forward(320)
    turtle.left(90)
    turtle.pendown()

for y in range(-160,160,80):
    for x in range(-160,160,80):
        turtle.begin_fill()
        turtle.penup()
        turtle.goto(x,y)
        

        for k in range(4):
            turtle.forward(40)
            turtle.left(90)

        turtle.end_fill()       

for y in range(-120,160,80):
    for x in range(-120,160,80):
        turtle.begin_fill()
        turtle.penup()
        turtle.goto(x,y)
        for k in range(4):
            turtle.forward(40)
            turtle.left(90)
        turtle.end_fill()   

turtle.done()
