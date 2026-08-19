College Database Demo – Project Explanation
📌 Introduction
The College Database Demo is a MySQL-based database project designed to manage basic information about a college.
The project organizes college information into five main categories:
- Departments
- Students
- Courses
- Enrollment
- Faculty
The main purpose of the project is to demonstrate how a relational database can store information in separate tables and connect those tables using relationships.
🏫 Department
The Department table stores information about the different departments available in the college.
In this project, there are three departments:
- Computer Science
- Mechanical
- Electronics
Each department has a unique department ID. This ID is used by other tables to identify which department a student, course, or faculty member belongs to.
👨‍🎓 Student
The Student table stores details about students.
Each student has:
- A unique roll number
- Name
- Email
- Aadhaar number
- Department
The department ID connects a student with their department.
For example, Chaitanya Deo belongs to Computer Science, while Varun Gharote belongs to Mechanical.
The database also prevents duplicate email addresses and Aadhaar numbers.
📚 Course
The Course table stores information about courses offered by the college.
Each course has:
- A unique course ID
- Course name
- Department
The department information allows us to identify which department offers a particular course.
For example, Database Systems is associated with Computer Science, while Thermodynamics is associated with Mechanical.
📝 Enrollment
The Enrollment table connects students and courses.
It records:
- Which student took a course
- Which course the student took
- The semester in which the course was taken
- The grade received
