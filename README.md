# Task Manager CLI App

A simple **command-line task management system** built in Python for beginners.

---

##  Project Summary

The **Task Manager CLI App** is a console-based Python application designed to help users manage their daily tasks efficiently. It allows users to add, view, update, and delete tasks with ease through a user-friendly text-based menu. All data is saved persistently using a `.txt` file, making it lightweight and easy to run on any system.

###  Ideal For:
- Python beginners exploring file handling and CLI apps
- College assignments or mini-projects
- Personal productivity tracking (no external libraries)

---

##  Key Features

-  **Add Tasks**: Create tasks with a title, due date, and auto-status as “Pending”.
-  **View Tasks**: Display all tasks in a clean, numbered list with details.
-  **Update Tasks**: Edit task title, due date (with validation), or mark as Done/Pending.
-  **Delete Tasks**: Remove tasks by selecting their number from the list.
-  **File-Based Storage**: All tasks stored in `tasks.txt` using pipe `|`-separated format.
-  **Input Validation**: Enforces correct date format and prevents invalid selections.
-  **Looped Menu**: Keeps running until the user chooses to exit.

---

##  How It Works

### Adding a Task
- Prompts user for task title and due date.
- Validates date format (`YYYY-MM-DD`).
- Saves task with status **Pending** to `tasks.txt`.

###  Viewing Tasks
- Reads from `tasks.txt`.
- Displays:  
  - Task Number  
  - Title  
  - Due Date  
  - Status  

###  Updating Tasks
- User selects a task number to update.
- Options to edit:  
  - Title  
  - Due Date (with validation)  
  - Status (Pending or Done)

###  Deleting Tasks
- User selects the task number.
- Task is removed and file is updated.

###  Menu Interface
A looped 5-option menu:
1. Add Task  
2. View Tasks  
3. Update Task  
4. Delete Task  
5. Exit

---

##  Technical Details

| Item             | Description                         |
|------------------|-------------------------------------|
| **Language**     | Python 3.x                          |
| **IDE Options**  | Jupyter Notebook                    |
| **Storage**      | `.txt` file (`tasks.txt`)           |
| **Modules Used** | `os`, `datetime`                    |

---

##  Data Storage Format

Tasks are stored in a plain text file (`tasks.txt`) with the following format:

