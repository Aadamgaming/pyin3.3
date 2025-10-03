# Pyin3.3 - Python OS with Nemo Package Manager

A lightweight, cross-platform Python operating system simulator with built-in package management. Runs on both Desktop Python and MicroPython devices.

![Pyin3.3 Demo](https://img.shields.io/badge/Python-3.3%2B-blue) ![MicroPython](https://img.shields.io/badge/MicroPython-ESP32-green) ![Platform](https://img.shields.io/badge/Platform-Cross--platform-orange)

## 🚀 Features

### Core System
- **Virtual Filesystem** - Complete file/directory management
- **Cross-Platform** - Runs on Desktop Python and MicroPython ESP32
- **Persistent State** - Saves your files and configuration between sessions
- **Command Line Interface** - Familiar Unix-like commands

### Basic Commands
- `ls` - List directory contents
- `cd` - Change directory
- `pwd` - Print working directory
- `cat` - Display file contents
- `edit` - Simple text editor
- `mkdir` - Create directories
- `calc` - Basic calculator
- `clear` - Clear screen
- `help` - Show available commands

### Package Management with Nemo
- `nemo install <package>` - Install packages from remote repositories
- `nemo search <package>` - Search for available packages
- `nemo config [url]` - Configure package sources

### MicroPython ESP32 Features
- `wifi search` - Scan for available WiFi networks
- `wifi connect <ssid> <password>` - Connect to WiFi
- Resource-optimized for limited hardware

### System Information
- `neofetch` - Display system info with ASCII art

