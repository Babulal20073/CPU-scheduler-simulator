# CPU Scheduler Simulator
Website link- https://babulal20073.github.io/CPU-scheduler-simulator/

## Overview

The **CPU Scheduler Simulator** is a web-based application designed to help users understand and visualize various CPU scheduling algorithms. This project provides an interactive interface where users can input processes, select scheduling algorithms, and analyze key performance metrics such as Turnaround Time and Waiting Time.

---

## Features

- **Supports multiple CPU scheduling algorithms:**
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF)
  - Round Robin (RR)
  - Priority Scheduling

- **Process Input Interface:**  
  - Allows users to enter process details, including Burst Time, Arrival Time, and Priority.

- **Visualization:**
  - Generates Gantt charts for process execution.
  - Displays a comparison of scheduling algorithms.

- **Performance Metrics:**
  - Computes Waiting Time, Turnaround Time, and Response Time for all processes.

---

## File Structure

CPU-scheduler-simulator/
│── index.html             
│── README.md                  
│── .gitignore              
│
├── css/               
│   ├── style.css         
│   ├── bootstrap-simplex.css 
│   ├── cpu-scheduler.css   
│   ├── explanation.css      
│
├── js/--cpu-scheduler.js
---

## Technologies Used

- **HTML5** – For structuring the webpage.  
- **CSS3** – For styling the user interface.  
- **JavaScript (Vanilla JS)** – For implementing scheduling logic and UI interactions.  
- **Chart.js** – Used for visualizing scheduling results.  
- **Git & GitHub** – Version control and repository hosting.

---

## Installation & Usage

### 1. Clone the Repository
bash
git clone https://github.com/Babulal20073/CPU-scheduler-simulator.git
cd CPU-scheduler-simulator
2. Run Locally
Open index.html in any modern web browser.

Enter process details in the input fields.

Select a scheduling algorithm from the dropdown menu.

Click "Simulate" to view results.

Use Cases
Educational Tool: Helps students understand CPU scheduling concepts.

Algorithm Analysis: Allows users to compare different scheduling strategies.

Project Demonstration: Useful for operating systems coursework and assignments.

Contribution Guide
Fork the Repository

Clone Your Fork
git clone https://github.com/your-username/CPU-scheduler-simulator.git

Create a Feature Branch
git checkout -b feature/new-feature
Make Changes & Commit
git add .
git commit -m "Added feature: new visualization for Gantt chart"
Push & Create Pull Request
git push origin feature/new-feature

Submit a Pull Request on GitHub.

Version Control Log
Initial Commit
Created project repository and set up the basic file structure.

Designed the main interface with HTML, CSS, and JavaScript.

Styled the UI using Bootstrap and custom CSS.

Implemented core scheduling algorithms: FCFS, SJF, Round Robin, Priority Scheduling.

Final Update
Added Gantt Chart and bar charts for Turnaround Time & Waiting Time.

Integrated dropdown selection with algorithm details (advantages & disadvantages).

Optimized JavaScript for efficiency and fixed UI bugs.

Added a detailed README.md and finalized documentation.

License
This project is licensed under the MIT License. Feel free to modify and distribute it as per the terms of the license.

Acknowledgments
Thanks to all contributors and the open-source community for supporting this project.
For more details, visit the GitHub Repository.


Summary of Additions:
- **File Hierarchy**
- **Technology Stack**
- **Use Cases**
- **Version Control Log (Git-style commits)**
- **Contribution Guide**
- **Proper Markdown Formatting**

