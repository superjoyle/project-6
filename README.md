# project-6
About/Overview:
The Monkey Sanctuary Management System is a program designed to manage a sanctuary for various species of monkeys. The system allows users to add new monkeys to the sanctuary, move them to different enclosures based on their species, provide medical attention when needed, and view details about monkeys in isolation and enclosures.

List of Features:
Add Monkey: Users can add new monkeys to the sanctuary by providing their details such as name, species, sex, size, weight, age, and favorite food.
Move to Enclosure: Monkeys can be moved from isolation to specific enclosures based on their species.
Provide Medical Attention: Users can provide medical attention to monkeys, potentially moving them back to isolation if necessary.
View Enclosures: The program displays details about monkeys housed in different enclosures based on species.
View Isolation Capacity: Users can see the current capacity of the isolation facility.
View All Monkeys: The system provides a list of all monkeys in the sanctuary, sorted alphabetically by name.

How To Run:
Running the Jar File:
To run the program, execute the jar file using the command java -jar MonkeySanctuary.jar.
The program requires no additional arguments.

How to Use the Program:
Adding a Monkey:

Enter the monkey's details in the respective text fields (name, sex, size, weight, age, favorite food).
Click the "Add Monkey" button to add the monkey to the sanctuary.
Moving a Monkey to an Enclosure:

Select a monkey from the dropdown list.
Select the species of the enclosure to move the monkey.
Click the "Move to Enclosure" button to move the monkey.
Providing Medical Attention:

Select a monkey from the dropdown list.
Click the "Provide Medical Attention" button to provide medical attention to the monkey.
Viewing Enclosure Details:

The details of monkeys in different enclosures are displayed in the text area.
Viewing Isolation Capacity:

The current isolation capacity is displayed at the top of the GUI.
Viewing All Monkeys:

The list of all monkeys in the sanctuary is displayed on the right side of the GUI.

Design/Model Changes:
Enclosures Management: Changed the enclosuresMap in MonkeySanctuaryModel to store a list of monkeys directly, simplifying the management of monkeys in enclosures.
GUI Updates: Updated the GUI in MonkeySanctuaryView to include functionality for adding monkeys and viewing all monkeys in alphabetical order.

Assumptions:
The program assumes a graphical user interface (GUI) for user interaction.
It assumes that the user has basic knowledge of adding monkeys, moving them to enclosures, and providing medical attention.
The program assumes a maximum capacity of 20 monkeys in isolation.
The enclosures can house an unlimited number of monkeys, but the isolation facility has a capacity limit.
Favorite food options are predefined and selected from a dropdown menu.
These assumptions guide the functionality and usability of the Monkey Sanctuary Management System.

Limitation: 
After adding a group of monkeys, the list of all monkeys may contain duplicates, which can also impact the isolation capacity.

Citations:
n/a