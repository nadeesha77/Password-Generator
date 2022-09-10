
print("♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦ AD Password Generator ♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦")                 
                                                   

print()
x = str(input(" •Enter Your Name(..without spaces..) : ")) 
y = int(input(" •Your Birth Year : "))  
z = str(input(" •A word  Of Your Choice : "))  

import math
x1 = x[0:6]
x2 = (x.capitalize())
y1 = y*112/100+2-6+1-3.86
y2 = math.trunc(y1)

pro = ("%s%d@%s#$"%(x2,y2,z))
print()
print(" ♥your passworld is =", pro)
print("  This is strong password!")
