Typing Practice Application - README
https://fondo.png

Overview
Improve your typing skills with this Java-based typing practice application! This project offers two difficulty levels, real-time performance tracking, and a beautiful futuristic UI. Perfect for beginners and advanced typists alike.

Key Features
🎯 Two difficulty levels with custom texts

📊 Real-time statistics (PPM, errors, points)

👤 User profiles with saved statistics

👨‍💻 Admin panel for content management

⌨️ On-screen keyboard with visual feedback

⏱️ Timed typing challenges

How to Run the Application
Prerequisites
Java JDK 22 (or compatible version)

Git (optional)

Installation Steps
Download the project:

bash
git clone https://github.com/yourusername/typing-practice-app.git
or download the ZIP file and extract it

Navigate to project directory:

bash
cd typing-practice-app
Compile and run:

bash
javac -d bin src/*.java
java -cp bin PantallaCarga
Application Screens Explained
1. Loading Screen (PantallaCarga)
Validates all required files and configurations

Shows progress bar while initializing

Ensures system meets requirements before starting

2. Welcome Screen (PanelBienvenida)
Beautiful futuristic design with animated elements

Options to start playing or exit

Clean, intuitive interface

3. Login Screen (PanelLogin)
Secure authentication system

Separate access for users and admins

Visual feedback for incorrect credentials

4. User Panel (PanelUsuario)
Choose between practice levels

View your typing statistics

Access typing tutorial

Logout functionality

5. Admin Panel (PanelAdministrador)
Manage users (add/remove)

Edit practice texts for both levels

View all registered users

Special privileges for content management

6. Typing Practice (PanelNivelFacil/PanelNivelDificil)
Easy Level:

200-character texts

4-minute time limit

5 error allowance

Perfect for beginners

Hard Level:

1000-character texts

3-minute time limit

3 error allowance

Challenging for advanced users

7. Statistics Tracking
Points system (gain points for correct characters, lose for errors)

Errors counter with limit

Pulses Per Minute (PPM) calculation

Time tracking

Session saving capability

Tutorial
Access the typing tutorial from the user panel to see proper finger placement and typing techniques:

https://tutorial.png

Technical Details
Built with Java Swing for the GUI

File-based storage (no database required)

Uses Java 22 features

Futuristic UI with custom graphics

Input validation at multiple levels

Contribution
Feel free to contribute to this project! Open issues or submit pull requests for:

UI improvements

Additional features

Bug fixes

Translation support
