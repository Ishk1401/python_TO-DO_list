# ✅ To-Do List App (CLI-Based)

A simple, persistent **command-line to-do list manager** written in Python.  
Manage your daily tasks directly from the terminal — no GUI, no distractions.

---

## 🚀 Features

- 📂 Loads tasks from a file when you start
- 🧾 View your current to-do list
- ➕ Add new tasks easily
- ❌ Remove tasks by their number
- 💾 Saves your list to `tasks.txt` automatically
- 🧠 Beginner-friendly and easy to modify

---

## 🛠️ How It Works

This app uses a **Python list** to store tasks in memory and a **text file (`tasks.txt`)** to save them between sessions.

### 📦 On startup:
- Loads tasks from `tasks.txt` (if it exists)

### 🧑‍💻 While running:
- Presents a simple menu with options to view, add, and remove tasks

### 💾 On exit:
- Saves your updated task list back to `tasks.txt`

---

## 💻 How to Run

1. Make sure you have **Python 3 installed**.
2. Clone or download this repository.
3. Open your terminal or command prompt.
4. Navigate to the folder where `todo.py` is located.
5. Run the program:

```bash
python todo.py
