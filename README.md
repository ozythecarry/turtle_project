# turtle_project
import turtle

# Background/window
window = turtle.Screen()
window.title("Dont hit the objects!")
window.bgcolor("black")
window.tracer(0)
window.setup(width=800, height=600)

# Left racket
l_racket = turtle.Turtle()
l_racket.speed(0)
l_racket.shape("square")
l_racket.color("Yellow")
l_racket.shapesize(stretch_wid=5, stretch_len=1)
l_racket.penup()
l_racket.goto(-350, 0)

# Right racket
r_racket = turtle.Turtle()
r_racket.speed(0)
r_racket.shape("square")
r_racket.color("Yellow")
r_racket.shapesize(stretch_wid=5, stretch_len=1)
r_racket.penup()
r_racket.goto(350, 0)

# Ball
ball = turtle.Turtle()
ball.speed(0)
ball.shape("circle")
ball.color("red")
ball.shapesize(stretch_wid=2)
ball.penup()
ball.goto(0, 0)




# Main game loop
while True:
    window.update()

