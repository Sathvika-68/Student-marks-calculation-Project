🎯Student Marks Calculation using API


📘Project Content :

A web-based application that streamlines the process of entering, calculating, and displaying student academic performance. Faculty can log in to entry internal (3 mid exams) and external marks of the sudents , while students can access their calculated grades and final report card.It is built for use in schools, colleges, or universities that supports both faculty and student roles.


⚙️Project Code :

app.py : Main Backend Application
index.html: Home page with login/registration
student-dashboard.html: Student dashboard with options to view marks and report
faculty-dashboard.html: Faculty dashboard for entering marks
report-card.html: Displays final marks and grades
student_mark.sql: Handles database schema and queries


🛠️Key Technologies

Backend:Python Flask
Database:MySQL
API: RESTful API (JSON format)
Testing Tools: Postman / Swagger UI
Optional: JWT for authentication


📝Description

This System allows:
Faculty to log in and submit internal marks (Mid1, Mid2, Mid3) and external marks.
Internal marks are calculated by selecting the best 2 midterm scores and averaging them.(25 each)
Final marks are computed by summing internal average and external marks. (externals = 75 marks)
Grades are assigned based on final marks.
Students can log in to view:
Subject-wise breakdown of internal, external, and final marks
Assigned grade per subject
Overall total and average marks -Faculty can log in to view:
Insertion of internas and externals
View all student's externals
View all there students


✅OUTPUT 

Home Page :


![Screenshot 2025-05-26 210022](https://github.com/user-attachments/assets/504edb44-7d4f-4d91-95e3-5cfbfca569e4)


Faculty Dashboard:


![Screenshot 2025-05-26 210310](https://github.com/user-attachments/assets/1fb37817-a5c9-4a08-b001-ed35ee8b2e3d)


Student Dashboard :


![Screenshot 2025-05-26 210219](https://github.com/user-attachments/assets/3ece652b-5416-420d-b1d3-94ee3fafbb26)


💡Feature Research

Authentication for teachers using JWT

Frontend using React or HTML templates

Export student report cards as PDF

Bulk import via Excel/CSV
