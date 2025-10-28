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
<img width="1147" height="925" alt="image" src="https://github.com/user-attachments/assets/19fe181a-2f73-463c-b3fe-3ccee0f8f877" />

<br>

#### CLASS DIAGRAM:
<img width="832" height="597" alt="image" src="https://github.com/user-attachments/assets/83bbf7f5-e47f-44ef-b380-875308cb4025" />

<br>

#### SEQUENCE DIAGRAM:
<img width="1225" height="947" alt="image" src="https://github.com/user-attachments/assets/b5d05f7a-f2cb-4d56-9c40-384e15abf178" />

<br>

#### COMMUNICATION DIAGRAM:
<img width="881" height="756" alt="image" src="https://github.com/user-attachments/assets/d6eeed0f-bfa0-44d0-9edb-b2afa8968d0b" />

<br>

#### ACTIVITY DIAGRAM:
<img width="1214" height="939" alt="image" src="https://github.com/user-attachments/assets/f9157bd3-29d2-4d6f-a18f-2ce66fecd39c" />

<br>

#### PACKAGE DIAGRAM:
<img width="1197" height="903" alt="image" src="https://github.com/user-attachments/assets/5d279022-34f3-4c13-a810-dee7406eaa10" />

<br>
### RESULT:
Thus the Library management system project was executed and the output was verified.
