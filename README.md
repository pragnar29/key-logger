# Keyboard Event Logger

## Project Overview
The Keyboard Event Logger is a simple Java application that demonstrates keyboard event handling using Java Swing. The program captures key presses made within its application window and stores them in a text file.

## Features
- Captures keyboard input using KeyListener.
- Displays pressed keys in the console.
- Saves key names to a text file.
- Uses Java Swing for the graphical user interface.
- Demonstrates event-driven programming.

## Technologies Used
- Java
- Java Swing
- File Handling (FileWriter)
- Event Handling (KeyListener)

## How It Works
1. The application opens a GUI window.
2. When a key is pressed within the window, the event is detected.
3. The key name is displayed in the console.
4. The key name is stored in a text file named `keys.txt`.

## Installation and Execution

### Prerequisites
- Java Development Kit (JDK 8 or higher)

### Compile the Program

```bash
javac KeyEventLogger.java
