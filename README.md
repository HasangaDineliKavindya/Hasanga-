# Hasanga-
from turtle import*
import colorsys

speed(0)
bgcolor('black')
h=0.2
pensize(2)

for i in range(180):
    c=colorsys.hsv_to_rgb(h,1,1)
    h+=0.002
    fillcolor("red")
    begin_fill()
    circle(180-i,70)
    lt(80)
    circle(180-i,70)
    rt(20)
    for j in range(4):
        rt(60)
    lt(120)
    end_fill()

done()
