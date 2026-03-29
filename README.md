# Student_Study_Tracker
## Overview  
A simple command-line Python application built using object-oriented programming. It lets users register, login, add study sessions, and view reports summarizing their habit and study times by subject.

## Features  
- User registration and login  
- Add study sessions with subject, date, duration, and breaks  
- View total study time and breakdown per subject  
- Easy-to-use command-line interface  
- Modular design with separate classes and files  

## Technologies Used  
- Python 3  
- Basic OOP concepts (Classes for User, StudySession, Tracker)  
- No external libraries  

## How to Use  
1. Clone or download the repository.  
2. Run main.py (e.g., python main.py) to start the program.  
3. At the start menu, choose to Register, Login, or Exit.  
4. After login, add sessions or view your study report.  
5. Logout to switch users or exit the program.

## Project Structure  
- main.py — program entry point and user interface menus  
- user.py — defines User class handling user data and sessions  
- session.py — defines StudySession class  
- tracker.py — defines Tracker class managing users and workflow  

## Testing Instructions

### Manual Testing  
- *Register User:* Try registering multiple users. Test for duplicate usernames.  
- *Login:* Test login with correct and incorrect credentials.  
- *Add Study Sessions:* Add sessions with valid and invalid inputs (e.g., non-numeric durations).  
- *View Reports:* After adding study sessions, check if total and subject-wise times are correct.  
- *Logout:* Check logout functionality returns to main menu correctly.  
- *Exit Program:* Ensure the program exits cleanly at any point when chosen.

### Suggested Test Cases  
- Register user “Alice”, add 2 sessions in Math and English, verify report.  
- Try to register “Alice” again (should fail).  
- Login with wrong password (should fail) and correct password (should pass).  
- Add sessions with zero break time and non-zero break time, verify effective time calculation.  
- Logout and login as another user, verify separation of data.

### Tips  
- Run program multiple times to simulate user experience.  
- Carefully input invalid data deliberately to test error handling robustness.
<img width="1919" height="1021" alt="Screenshot 2026-03-29 223757" src="https://github.com/user-attachments/assets/5c5a6e6d-5d57-4dcd-b6f2-03796cb27b4d" />
<img width="1919" height="1020" alt="Screenshot 2026-03-29 223925" src="https://github.com/user-attachments/assets/68f2e386-704b-4b26-b4ae-0fda051543fd" />
<img width="1919" height="1020" alt="Screenshot 2026-03-29 224115" src="https://github.com/user-attachments/assets/6ec23910-2f64-4d97-9063-09bb2d106f41" />
<img width="1919" height="1016" alt="Screenshot 2026-03-29 224329" src="https://github.com/user-attachments/assets/67b0a045-8533-4a21-a423-3c12ae9436c3" />
<img width="1919" height="1018" alt="Screenshot 2026-03-29 224356" src="https://github.com/user-attachments/assets/ddaf9931-7f0e-4a66-8d4f-f29547569fad" />
