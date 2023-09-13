import turtle as t
import colorsys
t.bgcolor('black')
t.tracer(10)
t.pensize(2)
h=0
n=50
for i in range(350):
     c=colorsys.hsv-to-rgb(h,1,1,1)
     t.width(i/140+2)
     t.pencolor(c)
     h+=1/n
     t.right(40)
     t.circle(-i*0.5,-100)
     t.circle(i*0.5,100)
     t.circle(i*0.5,40)
     t.done()
