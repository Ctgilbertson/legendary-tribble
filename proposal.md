# X-Team 110 Project Desk Organizer Proposal

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
We decided to tackle the problem of losing things in a desk after you put them in a drawer. It is hard for people to keep track of where they have put things so being able to keep track of where they were put and being able to do a search of the entire desk would be very helpful.

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

We would use an array to store all the drawers of a desk becasue they don't change. Inside each Array element would be a BST that would hold all of the elements in the drawer in alphabetical order so we can search by name each item. And in the main.java could include put method which set the name of the book into the BST in alphabetical order; search method which can search for the name of the item and return whether it has been searched or not.  

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Desk Organizer

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

User would get the drawer that the item is in after searching for the item. It would also tell if the item isn't in the desk at all. i.e. {Item Name} Is stored in {Drawer Name}. 
             {Item Name} is not stored in desk.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

At start user would need to give the layout of the desk and name the drawers. After, the user would have to input each item they put into the desk and which drawer the item was placed. When the user wants to find an item thety would have to give a name of the item they're looking for.
i.e. Desk has 4 drawers named 1, 2, 3, 4.
     Put item pencil in drawer 3.
     Search for pencil.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
Use text menu to tell user what drawer item is in. Menu would have options: Build New Desk, Put In Item, Search For Item, Rename Drawer, Remove Item, List All Items In Each Drawer, Switch Desk


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

Items: contain the name of the item to calculate its priority.
Drawer: implements a BST of item nodes based on alphabetical order. Each drawer would have a custom name. 
Desk: Stores the root of each drawer into an array of drawer objects. Desk would have a name and array would be the size of how many drawers there are.
DeskOrganizerADT: operations the user could perform. i.e. put, search, remove 
DeskOrganizer: Implementation of DeskOrganizerADT using data structures described earlier.

Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

