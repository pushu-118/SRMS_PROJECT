Student Management System (C Program)

A simple and efficient Student Management System built using C.
It supports three user roles — Admin, Staff, and Guest — each having specific access permissions.
The program uses file handling to manage student records and login credentials.


Features

Login System
Reads user credentials (username, password, role) from credentials.txt.

User Roles & Permissions
Admin  - Add, Display, Search, Update, Delete Students
Staff  - Add, Display, Search, Update Students
Guest  - Display, Search Students


File Structure

project-folder/
    student_app.c        (Main C program)
    students.txt         (Student records storage)
    credentials.txt      (User login credentials)


Student File Format (students.txt)

roll name marks

Example:
101 Rahul 89.50
102 Priya 76.25


Credentials File Format (credentials.txt)

username password role

Example:
admin admin123 admin
teacher tpass staff
viewer view123 guest


How to Compile and Run

Compile:
gcc student_app.c -o student_app

Run:
./student_app


Program Functionalities

Admin Menu:
1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Delete Student
6. Logout

Staff Menu:
1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Logout

Guest Menu:
1. Display Students
2. Search Student
3. Logout


Advantages

- Simple and user-friendly
- Persistent data storage
- Role-based access control
- Easy to modify and upgrade


Future Enhancements

- Password masking
- Better name handling (full name support)
- Duplicate roll number check
- Export student data to CSV
- Binary file storage
