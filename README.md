# ✨ Typing Practice Application

Welcome to the Typing Practice App! Improve your typing speed, accuracy, and finger placement with this futuristic, educational Java application.

---

## 💻 Overview

This application helps users develop strong typing skills through:

- Real-time interactive feedback
- Detailed performance analytics
- Visual keyboard interface
- Error-limited, time-bound challenges
- User and admin roles with saved progress

> Perfect for beginners learning touch typing and advanced typists aiming to break speed records.

---

## 🚀 Key Features

### 🎯 Core Functionality

- ✅ Dual difficulty levels: Easy and Hard
- ✅ Real-time statistics: Keystrokes per minute (PPM), error count, and points
- ✅ User profiles with saved performance data
- ✅ Admin panel to manage users and edit practice content

### ✨ User Experience

- 🎹 Virtual keyboard with real-time visual feedback
- ⏱️ Timed challenges with error limits
- 💡 Futuristic user interface with animated elements
- 📈 Performance tracking and session saving

### ⚙️ Technical Capabilities

- 🧾 File-based storage (no database needed)
- 🔐 Secure login and authentication system
- 🧼 Input validation at multiple levels
- 💻 Cross-platform support (Windows, macOS, Linux)

---

## 📋 Application Structure

| Screen              | Description                                  |
|---------------------|----------------------------------------------|
| **Loading Screen**  | Validates required files and configuration   |
| **Welcome Screen**  | Entry point with "Play" and "Exit" options   |
| **Login Screen**    | Secure login for Users and Admins            |
| **User Panel**      | Access to levels, stats, and tutorials       |
| **Admin Panel**     | User management and text editing             |
| **Typing Practice** | Typing interface with real-time stats        |

---

## 🎮 Difficulty Levels

| Feature         | 🅰️ Easy Mode           | 🅱️ Hard Mode            |
|-----------------|------------------------|--------------------------|
| Text Length     | 200 characters         | 1000 characters          |
| Time Limit      | 4 minutes              | 3 minutes                |
| Max Errors      | 5                      | 3                        |
| Target Audience | Beginners              | Advanced typists         |

---

## 🛠️ Installation & Usage

Open Eclipse, then go to:
File > Import > General > Existing Projects into Workspace
Select the extracted project folder and click **Finish**.

Run the app from `PantallaCarga.java` as a **Java Application**.

> ⚠️ **Important**: Do **not** modify the `.java` files unless you're editing functionality.  
> You can safely edit the `.txt` files to update users or texts.

---

## 📁 Project File Structure
src/
-├── 🚀 PantallaCarga.java # Main entry point
-├── 🏠 PanelBienvenida.java # Welcome screen
-├── 🔐 PanelLogin.java # User/Admin login
-├── 👤 PanelUsuario.java # User dashboard
-├── 👑 PanelAdministrador.java # Admin panel
-├── 🅰️ PanelNivelFacil.java # Easy typing level
-├── 🅱️ PanelNivelDificil.java # Hard typing level
-├── ✏️ Lecciones.java # Content editor for admin
-├── 👥 usuarios.txt # User credentials
-├── 📝 textos.txt # Practice texts
-└── 📊 estadisticas.txt # Typing session statistics
---

## 💻 Technology Stack

| Category         | Details                             |
|------------------|-------------------------------------|
| **Language**     | Java 22                             |
| **UI Library**   | Java Swing                          |
| **Storage**      | Plain text files (`.txt`)           |
| **Design**       | Futuristic aesthetic with animation |
| **Compatibility**| Windows, macOS, Linux               |

---

## ⭐ Support & Contribute

If you find this project helpful:

- 🌟 Star this repository on GitHub  
- 🛠️ Fork it and create your own version  
- 🐛 Open an issue if you find bugs or want to suggest features

---

## 👨‍💻 Author

Developed by **David Cereceda**  
🎓 Computer Science Student | Passionate about Java, C#, AI, and Educational Software
