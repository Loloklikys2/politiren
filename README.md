# politiren
x1 = 0
x2 = 0
def setup():
    size(800,600)
    
def draw():
    global x1
    global x2
    ellipse(370,300,x1,x2)
    x1 = x1 + 1
    x2 = x2 + 1
