# Student Database Management System

This is a simple Student Database Management System implemented in Java. It allows users to perform various operations such as adding students, viewing student details, searching for a student by roll number, calculating the average marks of all students, and exiting the program.

## Features

- **Add Student**: Users can add a new student by providing their name, roll number, age, and marks.
- **View Student**: Users can view the details of all students currently stored in the database.
- **Search Student**: Users can search for a specific student by entering their roll number.
- **Calculate Average Marks**: The system can calculate and display the average marks of all students.
- **Exit**: Users can choose to exit the program.

## How to Use

1. **Compile the Code**: Compile the Java file (`Database.java`) using a Java compiler.
   ```bash
   javac Database.java
   ```

2. **Run the Program**: Execute the compiled Java file.
   ```bash
   java Database
   ```

3. **Follow On-Screen Instructions**: Once the program is running, follow the on-screen menu to perform various operations.

## Usage Instructions

- When prompted, enter the corresponding number for the operation you want to perform.
- For adding a student, provide the required details such as name, roll number, age, and marks.
- To view all students, select the option to view students.
- To search for a specific student, enter their roll number.
- The option to calculate average marks will display the average marks of all students stored in the database.
- Choose the exit option to terminate the program.

## Note

- This program uses a `HashMap` to store student records. Roll numbers serve as the keys, and `Student` objects are stored as values.
- Input is read from the console using the `Scanner` class.
- Ensure valid input is provided to avoid unexpected behavior or errors.

## Example

'''

1. Add Student :
2. View Database :
3. Search Student (Input roll number) :
4. Calculate Average Marks :
5. Exit Loop

Enter your choice : 1
Enter student name : John Doe
Enter roll number : 101
Enter age : 20
Enter marks : 85.5
Student added successfully!

1. Add Student :
2. View Database :
3. Search Student (Input roll number) :
4. Calculate Average Marks :
5. Exit Loop

Enter your choice : 2

Student Details:
Name: John Doe
Roll Number: 101
Age: 20
Marks: 85.5

1. Add Student :
2. View Database :
3. Search Student (Input roll number) :
4. Calculate Average Marks :
5. Exit Loop

Enter your choice : 4
Average marks is 85.5

'''
