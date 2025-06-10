Student Course Manager
This is a Java Swing GUI application that allows users to manage student records. It supports adding, deleting, sorting, saving, and loading students. The project demonstrates object-oriented programming principles and uses useful data structures like ArrayList and HashMap. It also creates a file with all the data.

 How to Run
1. Compile and run the `Main.java` file.
2. A GUI window will appear to interact with the application.
3. Open your created file and keep track of your data

Features
Add new students (with ID, Name, and GPA)
Prevent duplicate IDs using a HashMap
Delete selected students
Sort students by GPA (highest to lowest)
Save students to a text file (`studentsq.txt`)
Load students from the file
Search students by ID instantly
GUI animation on add button (flashes green)

 File Handling
• Data is saved to and loaded from a file named `studentsq.txt`
• File format: Each student is stored on a separate line as: ID, Name, GPA

Data Structures Used
• ArrayList<Student> — to store the list of students and display them in the table
• HashMap<String, Student> — for quick ID-based lookups and duplicate checking

Object-Oriented Programming Principles
Encapsulation — Fields are private with getters/setters
Inheritance — `Student` inherits from `Person`

Project Files
• Main.java — Main GUI and program logic
• studentsq.txt — File for saving/loading student data
• README.txt — This file

