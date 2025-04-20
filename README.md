# 📚 Student Management System with Exception Handling  
-- Directly Committed from GIT BASH --

## 📖 Project Description  
This Java project is designed to manage student records and demonstrates effective use of **custom exception handling**. It supports operations such as adding, searching, and validating student data, while ensuring smooth execution using user-defined exceptions.

The project follows modular design principles — each class and functionality is implemented in separate files with clear responsibilities and documentation.

---

## 📂 Project Structure  

```
Assig8/
│── Main.java                        # Entry point of the program  
│── Operations.java                  # Contains all student-related operations  
│── Student.java                     # Represents the Student data model  
│── CustomException.java             # Base class for custom exceptions  
│── DuplicateStudentException.java   # Thrown when a student with same ID already exists  
│── InvalidChoiceException.java      # Thrown when an invalid menu option is selected  
│── InvalidInputException.java       # Thrown when user inputs invalid data  
│── StudentNotFoundException.java    # Thrown when student is not found in search  
│── (All corresponding .class files) # Compiled bytecode files for each source file  
```

---

## ⚡ Functions & Features

| File                        | Method / Class                      | Description |
|-----------------------------|--------------------------------------|-------------|
| `Main.java`                 | `main(String[] args)`               | Starts the program and handles user menu |
| `Operations.java`           | `addStudent()`                      | Adds a new student to the record |
|                             | `searchStudent()`                   | Searches for a student by ID |
|                             | `displayAllStudents()`              | Displays the list of all students |
|                             | `deleteStudent()`                   | Deletes a student from the list |
| `Student.java`              | `Student` class                     | Contains student attributes and methods |
| `DuplicateStudentException` | Custom Exception                    | Triggered when adding a student that already exists |
| `StudentNotFoundException`  | Custom Exception                    | Triggered when searching/deleting a non-existent student |
| `InvalidInputException`     | Custom Exception                    | Triggered for invalid data types or inputs |
| `InvalidChoiceException`    | Custom Exception                    | Triggered for menu options that don't exist |

---

## 🧠 Exception Handling  
This project utilizes **inbuilt and custom exceptions** to improve performance and enhance user experience. The following are the main exceptions handled:

- ✅ `DuplicateStudentException`  
- ❌ `InvalidInputException`  
- 🔍 `StudentNotFoundException`  
- 📋 `InvalidChoiceException`

Each exception has been declared in its own file to maintain a clean and scalable architecture.

---

## 🛠️ How to Run

1. Open Git Bash or any terminal.
2. Navigate to the project folder:
   ```bash
   cd "path_to_Assig8_folder"
   ```
3. Compile the main file:
   ```bash
   javac Main.java
   ```
4. Run the program:
   ```bash
   java Main
   ```

---

## 📌 Coding Guidelines Followed:
- Every class is modular and documented.
- Code is written using proper indentation and naming conventions.
- Comments are added for clarity in logic blocks.
- Exception messages guide the user for corrective actions.

---


---

🎓 **Built using Java | SEM 4 Project**  
✍️ **Author:** Arjun  
🧾 **PRN:** [23070126026]  

