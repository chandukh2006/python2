# Robo Speaker

## Project Overview

The **Robo Speaker** is a simple Python application that converts text input into speech. This project demonstrates basic usage of system commands to produce voice output using the `espeak` (or `spd-say`) tool in a Linux environment.

## Features

- Continuous input prompt: The program continuously asks for text input from the user.
- Text-to-Speech conversion: Converts the user's text input into speech.
- Exit functionality: The user can exit the program by typing 'q', at which point the program says "bye bye friend" and terminates.

## Technology Stack

- **Programming Language**: Python 3.x
- **Speech Synthesis Tool**: `espeak` (or `spd-say`)
- **Operating System**: Linux

## Project Setup

### Prerequisites

- **Python**: Ensure Python 3.x is installed on your system.
- **Speech Tools**: Install `espeak` or `spd-say` for the speech synthesis functionality.

### Installing Dependencies

To install `espeak` on Linux, run:
```bash
sudo apt-get install espeak

