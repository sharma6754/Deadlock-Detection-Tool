﻿# Deadlock Detection & Recovery – Visualization Tool

This is a Python GUI application that simulates the **Banker’s Algorithm** for deadlock detection and recovery. It provides an interactive interface to input matrices, check for safe states, visualize the **Resource Allocation Graph (RAG)** with arrows, node shapes, and highlight potential deadlocks. It also includes a **deadlock recovery mechanism** that preempts processes to restore system safety.

## Features

- **Autofilled Input Matrices** (Allocation, Max, Available)
- **Safe State Detection** using Banker's Algorithm
- **Resource Allocation Graph (RAG) Visualization**
  - Processes shown as **blue circles**
  - Resources shown as **light green rectangles**
  - **Directed arrows** for request and assignment edges
  - **Deadlock cycles** highlighted in red
- **Deadlock Recovery** via process preemption with safe sequence output
- **Scrollable GUI** for better usability

## How to Run

### 1. Clone the Repository

bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

### 2. Install Requirements
pip install matplotlib networkx numpy

### 3. Run the application
python your_script_name.py


## How it Works?
* Safe State Check: Uses the Banker's algorithm to determine if the system is in a safe state.

* RAG Visualization: Constructs a directed graph using networkx and matplotlib, showing request and assignment relationships   between processes and resources.

* Deadlock Recovery: Identifies deadlocks and preempts selected processes to release resources and restore a safe state.

## Project Structure
│
├── DDT.ipynb                  # Main Python GUI script
├── README.md                  # This file
└── requirements.txt           # Python dependencies


## Author
Name: Raunit Sharma, R. Shakruthi, S. Mamatha, S. Samhita, S. Sandeep
Institute: VNR VJIET, Bachupally
Purpose: Academic Project

## Licence
This project is open source and available under the MIT License.
