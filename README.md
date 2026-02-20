# Inheritance Template

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A Java starter template for learning object-oriented inheritance concepts, featuring animal and 2D shape class hierarchies with guided exercises.

## Overview

This project provides a hands-on exercise template designed to teach Java inheritance. Students work through a series of steps to build out class hierarchies for **Animals** (with `Cat` and `Dog` subclasses) and **2D Shapes** (with `Circle`, `Triangle`, and `ColouredTriangle` subclasses). The template includes skeleton classes with guided instructions to implement instance variables, getters/setters, constructors, and a main driver class.

## Features

- Pre-structured package hierarchy (`ie.gmit.animal`, `ie.gmit.twodshapes`)
- Animal inheritance chain: `Animal` -> `Cat`, `Dog`
- 2D Shape inheritance chain: `TwoDShape` -> `Circle`, `Triangle` -> `ColouredTriangle`
- Step-by-step guided exercises for building out each class
- Gitpod-ready configuration for browser-based development

## Prerequisites

- **Java JDK** 8 or higher
- A Java IDE or text editor (e.g., IntelliJ IDEA, VS Code with Java extensions, or Gitpod)

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/danielcregg/inheritance-template.git
   cd inheritance-template
   ```

2. Alternatively, open directly in Gitpod:
   ```
   https://gitpod.io/#https://github.com/danielcregg/inheritance-template
   ```

### Usage

1. Follow the step-by-step instructions to complete each class:
   - **Step 1:** Add two instance variables with getters and setters to the `Animal` class
   - **Step 2:** Add one instance variable with getter and setter to `Cat` and `Dog`
   - **Step 3:** Add the `main` method inside the `Main` class
   - **Step 4:** Create `Cat` and `Dog` objects, set their variables, and print values
   - **Step 5:** Add constructors to `Animal`, `Cat`, and `Dog`
   - **Step 6:** Add, commit, and push your code

2. Compile and run:
   ```bash
   javac -d . Main.java ie/gmit/animal/*.java ie/gmit/twodshapes/*.java
   java Main
   ```

## Tech Stack

- **Language:** Java
- **Environment:** Gitpod (optional)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
