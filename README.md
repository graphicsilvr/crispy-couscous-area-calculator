# Polygon Area Calculator

This is the boilerplate for the Polygon Area Calculator project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/scientific-computing-with-python/scientific-computing-with-python-projects/polygon-area-calculator

Shape area are are Calculator
The Shape area Calculator is a Python program that can calculate the area, perimeter, and diagonal of rectangles and squares, and determine how many smaller Shape areas can fit inside larger Shape areas.

# Getting Started
Prerequisites
To run the Shape area Calculator, you'll need to have Python 3 installed on your computer. You can download Python from the official website here.

# Installation

1. Clone the repository to your local machine:
bash

git clone https://github.com/graphicsilvr/crispy-couscous-area-calculator.git

2. Navigate to the project directory:
bash

cd Shape area-calculator

3. Run the program:
css

python main.py

# Usage
The Shape area Calculator allows you to create instances of Rectangle and Square objects, and perform various calculations on them.

# Creating Shape areas
To create a Rectangle object, you'll need to specify its width and height:

python
from Shape area_calculator import Rectangle
rect = Rectangle(3, 6)

# To create a Square object, you'll need to specify its side length:

python
from Shape area_calculator import Square
sq = Square(5)

# Calculating Properties
Once you've created a Shape area, you can use its methods to calculate its properties:

python

# Area
area = rect.get_area()
area = sq.get_area()

# Perimeter
perimeter = rect.get_perimeter()
perimeter = sq.get_perimeter()

# Diagonal
diagonal = rect.get_diagonal()
diagonal = sq.get_diagonal()
Calculating Amounts
You can also use the get_amount_inside() method to determine how many smaller Shape areas can fit inside a larger Shape area:

python
# Get amount of squares that can fit inside a rectangle
amount = rect.get_amount_inside(sq)
Outputting Shape areas
To output a string representation of a Shape area, you can use the __str__() method:

python
# String representation of a rectangle
rect_str = str(rect)

# String representation of a square
sq_str = str(sq)

# Here's an example program that creates a rectangle and a square, and calculates their properties:

python
from Shape area_calculator import Rectangle, Square

rect = Rectangle(3, 6)
sq = Square(5)

print("Rectangle:")
print("Area:", rect.get_area())
print("Perimeter:", rect.get_perimeter())
print("Diagonal:", rect.get_diagonal())
print()

print("Square:")
print("Area:", sq.get_area())
print("Perimeter:", sq.get_perimeter())
print("Diagonal:", sq.get_diagonal())
print()
Output:

# makefile

Rectangle:
Area: 18
Perimeter: 18
Diagonal: 6.708203932499369

Square:
Area: 25
Perimeter: 20
Diagonal: 7.0710678118654755

Running Tests
# The Shape area Calculator includes a set of unit tests in test_module.py. To run the tests, simply run:
python test_module.py

# Contributing
If you find a bug or have a suggestion for a new feature, feel free to open an issue or submit a pull request!

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.