<div align="center">

<h3 align="center">YouCode SAS Training Challenges</h3>

  <p align="center">
    A collection of C programming challenges completed during the YouCode SAS training.
    <br />
    <a href="https://github.com/issam-mhj/youcode-sas">https://github.com/issam-mhj/youcode-sas</a>
  </p>
</div>

## Table of Contents

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#key-features">Key Features</a></li>
      </ul>
    </li>
    <li><a href="#architecture">Architecture</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

This repository contains a series of C programming challenges completed as part of the YouCode Simplon Access School (SAS) training program. The challenges are organized by day and cover a range of fundamental programming concepts, including:

- Basic input/output operations
- Data types and variables
- Conditional statements (if/else, switch)
- Loops (for, while)
- Arrays
- Functions
- Structures

### Key Features

- **Daily Challenges:** The challenges are structured into daily folders (Day1, Day2, etc.), allowing for a progressive learning experience.
- **Variety of Topics:** The challenges cover a wide range of C programming concepts, from basic syntax to more complex problem-solving.
- **Mini-Project:** Day 3 includes a mini-project, providing an opportunity to apply learned concepts to a larger task.
- **Code Examples:** Each challenge includes a C source code file with a solution or attempt at a solution.

## Architecture

The repository is organized into a simple directory structure:

```
youcode-sas/
├── README.md          # This file
├── Day1/              # Challenges for Day 1
│   ├── challenge_1.c
│   ├── ...
├── Day2/              # Challenges for Day 2
│   ├── challenge_1.c
│   ├── ...
├── Day3/              # Challenges for Day 3, including Loops challenges and a mini-project
│   ├── mini_project.c
│   └── Loops/
│       ├── challenge_1.c
│       ├── ...
├── Day4/              # Challenges for Day 4, including boucles challenges
│   ├── challenge_1.c
│   ├── ...
│   └── boucles/
│       ├── challenge_1.c
│       ├── ...
├── Day5/              # Challenges for Day 5
│   ├── challenge_1.c
│   ├── ...
└── Day6/              # Challenges for Day 6
    ├── challenge_1.c
    ├── ...
```

The code is written in C and can be compiled using a C compiler such as GCC.

## Getting Started

To explore the challenges in this repository, you will need a C compiler and a text editor or IDE.

### Prerequisites

- **C Compiler (GCC):**  You'll need a C compiler to compile and run the code.  GCC is a popular choice.

  ```sh
  # Example installation on Ubuntu/Debian
  sudo apt update
  sudo apt install gcc
  ```

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/issam-mhj/youcode-sas.git
   cd youcode-sas
   ```

2. **Navigate to a specific day's challenges:**

   ```sh
   cd Day1
   ```

3. **Compile a challenge (e.g., challenge_1.c):**

   ```sh
   gcc challenge_1.c -o challenge_1
   ```

4. **Run the compiled program:**

   ```sh
   ./challenge_1
   ```
