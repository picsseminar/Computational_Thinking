``` python
import turtle

tom = turtle.Turtle()
tom.forward(100)
tom.right(90)
tom.forward(100)
tom.right(90)
tom.forward(100)
tom.right(90)
tom.forward(100)
tom.right(90)
```

The code above will draw a square with sides of length 100.

How would you change the code if you wanted a different side length?

How would you change the code if you wanted a hexagon of side length 100?

Let's get new code to draw a polygon.  

``` python
import turtle

sides = 10
angle = 36
tom = turtle.Turtle()

for i in range(sides):
  tom.forward(100)
  tom.right(angle)
  
```

``` python
import turtle

def drawPolygon(sides,length,t):
  for i in range(sides):
    t.forward(length)
    t.right(360/sides)

tom = turtle.Turtle()

drawPolygon(5,100,tom)
drawPolygon(4,200,tom)
drawPolygon(6,50,tom)
```
