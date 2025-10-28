
# Java GUI – ToDo App

## Project Description
The ToDo App is a simple Java Swing-based desktop application that allows users to add and delete tasks. It demonstrates the use of Swing components, event handling, and layout management in Java GUI development.

### Objective
Build a To-Do list using Java Swing that performs basic task management operations.

### Tools Used
- Java  
- Swing (built-in GUI toolkit)  
- IntelliJ IDEA Community Edition or Eclipse  

### Deliverables
A fully functional Java GUI application that supports adding and deleting tasks from a list.

---

## Features
- Add tasks to a list  
- Delete selected tasks  
- Scrollable task list using `JScrollPane`  
- Simple and clean GUI layout  

---

## How to Run
1. Save the code as `ToDoApp.java`.  
2. Open a terminal in the project directory.  
3. Compile the file:  
   ```bash
   javac ToDoApp.java

4. Run the program:

   ```bash
   java ToDoApp
   ```
5. The ToDo App window will open where you can add or delete tasks.

---

## Key Concepts

* Swing Components (`JFrame`, `JPanel`, `JButton`, `JTextField`, `JList`, `JScrollPane`)
* Event Handling using `ActionListener`
* Layout Management (`BorderLayout`, `GridLayout`)
* DefaultListModel for dynamic task management

---

## Interview Questions and Answers

### 1. What is Swing?

Swing is a Java GUI toolkit that provides lightweight components for building desktop applications.

### 2. Difference between AWT and Swing?

AWT is platform-dependent and uses native components, while Swing is platform-independent and provides more flexible, lightweight components.

### 3. What is ActionListener?

`ActionListener` is an interface used to handle action events, such as button clicks.

### 4. How to manage layouts in Java?

Layouts are managed using layout managers like `BorderLayout`, `FlowLayout`, and `GridLayout` to control component placement.

### 5. What is the Event Dispatch Thread?

The Event Dispatch Thread (EDT) is a special thread that handles all GUI updates and event processing in Swing.

### 6. What are the GUI components in Java?

Common GUI components include `JButton`, `JLabel`, `JTextField`, `JList`, `JPanel`, and `JFrame`.

### 7. How to handle multiple events?

You can register multiple event listeners or use anonymous inner classes or lambda expressions to handle different events.

### 8. What is JPanel vs JFrame?

`JFrame` represents the main window, while `JPanel` is a container used to organize and group components within the frame.

### 9. How to add scroll bar in GUI?

A scrollbar can be added by wrapping components inside a `JScrollPane`, for example: `new JScrollPane(JList)`.

### 10. What is MVC architecture?

MVC (Model-View-Controller) separates an application into three layers: Model (data), View (UI), and Controller (logic), improving modularity and maintainability.




