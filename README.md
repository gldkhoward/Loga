# Loga

## Overview
Loga is a lightweight, versatile logging library for C++ applications. Designed with simplicity and performance in mind, it provides a seamless experience for developers needing precise and configurable logging. From debugging to critical error reporting, Loga offers a comprehensive solution.

## Features
- **Multiple Log Levels**: DEBUG, INFO, WARN, ERROR, FATAL to suit all your logging needs.
- **Flexible Output**: Supports console and file outputs, with options for customizing log formats.
- **Easy Integration**: Simple setup process and easy to integrate with existing C++ projects.
- **Thread-Safe**: Ensures logging is safe across multiple threads in concurrent applications.
- **Configurable**: Allows dynamic log level changes and supports configuration through external files.

## Getting Started
### Prerequisites
- CMake 3.10 or higher
- A C++17 compliant compiler

### Building from Source
Clone the repository and build the project using CMake:

```bash
git clone https://github.com/yourusername/Loga.git
cd Loga
mkdir build && cd build
cmake ..
make
