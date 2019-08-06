Who was Sol LeWitt?

Find the instructions to make Wall Drawing 273.

Below, you will find starter code to make the computer draw Wall Drawing 273.  Your task is to write the necessary code to
draw the colored lines from appropriate places by calling the functions with appropriate arguments.

```python
import turtle
from random import randrange

def drawBox(l,w,t):
    t.color('black')
    for i in range(2):
        t.forward(l)
        t.left(90)
        t.forward(w)
        t.left(90)

def drawRedLines(parameters):
  t.color('red')
  for i in range(i):
    endX =
    endY =
    t.pu()
    t.goto(startX,startY)
    t.pd()
    t.goto(endX,endY)
  
  
def drawYellowLines(parameters):
  t.color('yellow')
  for i in range(i):
    endX =
    endY =
    t.pu()
    t.goto(startX,startY)
    t.pd()
    t.goto(endX,endY)
  
  
def drawBlueLines(parameters):
  t.color('blue')
  for i in range(i):
    endX =
    endY =
    t.pu()
    t.goto(startX,startY)
    t.pd()
    t.goto(endX,endY)
  
  
wn = turtle.Screen()
tom = turtle.Turtle()

length = 420
width = 360

drawBox(length,width,tom)
drawRedLines( )
drawYellowLines( )
drawBlueLines( )

wn.mainloop()
```
