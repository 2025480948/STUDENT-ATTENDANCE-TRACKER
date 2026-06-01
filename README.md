Student Attendance Tracker
Prepared by: MUHAMAD FARIS AIMAN BIN MOHAMAD ROSLI (2025480948)
Prepared for: TS. DR. MOHAMAD RAHIMI BIN MOHAMAD ROSMAN 
Semester: MAC 2026 – AUGUST 2026
Faculty of Information Science, UiTM Machang, Kelantan
Project Description
This project is a functional web application interface developed for the IMS566 - Advanced Web Design Development & Content Management course at UiTM Machang. It serves as a comprehensive Student Attendance Management System, allowing administrators to track, manage, and visualize student attendance data efficiently. The application features a modern, dark-themed UI with a seamless user experience, fully simulated on the front-end without the need for a backend database.

Features Included
1.	Authentication System
•	Admin Login: Secure simulated login with hardcoded credentials and error feedback via toast notifications.
•	Student Registration: A multi-step sign-up form (Student Info → Account Setup → Review & Confirm) with live validation, password strength indicator, and input formatting.
2.	Responsive Navigation Menu
•	Consistent sidebar navigation across all pages.
•	Fully responsive design: collapses into a hamburger menu overlay on mobile devices.
3.	Interactive Dashboard
•	Summary statistics cards (Total Students, Present, Absent, Attendance Rate).
•	Line Chart: Monthly attendance vs. absence percentage trend.
•	Doughnut Chart: Today's attendance status breakdown.
•	Activity feed and low-attendance alerts.
4.	Data View Pages
•	Attendance Records: Data table to mark daily attendance (Hadir, Tidak Hadir, Lewat) with remarks and a "Mark All Present" feature.
•	Student List: Data table displaying enrolled students with search/filter functionality, attendance percentages, and action buttons (Edit, Delete).
5.	Data Visualization
•	Interactive charts powered by Chart.js.
•	Visual progress bars for individual student attendance rates.
6.	CRUD Operations
•	Add, edit, and delete students via modal dialogs.
•	Dynamic data binding that instantly updates tables and dashboard statistics.
7.	UI/UX Enhancements
•	Toast notifications for action feedback (success, error, info).
•	Custom form validation with real-time error messages.
•	Password visibility toggle.
•	Smooth page transitions and hover effects.
8.	Content Management & Structure
•	Proper metadata implementation for SEO awareness.
•	Structured footer containing project information, developer details, quick links, and lecturer info.

 
Instructions to Test Login
To access the main application, you can use the hardcoded Admin credentials or register a new student account.
Option 1: Admin Login (Recommended)
1.	Launch the application in your web browser.
2.	On the login screen, enter the following credentials:
•	Username: admin
•	Password: admin123
3.	Click the "Sign In" button.
4.	You will be redirected to the Dashboard.
Option 2: Student Registration & Login
1.	On the login screen, click the "Register Account" link.
2.	Complete the 3-step registration form (Name, Student ID starting with 2025, Email, Password).
3.	Agree to the terms and click "Register".
4.	You will be redirected back to Login. Enter your newly created Student ID as the username and your chosen password.
5.	Click "Sign In" to access the system.

Frameworks & Libraries Used
•	Tailwind CSS (v3.x): Utility-first CSS framework used for rapid, responsive UI styling and layout design.
•	Chart.js: JavaScript library used for rendering interactive data visualizations (Line and Doughnut charts) on the Dashboard.
•	Font Awesome (v6.5.0): Icon library used for UI elements, navigation items, and action buttons.
•	Google Fonts:
o	Space Grotesk: Used for display headings and titles.
o	DM Sans: Used for body text and interface elements.

