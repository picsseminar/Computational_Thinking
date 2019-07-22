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
  ## Your Code here
  
def drawYellowLines(parameters):
  ## Your Code here
  
def drawBlueLines(parameters):
  ## Your Code here
  
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
