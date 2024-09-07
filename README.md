name = "Bathani Avnish"

print(f"Hello, {name}!")
name = input("What is your name? ")
print(f"Hello, {name}!")

import math

radius = float(input("Enter the radius of the circle: "))

area = math.pi * radius ** 2

print(f"The area of the circle with radius {radius} is {area:.2f}")


def rectangle_properties():

    length = float(input("Enter the length of the rectangle: "))
    width = float(input("Enter the width of the rectangle: "))


    perimeter = 2 * (length + width)
    area = length * width


    print(f"The perimeter of the rectangle is: {perimeter}")
    print(f"The area of the rectangle is: {area}")

rectangle_properties()
