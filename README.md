# Lab 30 - Grade Calculator GUI

### Introduction

In this lab you will be using a Tkinter GUI to calculate a semester average using user input.

### Instructions

Look at the example images.  Use your knowledge of Tkinter, the example picture, and the details below to create this GUI.

The user should be able to enter their two 9 weeks grades and their final exam grade, click the Calculate `Button` and have their semester average displayed in the `Label` at the bottom.

### Examples

!(./Example1.PNG)

!(./Example2.PNG)

### Details

* Each set of `Label` and `Entry` pairs should be in their own `Field`.
* Each `Field` should be 20 wide and have some sort of relief along the border (you can choose which one).
* The `Button` can be in a `Field`, or not, your choice.
* All `Field`s should have the same width so it looks nice.
* Set the window title using `window.title("Words For Title")`
* Add some color!  Make it look nicer than a flat grey application.
* In the example the `Entry` fields have a width of 5.
* After the user enters the three grades and clicks the `Button`, the `Label` beneath the "Semester Grade" `Label` should have its `text` property changed to hold the correct grade.
* Semester Grade = (1st + 2nd) / 2 \* 0.8 + Exam \* 0.2