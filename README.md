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
