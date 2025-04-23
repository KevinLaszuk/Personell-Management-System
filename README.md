# Personel-Management-System

- A console-based Java application designed to manage university personnel, including students, faculty, and staff. It demonstrates object-oriented programming principles such as inheritance, abstraction, method overriding, and encapsulation.

# 📚 Project Overview
- This application allows users to add, manage, and view details about students, faculty, and staff. It supports tuition invoice generation, input validation, data reporting, and sorting functionalities—all via a simple command-line interface.

# 👨‍🏫 Key Features
- Add and manage Students, Faculty, and Staff

- Automatically generate tuition invoices for students

- Validate inputs like ID formats, department names, and faculty ranks

- Prevent duplicate entries using unique ID enforcement

- Generate and save a report file (report.txt) upon exit

- Sort student data by descending GPA or alphabetical name

# 🏗️ Class Structure
Abstract Classes
- Person – Base class for all people in the system. Declares the abstract method print().

- Employee – Extends Person; serves as the base class for Faculty and Staff.

Concrete Classes
- Student – Inherits from Person; includes GPA, credit hours, and tuition calculation.

- Faculty – Inherits from Employee; includes department and academic rank.

- Staff – Inherits from Employee; includes department and employment status.

