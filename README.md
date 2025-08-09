# e-Portfolio - Anthony Baratti
====Contents====
[CS-499 Computer Science Capstone Project SNHU](#cs-499-computer-science-capstone-project-snhu)

## CS-499 Computer Science Capstone Project SNHU
### Table of Contents
-[View GitHub Page](https://anthonybaratti.github.io/)<br>
-[Full Project Code Review (Binary Search Tree & MongoDB Dashboard)](#code-review-for-cs-499-capstone-artifact-enhancements)<br>
-[Enhancement One](#enhancement-one)<br>
-[Enhancement Two](#enhancement-two)<br>
-[Enhancement Three](#enhancement-three)<br>
### Project Description
The project requires 3 enhancements of artifacts from the software engineering program at Southern New Hampshire University
The artifacts chosen must be enhanced to meet: 
1. Software Engineering & Design
2. Data Structures & Algorithms
3. Databases

Two artifacts were chosen to perform these enhancements:
1. Binary Search Tree conversion into an AVL self-balancing tree with added user functionality
2. Animal Shelter Dashboard using MongoDB and Python script conversion to SQLite

### Code Review for CS-499 Capstone Artifact Enhancements
The code review will explain the purpose of both original artifacts, showcasing the code and its functionality.  
It will also assess the code for vulnerabilities or flaws, reviewing concepts such as structure, documentation/readability, variables/naming conventions, arithmetic operations, loops, branches, and defensive/secure programming.  
Then the enhancements are explained, forming a relationship between the skills used and the outcomes achieved for the course by the artifact enhancements.
<br><br>
[Full Project Code Review (Binary Search Tree & MongoDB Dashboard)](https://www.youtube.com/embed/KDOPncTitjU)

### ENHANCEMENT ONE
This enhancement takes the original Binary Search Tree program, which is designed to load courses from a 
.csv file and push them into a binary search tree data structure (this makes search time complexity O(log n)).
The enhancement performed allows a user to create a custom course from the menu options as well as delete a course
from the Binary Search Tree list.
<br> <br>
[Binary Search Tree Enhancement One](https://github.com/AnthonyBaratti/EnhancementOne)
<br> <br>
====Enhancement One Contents==== <br>
- Original BinarySearchTree C++ Program <br>
- Enhanced BinarySearchTree C++ Program with user functionality <br>
- README file <br>
- Artifact Enhancement Narrative

### ENHANCEMENT TWO
This enhancement takes the Binary Search Tree one step further. The added user functionality could
destabilize the tree (making it unbalanced, or "heavy"), degrading the search time complexity from 
O(log n) to O(n). Creating self-balancing algorithms helps maintain the search time complexity at O(log n)
while deletes and inserts are being performed.
<br> <br>
[Binary Search Tree Enhancement Two](https://github.com/AnthonyBaratti/EnhancementTwo)
<br><br>
====Enhancement Two Contents==== <br>
- Original BinarySearchTree C++ Program <br>
- Enhanced BinarySearchTree C++ Program with self-balancing algorithms <br>
- README file <br>
- Artifact Enhancement Narrative

### ENHANCEMENT THREE
This enhancement takes a user dashboard for filtering animal types and displaying them in a data table with a selectable  
row. The filtered data is also displayed in a pie chart as well as a geo-location interactive map. The original artifact  
uses CRUD operations with MongoDB via two python scripts, one for the CRUD operations and one for the Dash layout. The  
enhancement will convert the database from online MongoDB to offline local storage using SQLite 3.
<br> <br>
[Animal Shelter Dashboard Enhancement Three](https://github.com/AnthonyBaratti/EnhancementThree)
<br> <br>
====Enhancement Three Contents==== <br>
- Original AnimalShelterArtifact Python Program using MongoDB <br>
- Enhanced AnimalShelterArtifact Python Program using SQLite3 with main.exe <br>
- README file<br>
- Artifact Enhancement Narrative<br>
- Grazioso Salvare Application v1.0 (dist.zip)
