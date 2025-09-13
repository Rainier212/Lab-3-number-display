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

ANSWERS TO QUESTIONS:

1- Class diagrams are persistent, meaning it saves its data even after being shutdown. However, the object diagram does not.

2- It changes when we compile the class diagram. We can change it by doing modifications in the source code of the class diagram.

3- When we create objects.

4- private Instructor tutor;

6- When = 0 zero increment should be called

8 - Yes, when I set the value to a certain number and called the getValue, it gives me same value I inputted earlier.

9- I predict that the returned value will be 10 when calling the getValue.I predicted incorrectly, but understand my istake. When setting the value to 10, and the limit we added was 10; the return value would be 0 since when it reaches 10, it would reset to 0.

10- Error: non-static method getValue() cannot be referenced from a static context

11- Error: '.class' expected 
We added int in the colons.
Correct way to call setValue would be the following: display.setValue(5);

13- 0 would be the only valid value that would no longer be accepted

14- I do not understand this question. :(

15- ! false
    (34 != 33) && ! false

16- (a == b)

17- (a != b)

18- A three-digit String is returned from a call to getDisplayValue.

19- Nope, it shows the same results.

20- The first expression will most likely be 12 + "cat", and the second one, "cat" + 12
    Result for 9 + 3 + “cat”: "12cat"
        -> This result really surprised me since "12cat" should've been 9+3 x "cat".
    Result for “cat” + 3 + 9: "cat39"
        -> I was way more surprised with this one. Apparently, we have to solve the expression from left to right. So it                would first be "cat" + 3, which results to "cat3". Then it's "cat3" + 9, which gives us "cat39". So we do not get            the sum of 3 and 9, but rather insert/glue them to "cat".
            

