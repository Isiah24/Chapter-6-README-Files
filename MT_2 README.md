# Math Tutor Program 2
This program will help grade school students practice math. Program should present the student with a menu that allows the choice of _addition_, _subtraction_, _multiplication_, _divison_ and the chocie to quit the program all together.

## Directions
Begin the program (by choosing a number between 1-5) after choosing a type of math the program will prompt you math questions telling you when they are **correct** or not. The problems will continue to loop and randomly generate until the user decides to quit by entering the number five as your input option.The program also keeps track of the amount of questions answered correctly and incorrectly.

## Variable(s)
(When my partner and I worked on this program we went about it in two different manners but came across the same solution so naturally we utilzed different variables and variable types.)

**(Partners Variables)**
_float_ printScore(int );

_int_ menu();

_int_ add();

_int_ sub();

_int_ mult();

_int_ div();

**(My Variables)** 
_int_ DoMenu();

_void_ addition(int random1, int random2, int& correct, int& total);

_void_ subtraction(int random1, int random2, int& correct, int& total);

_void_ multiplication(int random1, int random2, int& correct, int& total);

_void_ division(int random1, int random2, int& correct, int& total);
