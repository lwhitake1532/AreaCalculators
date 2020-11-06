# AreaCalculators
def calculator():
    areacalculator = input("enter shape name")
    areacalculator =str(areacalculator)

   if areacalculator == "rectangle":
        print("Area of rectangle is",rectangle())
    elif areacalculator == "square":
        print("Area of square is ",square())
    elif areacalculator == "triangle":
        print("Area of triangle is ",triangle())
    elif areacalculator == "circle":
        print("Area of circle is ",circle())
    else:
        print("try again please")

def rectangle():
    width, length = int(input("Enter the width of rectangle")) ,int(input("Enter the length of rectangle"))
    area=width*length
    return (area)

def square():
    side = int(input("enter the side of the square"))
    area=side*side
    return(area)

def triangle():
    base, height = int(input("Enter the base of the triangle")) ,int(input("Enter the height of triangle"))
    area=base*height/2
    return(area)
def circle():
    radius = int (input("Enter the radius of the circle"))
    area=3.141592*radius**2
    return(area)
calculator()
