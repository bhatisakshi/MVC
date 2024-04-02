## Python Task Manager
A simple, yet effective, Python project to manage tasks using the Model-View-Controller (MVC) architectural pattern. This application allows users to add tasks and view a list of all tasks. It's designed to demonstrate basic Python programming concepts and the MVC design pattern.

### Description
This project is a straightforward Python application that implements the MVC pattern to manage tasks. It consists of three main components:

Model (TaskModel): Manages the application's data. It stores tasks in a list and provides methods to add tasks and retrieve the list of tasks.
View (TaskView): Responsible for displaying information to the user. It can display a list of tasks.
Controller (TaskController): Acts as an intermediary between the Model and the View. It processes user inputs (e.g., adding a task), updates the Model, and updates the View to reflect changes in the Model.
This setup provides a clean separation of concerns, making the code more modular, easier to manage, and scalable.

## Getting Started
### Dependencies
Python 3.10.12

### Installing
Copy the provided Python code into separate files: model.py, view.py, controller.py, and main.py within the same directory. The main.py file will contain the combined code to initiate and use the MVC components.
No special modifications are required for the files or folders.

### Executing Program
To run the program, navigate to the directory containing the files and run the main.py file with Python. Follow these steps:

Open your terminal or command prompt.
Navigate to the directory containing your files.
Run the program using Python:
bash
Copy code
python main.py
This will start the application, and you will see the tasks being added and displayed in the console output. You can modify main.py to add or change tasks as desired.

### Step-by-step:
The program initiates by creating instances of the TaskModel, TaskView, and TaskController classes.
It then adds tasks using the add_task method of the TaskController instance.
Each time a task is added, the TaskController updates the view, displaying the current list of tasks.
Extending the Program
This program can be extended in numerous ways, such as adding functionality to remove tasks, mark tasks as completed, or even save tasks to a file or database. The MVC architecture makes it easier to extend the functionality without affecting other components of the application.







