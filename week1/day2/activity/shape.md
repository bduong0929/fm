# Shape Activity

This activity demonstrates how inheritance can be used to create a hierarchy of shapes. It also sorts the shapes based on their perimeter or area.

## Classes

The activity defines three classes:

* `Shape` is the base class. It has methods for calculating the area and perimeter of a shape.
* `Circle` is a subclass of `Shape`. It has a method for calculating the circumference of a circle.
* `Rectangle` is a subclass of `Shape`. It has a method for calculating the diagonal of a rectangle.

## Main Method

The main method of the activity creates objects of each of the subclasses and calls the appropriate methods. It also sorts the shapes based on their perimeter or area.

## Instructions

1. Create a class called `Shape`.
2. The `Shape` class should have two protected fields: `area` and `perimeter`.
3. The `Shape` class should have two public methods: `getArea()` and `getPerimeter()`.
4. Create a subclass called `Circle` that inherits from `Shape`.
5. The `Circle` class should have a private field called `radius`.
6. The `Circle` class should override the `getArea()` and `getPerimeter()` methods to calculate the area and perimeter of a circle.
7. Create a subclass called `Rectangle` that inherits from `Shape`.
8. The `Rectangle` class should have two private fields: `width` and `height`.
9. The `Rectangle` class should override the `getArea()` and `getPerimeter()` methods to calculate the area and perimeter of a rectangle.
10. Create a main method that prompts the user to enter the sizes for the shapes. Create objects of the `Circle` and `Rectangle` classes and calls the appropriate methods. Sort the shapes based on their perimeter or area.

## Output

The output of the activity should show how the subclasses inherit the methods from the base class, but they can also have their own unique methods. It should also show how the shapes are sorted based on their perimeter or area.
