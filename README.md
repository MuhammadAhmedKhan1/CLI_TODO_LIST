# CLI_TODO_LIST
A simple command-line To-Do List Manager built with Python and Click, managed using UV package manager.

<h1>Install UV</h1>
First, install UV (if not already installed):<br>
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
<br>
Verify installation:
uv --version
<br>
Create and Initialize the Project
uv init todo-cli
cd todo-cli
<br>
 Install Click (Dependency)
 uv add click
<br>
 Activate UV Virtual Environment (Windows)
 .venv\Scripts\activate
<br>

  Run To-Do List Commands
<br>
➕ Add a New Task
uv run python todo.py add "Buy grocery for sehri and iftari"
<br>
 List All Tasks
 uv run python todo.py list
<br>

 Mark a Task as Completed
 uv run python todo.py complete 1

 Remove a Task
 uv run python todo.py remove 1
 
