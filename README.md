# Library-Management
### AIM:
To study the problem statement, SRS document and draw all the UML diagrams of a Library Management System.

<br>

### SRS(Procedure):
#### Usecase Diagram
- First, identify the **actors** (like `Librarian` and `Student`) and the **system boundary** (the "Library Management" box). Then, list all the **use cases** (functions like `Issue Book`, `Return Book`, `Search for Books`) inside the boundary and connect the actors to the functions they perform.

#### Class Diagram
- Identify the main **classes** (nouns like `Book`, `Member`, `Librarian`). For each class, define its **attributes** (data like `+bookID`, `+name`) and **methods** (actions like `+borrowBook()`). Finally, draw solid lines to show the associations (relationships) between the classes.

#### Activity Diagram
- Map the step-by-step **workflow** for a single use case (like borrowing a book) from a start node to an end node. Use **action boxes** for steps (`Search Books`), **diamond shapes** for decisions (`Book Available?`), and arrows to show the sequence of activities.

#### Sequence Diagram 
- Show how objects interact **over time** for one specific scenario (like "Issue Book"). Place the objects (`Librarian`, `Library System`, `Database`) as vertical **lifelines** across the top. Then, draw **numbered messages** from top to bottom to show the exact sequence of calls between them.

#### Communication Diagram
- This diagram shows the **relationships** between objects for a scenario (like "Checkout Book"). Place the objects (`Librarian`, `LibrarySystem`, `Member`, `Database`) on the diagram, draw links between them, and then add **numbered messages** along those links to show the sequence of communication.

#### Package Diagram
- Group related classes and functions into **packages** (like folders, e.g., `Members`, `Librarian`). This organizes your system into logical modules. Then, draw dashed arrows (dependencies) to show how these packages and other components (like `Library` or `Admin`) relate to each other.

<br>

### UML Diagrams:
#### USE CASE DIAGRAM:

![UseCaseDiagram1](https://github.com/user-attachments/assets/f2a9c303-ce1b-4c49-a94a-a3f798357623)

<br>

#### CLASS DIAGRAM:
![ClassDiagram1](https://github.com/user-attachments/assets/5bf15fd5-30fb-4930-96d7-182e989857de)


<br>

#### SEQUENCE DIAGRAM:
![SequenceDiagram1](https://github.com/user-attachments/assets/845a3f21-526d-4c30-a352-d6f7b70be5d4)


<br>

#### COMMUNICATION DIAGRAM:
![CommunicationDiagram1](https://github.com/user-attachments/assets/bda673ea-aa2d-454d-bd11-fda98d8bdc17)


<br>

#### ACTIVITY DIAGRAM:
![ActivityDiagram1](https://github.com/user-attachments/assets/d6d2087b-5679-465c-b7b5-6d7f4a3835b1)


<br>

#### PACKAGE DIAGRAM:
![PackageDiagram1](https://github.com/user-attachments/assets/5600a382-6f34-4f17-96d4-41a83417b8f4)


<br>

### RESULT:
Thus the Library management system project was executed and the output was verified.
