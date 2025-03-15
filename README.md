**StudentSignIn - Final Year Project Documentation**

**Project Overview**

StudentSignIn is an attendance-taking application that uses QR codes and facial recognition to automate the student sign-in process for classes. The system allows students to log in, select their courses, scan a QR code provided by the lecturer, undergo facial recognition, and mark their attendance. Lecturers can view attendance statistics for their classes in real time. This system streamlines attendance management and improves the accuracy of tracking student presence.

**Technologies Used**

Android (using Kotlin)

Jetpack Compose for UI

Firebase for backend services

Google ML Kit for facial recognition

Zxing for QR Code generation

**Backend:**

Firebase Firestore for real-time database

Firebase Authentication for user management

**Development Tools:**

Android Studio

**Features**

Student Login: Students can sign in using their email and password, with access restricted to students and lecturers.

Course Selection: After logging in, students select their course (e.g., ISD) to view the corresponding timetable.

QR Code Scanning: Students scan a QR code provided by the lecturer for a specific class session. This validates the QR code’s authenticity and timing.

Facial Recognition: After scanning the QR code, students undergo facial recognition to confirm their identity.

Attendance Marking: Once a student's face is recognized, attendance is automatically marked for that class session.

Lecturer's Dashboard: Lecturers can view real-time attendance reports for their classes and generate statistics.

**App Flow**

Login Page: Students and lecturers log in using their credentials.

Hub Page: After login, students see their timetable based on their course.

QR Code Scanner: Students scan the QR code provided by the lecturer for that day's class.

Facial Recognition: The app captures the student's face for identity verification.

Attendance Confirmation: Upon successful facial recognition, the attendance is marked, and the student is allowed into the class.

**Contributors**

Jason Price - Project Developer
