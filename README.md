# Student-Management-System-PHP-PDO-MySQL-
This project is a simple Student Management Web Application built with PHP, PDO, MySQL, HTML/CSS, and sessions.
It allows an admin to log in, add students, view all students, and filter them by admission status based on their calculated average.
**Authentication**
Admin login system using PHP sessions.
Error handling for invalid credentials.
**Student Management**
Add new students with:
Nom,Email,Contrôle,Projet,Examen
**Consultation / Search**
Display a table of all students.
Automatic calculation of the general average:
Moyenne = (25% * Contrôle) + (15% * Projet) + (60% * Examen).
**Filter results:**
All students
Admitted students
Failed students
**Admin Security**
Restricted access using session authentication.
Logout system with session destruction.
