Simple To-Do List Manager
A lightweight and interactive to-do list manager created using Batch scripting. This program allows you to add, view, and remove tasks from your to-do list directly from the command line.

Features
View Tasks: Display all tasks in your to-do list.
Add Tasks: Quickly add new tasks to your to-do list.
Remove Tasks: Delete tasks from your to-do list by selecting their number.
Persistent Data: Tasks are saved in a text file and persist across program runs.
How It Works
The program manages tasks using a text file (todo.txt) stored in the project directory. Each time you add or remove tasks, the list is updated and saved.

The main menu provides options for:

Viewing the current tasks.
Adding a new task to the list.
Removing an existing task by its index number.
Exiting the program.
Requirements
Windows Operating System (works with any version of Windows).
No external software dependencies (runs purely on the Windows command line).

Getting Started
Clone the Repository
First, clone the repository to your local machine:

bash
Kopieren
Bearbeiten
git clone https://github.com/your-username/simple-todo-list-manager.git
cd simple-todo-list-manager
Running the Program
To run the program, simply double-click on the todo_manager.bat file, or run it from the command line:

bash
Kopieren
Bearbeiten
todo_manager.bat
Using the To-Do List Manager
View Tasks: Select option 1 to see the list of tasks.
Add Task: Select option 2 to add a new task. Enter the task description when prompted.
Remove Task: Select option 3 to remove a task. You'll be asked to enter the task number (which appears when you view tasks).
Exit: Select option 4 to exit the program.
Data Persistence
The tasks are saved to the todo.txt file in the same directory as the batch file. This file will persist across program runs, so your tasks will be saved even after closing the application.

Example Workflow
When you run the script, the main menu will display:

markdown
Kopieren
Bearbeiten
*** To-Do List Manager ***
1. View tasks
2. Add task
3. Remove task
4. Exit
Choose an option:
After selecting 1, you will see the current list of tasks:

markdown
Kopieren
Bearbeiten
*** Tasks ***
1. Buy groceries
2. Complete project report
3. Call mom
If you select 2 to add a new task, you'll be prompted to enter the task description, such as "Finish homework". This will add the new task to the list.

If you select 3 to remove a task, you will be asked for the task number (e.g., 2 to remove "Complete project report").
