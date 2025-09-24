Campus Course & Records Manager (CCRM)

The Campus Course & Records Manager (CCRM) is a Java console application that helps academic institutions manage their students, courses, enrollments, and grades.
This project demonstrates Object-Oriented Programming (OOP) concepts, design patterns, file operations, and exception handling in Java.

 Features
 Student Management

Add new students with ID, registration number, name, and email.

Track enrollment status (Active, Inactive, Deceased).

View list of all students.

 Course Management

Add new courses with course code, title, credits, semester, department.

Assign instructors to courses.

View list of all available courses.

 Enrollment & Grading

Enroll students in courses (with max credit validation per semester).

Prevent duplicate enrollments with custom exceptions.

Record marks for assessments (e.g., Midterm, Final).

Compute grades automatically (S, A, B, C, D, F) based on average marks.

Print student transcripts with course details and grades.

 File Operations

Export student and course data to CSV files.

Create timestamped backups of CSV files.

Calculate total size of backup directories using a recursive utility.

 Reports

List students by active status.

Search courses by instructor name.

Easily extendable to add more report types (e.g., GPA reports, course enrollments).

🛠️ Concepts Demonstrated

OOP Principles

Inheritance, Polymorphism, Abstraction, Encapsulation

Design Patterns

Singleton (AppConfig)

Builder (Student, Course)

Custom Exceptions

DuplicateEnrollmentException

MaxCreditLimitExceededException

Java Utilities

Streams & Lambdas

Predicates for filtering

Enhanced switch expressions

File I/O

Exporting data to CSV

Recursive directory size calculation

Timestamp-based backup creation
