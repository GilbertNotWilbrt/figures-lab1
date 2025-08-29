Project "figures"
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 1.

This is a very simple project to demonstrate some characteristics of
objects.

You can create various shapes, and you will see, if you do, that those
shapes are drawn on screen (in a window that we call the "canvas").

You can then manipulate these objects: change their position, size and 
colour. Try it out: create a few different squares, triangles and circles.

This project is designed as a first example of object-oriented programming.
It illustrates a number of concepts:

 - a Java project (application) is a collection of classes
 - objects can be created from classes
 - from any one class, many objects may be created
 - objects have operations (methods)
 - operations can have parameters
 - parameters have types (at least String and int)
 - objects hold data (fields)
 - the operations and fields are common to all objects
 - the values stored in the fields can be different for each object

The project also demonstrates

 - BlueJ object creation
 - interactive method invocation
 - parameter passing

A good second project to look at after this is "picture", which adds a class
to those ones in this project. That class (named "Picture") uses the shapes
to draw a picture. It can be used to experiment with coding.

Q.2 If you call moveDown twice it moves it down 40 pixels, 3 times, 60 pixels,
as when you call moveDown once it moves down 20 pixels, so 20 x 2 = 40, 20 x 3 = 60.

Q.6 Invoking changeColor changes the color to whatever you put withing quotes, given
that it is a valid color within BlueJ.
