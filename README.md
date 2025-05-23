import pyttsx3
engine= pyttsx3.init()
engine.say("welcome to the our shop")
engine.runAndWait()


import pyttsx3
engine= pyttsx3.init()
engine.say("enter the value of a")
engine.runAndWait()

a =int(input("enter the  value a:"))

import pyttsx3
engine= pyttsx3.init()
engine.say("enter the QTY x")
engine.runAndWait()




x =int(input("enter the QTY x"))
import pyttsx3
engine= pyttsx3.init()
engine.say("enter the value of b")
engine.runAndWait()

b =int(input("enter the value of b"))
import pyttsx3
engine= pyttsx3.init()
engine.say("enter the QTy z")
engine.runAndWait()


z =int(input("enter the QTY z"))

import pyttsx3
engine= pyttsx3.init()
engine.say("total price is")
engine.runAndWait()


print(a+x+b+z)
x = a*x
z = b*z
print("x= ",x)
print("z= ",z)
total = x+z

print("total price is=",total)
