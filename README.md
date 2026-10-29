# To-Do App

A command-line to-do app in Python that saves your tasks between runs.

## Features
- Add, view, complete, and delete tasks
- Tasks are saved between runs
- Bad input does not crash it

## Requirements
- Python 3 (no extra packages)

## How to Run
```bash
python todo.py
```

## Example Session
```
1. Add
2. View
3. Complete
4. Delete
5. Quit
Enter your choice: 1
Enter your task: buy milk
Added

1. Add
2. View
3. Complete
4. Delete
5. Quit
Enter your choice: 1
Enter your task: study python
Added

1. Add
2. View
3. Complete
4. Delete
5. Quit
Enter your choice: 3
1. [ ] buy milk
2. [ ] study python

Task number to complete: 1
Completed

1. Add
2. View
3. Complete
4. Delete
5. Quit
Enter your choice: 2
1. [x] buy milk
2. [ ] study python


1. Add
2. View
3. Complete
4. Delete
5. Quit
Enter your choice: 5

```

## How It Works
tasks are a list of dictionaries, saved to todos.json after every change, loaded at startup.