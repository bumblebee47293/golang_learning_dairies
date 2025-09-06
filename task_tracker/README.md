# Task Tracker CLI

Build a simple command-line interface (CLI) app to **track your tasks** and manage your to-do list. Perfect for honing your programming skills in **filesystem operations**, **user input handling**, and **CLI development**.

**Project Brief:**

* Create an app that runs from the command line, using JSON files for task storage.
* Users should be able to add, update, delete tasks; mark them as in-progress or done; and filter/list tasks by status.
  ([roadmap.sh][1])

---

## Table of Contents

1. [Features](#features)
2. [Getting Started](#getting-started)
3. [Usage Examples](#usage-examples)
4. [Task Properties](#task-properties)
5. [Implementation Guidelines](#implementation-guidelines)
6. [Roadmap & Feedback](#roadmap--feedback)
7. [License](#license)

---

## Features

* Add, update, and delete tasks
* Mark a task's status: `todo`, `in-progress`, or `done`
* List tasks:
* All tasks
* Only done tasks
* Only in-progress tasks
* Only todo (not done) tasks
  ([roadmap.sh][1])

---

## Getting Started

1. **Clone the project** to your local machine and set up your environment.
2. **Initialize version control**, preferably with Git.
3. **Install requirements** (none external — use your language's standard library).
4. **Create the JSON storage file** automatically if it's not present.
   ([roadmap.sh][1])

---

## Usage Examples

```bash
# Add a new task
task-cli add "Buy groceries"
# Output: Task added successfully (ID: 1)

# Update a task
task-cli update 1 "Buy groceries and cook dinner"

# Delete a task
task-cli delete 1

# Change task status
task-cli mark-in-progress 1
task-cli mark-done 1

# List tasks
task-cli list
task-cli list done
task-cli list todo
task-cli list in-progress
```

([roadmap.sh][1])

---

## Task Properties

Each task stored in JSON should include:

* **id**: Unique identifier
* **description**: Brief task description
* **status**: `'todo'`, `'in-progress'`, or `'done'`
* **createdAt**: Timestamp when created
* **updatedAt**: Timestamp of last update
  ([roadmap.sh][1])

Ensure these are properly formatted and updated in your JSON storage file whenever changes occur.

---

## Implementation Guidelines

* Use **positional CLI arguments** to accept inputs.
* Rely only on your language’s **native filesystem module**.
* Avoid external libraries/frameworks, focusing on learning fundamentals.
* Handle errors and edge cases gracefully — e.g., missing files, invalid IDs, etc.
  ([roadmap.sh][1])

---

## Roadmap & Feedback

Follow these steps to build your project effectively:

1. **Choose your stack** — for example, Python or JavaScript.
2. Build core features one by one:

   * Add → List → Update → Delete → Status changes
3. **Test thoroughly** at each stage, verifying JSON contents.
4. **Polish your code**, add comments, and improve user feedback.
5. **Write this README** and share your implementation for community feedback.
   ([roadmap.sh][1])

---

## License

*(Add your chosen license here — e.g., MIT, Apache 2.0, etc.)*

---

## Original Project Reference

This project is inspired by the **Task Tracker CLI** from [roadmap.sh/projects/task-tracker](https://roadmap.sh/projects/task-tracker) — built to help you practice core programming concepts through a practical CLI tool.
([roadmap.sh][1])

---

### How to Use This README
