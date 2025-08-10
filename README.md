# e-Portfolio Anthony Baratti
-[View GitHub Page](https://anthonybaratti.github.io/)<br>
#### Contents
- [CS-499 Computer Science Capstone Project SNHU](#cs-499-computer-science-capstone-project-snhu)
- [CS-370 Current & Emerging Trends in CS](#cs-370-current-and-emerging-trends-in-computer-science-artificial-intelligence)
- [CS-360 Mobile Architecture & Programming](#cs-360-mobile-architecture-and-programming)
- [CS-350 Emerging Systems Architecture](#cs-350-emerging-systems-architecture)
- [CS-320 Software Testing](#cs-320-software-testing)

<br><br>
## Professional Assessment
Insert professional assessment here

## CS-499 Computer Science Capstone Project SNHU
### Capstone Table of Contents
-[Full Project Code Review (Binary Search Tree & MongoDB Dashboard)](#code-review-for-cs-499-capstone-artifact-enhancements)<br>
-[Enhancement One](#enhancement-one)<br>
-[Enhancement Two](#enhancement-two)<br>
-[Enhancement Three](#enhancement-three)<br>
-[Course Outcome Completion](#course-outcome-completion)<br>

### Project Description
The project requires 3 enhancements of artifacts from the software engineering program at Southern New Hampshire University. <br>
The artifacts chosen must be enhanced to meet: 
1. Software Engineering & Design
2. Data Structures & Algorithms
3. Databases

The artifacts must also meet the course outcomes:
1.  Employ strategies for building collaborative environments that enable 
diverse audiences to support organizational decision-making in the field of 
computer science.  

2.	Design, develop, and deliver professional-quality oral, written, and 
visual communications that are coherent, technically sound, and appropriately 
adapted to specific audiences and contexts.  

3.	Design and evaluate computing solutions that solve a given problem 
using algorithmic principles and computer science practices and standards 
appropriate to its solution while managing the trade-offs involved in design 
choices.  

4.	Demonstrate an ability to use well-founded and innovative techniques, 
skills, and tools in computing practices for the purpose of implementing computer 
solutions that deliver value and accomplish industry-specific goals.

5.	Develop a security mindset that anticipates adversarial exploits 
in software architecture and designs to expose potential vulnerabilities, 
mitigate design flaws, and ensure privacy and enhanced security of data and 
resources.  

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
#### Software Engineering & Design
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
#### Data Structures & Algorithms
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
#### Databases
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
- Grazioso Salvare Application v1.0 (dist.zip)<br>

### Course Outcome Completion
#### Enhancement One
_Binary Search Tree User Functionality showcases skill sets that align with these course outcomes:_<br>
(1). Being able to articulate  the features advantages and disadvantages (such as search time complexity vs. overhead) between the data structures (BST vs. AVL) can help support decision-making in the computer science field. For example, an AVL tree requires more overhead (extra resources due to more work being performed), and is useful if there are a lot of adding and deleting of nodes, whereas a standard BST is useful for quick searches if it is prebalanced and will not be modified (adding or deleting nodes). Since we will be adding user functionality to accomodate usefulness, these comparisons must be addressed.<br><br>
(3). Understanding the design and implementation of search trees is vital for determining when to develop specific structures. Moreover, the trade-offs are case-appropriate. For example, if we are going to populate the tree once and never modify it, then an AVL tree may not be the best solution. If our data is extrememly unbalanced (an example would be that the first "root" node is last in an alphabetical list, then all proceeding nodes will be down the left branch with no right branch) a BST would not be the proper solution. Understanding the case allows us to evaluate and design a solution to solve the given problem using the appropriate algorithmic standards. <br><br>
(4). Understanding and planning are important skills to possess. Being able to create universal pseudocode that can be modified to fit any programming language is a great way to showcase using well-founded and innovative techniques that can help accomplish industry-specific goals. <br><br>
(5). Validating user input to ensure that it is accurate (or denying it when it is not) is one of many solutions concerning security. Ensuring that proper input has been received (such as ensuring that the courses object has at LEAST a name and ID) can help prevent out of bounds access of objects in the tree. With data validation techniques, we can demonstrate security awareness to reduce vulnerabilities. Encapsulating data is also a skill that is helpful (such as wrapping many private functions in a few accessible public functions) in keeping the logic hidden, only exposing what is necessary to the public facing side of the application. This helps reduce potential exploitation of the code, keeping variables in their appropriate scope so that the data is not exposed or accessed unnecessarily (intentionally or not).
#### Enhancement Two
Self-balancing AVL structure showcases skill sets that align with these course outcomes: <br>

#### Enhancement Three
[Final Artifact Update](https://github.com/AnthonyBaratti/AnthonyBaratti.github.io/blob/main/Final%20Artifact%20Update.pdf)  
[Back to e-Portfolio Contents](#e-portfolio-anthony-baratti)

## CS-370 Current and Emerging Trends in Computer Science (Artificial Intelligence)
TODO:
- [ ] Refine C&E trends page
- [x] Add C&E Trends to e-portfolio
- [ ] Describe C&E trends on e-portfolio
- [ ] Add C&E trends to github page as a project

[Artificial Intelligence Project](https://github.com/AnthonyBaratti/CS-370-Current-Emerging-Trends-in-CS/tree/main)<br>
[Back to e-Portfolio Contents](#e-portfolio-anthony-baratti)

## CS-360 Mobile Architecture and Programming
TODO:
- [ ] Refine Mobile A&P systems page
- [x] Add Mobile A&P to e-portfolio
- [ ] Describe Mobile A&P on e-portfolio
- [ ] Add Mobile A&P to github page as a project

[Mobile Architecture Project](https://github.com/AnthonyBaratti/CS-360-Mobile-Architecture-Programming)<br>
[Back to e-Portfolio Contents](#e-portfolio-anthony-baratti)

## CS-350 Emerging Systems Architecture
TODO:
- [ ] Refine Emerging systems page
- [x] Add Emerging Systems to e-portfolio
- [ ] Describe emerging systems on e-portfolio
- [ ] Add emerging systems to github page as a project

[Micro-Controller Project](https://github.com/AnthonyBaratti/CS-350-Emerging-Systems-Architecture)<br>
[Back to e-Portfolio Contents](#e-portfolio-anthony-baratti)

## CS-320 Software Testing
TODO:
- [ ] Refine Software testing page
- [x] Add Software testing to e-portfolio
- [ ] Describe software testing on e-portfolio
- [ ] Add software testing to github page as a project

[Software Testing Project](https://github.com/AnthonyBaratti/CS-320-Software-Testing)<br>
[Back to e-Portfolio Contents](#e-portfolio-anthony-baratti)

