
from turtle import Turtle, Screen, colormode
import random

t = Turtle()

def random_color():
    r = random.randint(0, 255)
    g = random.randint(0, 255)
    b = random.randint(0, 255)
    new_color = (r, g, b)
    return new_color

directions = [0, 90, 180, 270]
t.pensize(15)
t.speed("fastest")
colormode(255)

for _ in range(300):
    t.color(random_color())
    t.forward(30)
    t.setheading(random.choice(directions))

s = Screen()
s.exitonclick()
