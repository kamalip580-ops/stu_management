# stu_management
# Student Management System

A beginner-friendly Python project that manages student records using object-oriented programming and JSON file storage.

## Project Description

This project demonstrates how to build a complete console-based Student Management System using Python. It includes features such as adding, viewing, searching, updating, deleting, counting, and sorting students. The data is stored in a JSON file so the records persist between runs.

## Features

- Add a new student
- Display all students in a formatted table
- Search a student by Student ID
- Update student details
- Delete a student with confirmation
- Count the total number of students
- Sort students by name or Student ID
- Validate input and prevent duplicate Student IDs
- Automatically save data to a JSON file
- Display the current date and time on startup
- Show a welcome banner and colored terminal output

## Technologies Used

- Python 3
- JSON for data storage
- Colorama for colored terminal output

## Folder Structure

```text
student-management-system/
│
├── main.py
├── student.py
├── student_manager.py
├── utils.py
├── data/
│   └── students.json
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation

1. Clone the repository:
   ```bash
   git clone <your-repository-url>
   ```
2. Navigate to the project folder:
   ```bash
   cd student-management-system
   ```
3. Install the required package:
   ```bash
   pip install -r requirements.txt
   ```

## How to Run

Run the program with:

```bash
python main.py
```

## Sample Output

```text
============================================
   Student Management System
============================================
Current date and time: 2026-07-06 14:30:00

=== Student Management System Menu ===
1. Add a new student
2. Display all students
3. Search for a student
4. Update a student
5. Delete a student
6. Count total students
7. Sort students
8. Exit
```

## 📸 Screenshot

![Student Management System](images/student-management-system.png)


## Future Improvements

- Add a graphical user interface (GUI)
- Add database support (SQLite)
- Add search by name or course
- Add export to CSV
- Add authentication for admin users

## Author

Your Name

## License

This project is licensed under the MIT License.
