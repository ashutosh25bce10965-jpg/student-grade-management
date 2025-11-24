# **Student Grades Management System**

This is a simple Python-based console application that allows users to manage student grades.
It provides basic CRUD functionality—Add, Update, Delete, and View students along with their grades.

---

## **Features**

* **Add Student**
  Add a new student with a grade to the system.

* **Update Student**
  Update the grade of an existing student.

* **Delete Student**
  Remove a student from the system.

* **Display All Students**
  View all students and their corresponding grades.

* **Exit Program**
  Close the application gracefully.

---

## **How It Works**

The application uses a dictionary:

```python
student_grades = {}
```

Each student's name is stored as a **key**, and their grade is stored as a **value**.

---

## **Functions Overview**

### `add_student(name, grade)`

Adds a new student and displays a confirmation message.

### `update_student(name, grade)`

Updates the grade of an existing student.
If the student does not exist, an error message is shown.

### `delete_student(name)`

Deletes a student from the dictionary if they exist.

### `display_all_student()`

Prints all the students and their grades.
If no students are stored, a message is shown.

### `main()`

Runs an infinite loop displaying a menu, taking the user's choice, and calling the corresponding functions.

---

## **Usage**

1. Run the script:

   ```bash
   python your_script_name.py
   ```

2. Choose an option from the menu:

   ```
   Student Grades Management System
   1. Add student
   2. Update student
   3. Delete student
   4. View student
   5. Exit
   ```

3. Enter the required inputs (student name and grade) based on your selected action.

---

## **Example**

```
Student Grades Management System
1. Add student
2. Update student
3. Delete student
4. View student
5. Exit
enter your choice = 1
enter student name = John
enter student grade = 85
Added John with a 85
```

---

## **Notes**

* Input validation is minimal; ensure grade values are integers.
* Student names are case-sensitive (e.g., `"John"` and `"john"` are treated as different students).

---

## **Future Improvements (Optional)**

* Add data persistence (save to a file).
* Add input validation and error handling.
* Provide sorting options (by name or grade).
* Convert to a GUI or web application.

