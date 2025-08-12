# 📝 Java GUI – ToDo App

## 📌 Objective
A simple **To-Do List Application** built using **Java Swing** that allows users to **add** and **delete** tasks with a clean and interactive GUI.

---

## 🛠 Tools & Technologies
- **Java** (JDK 8 or later)
- **Swing** (Java built-in GUI framework)
- **IDE**: IntelliJ IDEA Community Edition / Eclipse


## 🚀 Features
- Add new tasks using a text field and button  
- Delete selected tasks from the list  
- Responsive and user-friendly interface using Java Swing components  
- Tasks displayed dynamically in a `JList`

---

## 📂 Project Structure
ToDoApp/
│── src/
│ └── ToDoApp.java # Main application file
│── README.md


## 💻 Implementation Guide
1. **Create Main Window**
   - Use `JFrame` for the main window
   - Set layout, size, and close operation

2. **Add Components**
   - `JTextField` → For entering tasks
   - `JButton` → "Add Task" and "Delete Task"
   - `JList` → Display tasks in a list format
   - `DefaultListModel` → Store and manage tasks dynamically

3. **Add Functionality**
   - **Add Task**: When "Add" is clicked, text from the field is added to the list
   - **Delete Task**: When "Delete" is clicked, selected task(s) are removed
