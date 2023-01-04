Python: More Classes and Objects

0. Simple rectangle

0-rectangle.py: Empty Python class that defines a rectangle.

1 Real definition of a rectangle

1-rectangle.py: Python class that defines a rectangle. Builds on 0-rectangle.py

2. Area and Perimeter

2-rectangle.py: Python class that defines a rectangle. Builds on 1-rectangle.py

3. String representation

3-rectangle.py: Python class that defines a rectangle. Builds on 2-rectangle.py

4. Eval is magic

4-rectangle.py: Python class that defines a rectangle. Builds on 3-rectangle.py with:

Special method __repr__ to return a string representation of the rectangle.

5. Detect instance deletion



5-rectangle.py: Python class that defines a rectangle. Builds on 4-rectangle.py with:

Special method __del__ that prints the message Bye rectangle... when a Rectangle is deleted.

6. How many instances



6-rectangle.py: Python class that defines a rectangle. Builds on 5-rectangle.py with:

Public class attribute number_of_instances that is initialized to 0, incremented for each new instantiation, and decremened for each instance deletion.

7. Change representation



7-rectangle.py: Python class that defines a rectangle. Builds on 6-rectangle.py with:

Public class attribute class_symbol that is initialized to # but can be any type - used as the symbol for string representation.

8. Compare rectangles



8-rectangle.py: Python class that defines a rectangle. Builds on 7-rectangle.py with:

Static method def bigger_or_equal(rect_1, rect_2): that returns the rectangle with the greater area (returns rect_1 if both areas are equal).

If either of rect_1 or rect_2 is not a Rectangle instance, a TypeError is raised with the message rect_1 must be an instance of Rectangle or rect_2 must be an instance of Rectangle.

9. A square is a rectangle



9-rectangle.py: Python class that defines a rectangle. Builds on 8-rectangle.py with:

Class method def square(cls, size=0): that returns a new Rectangle instance with width == height == size.

10. N Queens
101-nqueens.py: Python program that solves the N queens puzzle.
