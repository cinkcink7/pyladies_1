 def domecek(A):
    forward(A)
    left(90)
    forward(A)
    left(45)
    a = ((A/2)** 2) * 2
    forward(pow(a, 1/2))
    left(90)
    forward(pow(a, 1/2))
    left(135)
    forward(A)
    left(225)
    b = (A**2) * 2
    forward(pow(b, 1/2))
    right(135)
    forward(A)
    right(135)
    forward(pow(b, 1/2))
    left(45)
    forward(A)
 
domecek(50)
domecek(30)
domecek(15) 
 
exitonclick() 
