# Java Swing Learning Management System (LMS)

![LMS Dashboard Preview](resources/images/dashboard-preview.png) <!-- Add actual screenshot if available -->

A Java Swing-based Learning Management System designed for student and administrator academic management, built with Maven and modern UI principles.

## 📋 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [OOP Concepts](#-object-oriented-programming-concepts-used)
- [Events & Listeners](#-events--listeners)
- [Libraries](#-libraries-used)

## 🌟 Features
- 🎨 **Modern UI** with consistent styling via `UIConstants` and `UIHelper`
- 👤 **Student Profile** with dynamic avatar and academic details
- 📊 **Dashboard** with navigation panel and content sections
- 🔐 **Secure Login** with password field validation
- 🖼️ **Image Fallback System** displays initials when images are missing
- 📦 **Maven Build** for dependency management

## 🗂 Project Structure
- src/
- ├── main/
- │ ├── java/
- │ │ ├── com/lms/
- │ │ │ ├── main/ # Application entry point
- │ │ │ ├── views/ # GUI components (Dashboard, LoginPage)
- │ │ │ ├── components/ # Custom UI elements
- │ │ │ ├── utils/ # Helper classes (UIHelper, ImageLoader)
- │ │ │ └── models/ # Data models
- │ │ └── resources/
- │ │ └── images/ # UI icons and avatars
- ├── test/ # Unit tests (if added later)

## 🧩 Object-Oriented Programming Concepts Used
**Encapsulation**
- UI logic contained within components (LoginPage, DashboardPanel)

**Abstraction**
- UIHelper class handles repetitive styling tasks
**Inheritance**
- Custom components extend Swing classes (JPanel, JButton)
**Modularity**
- Independent screens/components for easy maintenance

##⚡Events & Listeners
- **MouseListener for button hover effects**

**ActionListener for:**
- Login validation
- Navigation between panels
- File uploads/downloads
- MouseAdapter in UIHelper for interactive elements

##📚 Libraries Used

- **javax.swing.*** - Core GUI components
- **java.awt.*** - Layout management and rendering
- **javax.swing.border.*** - Custom border designs
- **java.net.URL** - Resource loading
- **java.awt.image.BufferedImage** - Dynamic image generation
