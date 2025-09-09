Project: number-display
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class NumberDisplay. Then inspect this 
instance and leave the inspector window open. With the inspector window open, 
call the object's methods, such as increment and setValue.

part i:
1. class diagrams represent static (non-changing) things (classes) and the relations between them, whereas object diagrams represent non-static (changing) things (objects), their relations, and their information
2. when a new class is written, or methods are modified, it changes by the arrows between them changing
3. when methods are called or objects are created, it changes by what is visible in the diagram
4. 'public Instructor tutor;'
6. check if the minutes rolled over, if yes, then hours should be incremented
8. no, only the first one made a change, this is becuase theres a check on the setValue() method to make sure it doesnt get set to a value higher than the limit 
10. Error: non-static method getValue() cannot be referenced from a static context
