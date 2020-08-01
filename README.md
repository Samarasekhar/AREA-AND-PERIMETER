# AREA-AND-PERIMETER
I have code the area and perimeter of square,rectangle ,rhombus and parallogram
#SQUARE
print("Enter 'x' for exit.");
side = input("Enter side length of Square: ");
if side == 'x':
    exit();
else:
    side_length = int(side);
    area_square = side_length*side_length;
    print("\nArea of Square =",area_square);
    side_length = int (side);
    perimeter_square =4*side_length;
    print ("\nperimeter of Square =",perimeter_square)
    
    
 #RECTANGLE
    
l=int(input("Length : "))
w=int(input("Width : "))
area=l*w
perimeter=2*(l+w)
print("Area of Rectangle : ",area)
print("Perimeter of Rectangle : ",perimeter)


#Rhombus

from math import sqrt, pow
d1=float(input("digonal 1 : "))
d2=float(input("digonal 2 : "))
area = (d1 * d2) / 2
perimeter = 2 * sqrt(pow(d1, 2) +  pow(d2, 2)) 
print("Area of Rhombus : ",area )
print("Perimeter of Rhombus  : ",perimeter)




#PARALLOGRAM

base = float(input('Length of base: '))
height = float(input('Measurement of height: '))
area = base * height
perimeter =2*(base + height)
print("Area OF PARALLOGRAM : ", area)
print("Perimeters OF PARALLOGRAM is :",perimeter )
