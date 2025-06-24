Typing Practice Application - README
Overview 💻
Improve your typing skills with this Java-based application featuring a futuristic UI, two difficulty levels, and real-time performance tracking. Perfect for beginners and advanced typists!

Key Features ✨
🎯 Two difficulty levels with custom texts

📊 Real-time statistics (PPM, errors, points)

👤 User profiles with saved statistics

👨‍💻 Admin panel for content management

⌨️ On-screen keyboard with visual feedback

⏱️ Timed typing challenges with error limits

🖥️ Futuristic UI design with animated elements

📁 File-based storage (no database required)

🔒 Secure authentication system

📈 Performance tracking with session saving

Installation 🛠️
Download the project ZIP file

Extract contents to your preferred directory

Import into Eclipse:

Open Eclipse IDE

Go to File > Import > General > Existing Projects into Workspace

Select the extracted folder

Click Finish

Running the Application ▶️
Locate the PantallaCarga.java file

Right-click and select Run As > Java Application

Application Structure 🖥️
Loading Screen
Validates essential files and configurations

Checks system requirements

Shows progress bar during initialization

Welcome Screen
Futuristic design with animated visual effects

Clean interface with "Play" and "Exit" options

Login Screen
Secure authentication for users and admins

Input validation with visual feedback

User Panel
Choose difficulty level (Easy/Hard)

View personal statistics

Access typing tutorial

Logout functionality

Admin Panel
User management (add/remove users)

Edit practice texts for both levels

View all registered users

Typing Practice
Easy Level:
200-character texts

4-minute time limit

Max 5 errors allowed

Hard Level:
1000-character texts

3-minute time limit

Max 3 errors allowed

File Structure 📁
text
src/
├── PantallaCarga.java       # Main entry point
├── PanelBienvenida.java     # Welcome screen
├── PanelLogin.java          # Login screen
├── PanelUsuario.java        # User dashboard
├── PanelAdministrador.java  # Admin controls
├── PanelNivelFacil.java     # Easy typing level
├── PanelNivelDificil.java   # Hard typing level
├── Lecciones.java           # Text editing
├── usuarios.txt             # User credentials
├── textos.txt               # Practice content
└── estadisticas.txt         # Performance data
