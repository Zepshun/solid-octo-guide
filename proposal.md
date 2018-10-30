# X-Team 34 Seating Chart Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.
The program would create a seating chart utlizing given seating preferences.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
Seating Chart.

2. Output: Describe the output your program will produce.  Include an example format of the output produced.
The output of the program will provide an array in console-text form designating different people to different desks in a classroom.
The output could be a GUI including the person's last initial and first five letters of their first name separated by a comma, and all
of these names arranged in a matrix formation with their pictures.  i.e.:
T,Micha  T,Micha  T,Micha  T,Micha  T,Micha
T,Micha  T,Micha  T,Micha  T,Micha  T,Micha
T,Micha  T,Micha  T,Micha  T,Micha  T,Micha
T,Micha  T,Micha  T,Micha  T,Micha  T,Micha

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
First and foremost, we need all individuals' first and last names, obviously.  Then we'd ask them to give their seating preferences, or 
lack thereof.  If individuals prefer a certain area of the room to be seated, such as the front of the room, they should make that 
known.  If individuals wished to sit next to each other, they should both include each other's names in their preferences as well.
Preferences would be considered in the order in which they were submitted.  They would also need to provide pictures of themselves.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
The interface would be pretty simple, with a few text boxes/drop-down menus on a webpage for providing their input.  The output would be 
a simple GUI, printable, could be used for attendance/seating rearrangements.


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
- String conversion from first/last names to condensed graph version.
- Algorithm to sort preferences in order of submission.
- Algorithm to consider desired pairings of individuals next to each other.
- Print method.


Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

