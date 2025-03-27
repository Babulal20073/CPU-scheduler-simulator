# CPU-scheduler-simulator
# CPU Scheduler Simulator

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

CPU-scheduler-simulator/ │── index.html # Main HTML file (UI structure) │── README.md # Project Documentation │── LICENSE # License File │── .gitignore # Git Ignore File │── css/ │ ├── style.css # Stylesheet for UI │── js/ │ ├── main.js # Core logic and algorithm implementations │ ├── fcfs.js # First Come First Serve Algorithm │ ├── sjf.js # Shortest Job First Algorithm │ ├── round_robin.js # Round Robin Algorithm │ ├── priority.js # Priority Scheduling Algorithm │── assets/ │ ├── images/ # Stores images used in the UI │── docs/ │ ├── project_report.pdf # Documentation and Reports

yaml
Copy
Edit

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
```bash
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

bash
Copy
Edit
git clone https://github.com/your-username/CPU-scheduler-simulator.git
Create a Feature Branch

bash
Copy
Edit
git checkout -b feature/new-feature
Make Changes & Commit

bash
Copy
Edit
git add .
git commit -m "Added feature: new visualization for Gantt chart"
Push & Create Pull Request

bash
Copy
Edit
git push origin feature/new-feature
Submit a Pull Request on GitHub.

Version Control Log
sql
Copy
Edit
<<<<<<< HEAD

CPU Scheduler Simulator

=======
Initial Commit
>>>>>>> 72ac4b5 (Created basic interface for CPU scheduling simulator)

<<<<<<< HEAD

Implemented FCFS Algorithm

=======
Added Gantt Chart for visualization
>>>>>>> 9bc3d2f (Gantt chart integrated for process execution visualization)

<<<<<<< HEAD

Implemented SJF Algorithm

=======
Added SJF Algorithm with user input validation
>>>>>>> e4a5f1a (Shortest Job First Algorithm added with optimized execution)
License
This project is licensed under the MIT License. Feel free to modify and distribute it as per the terms of the license.

Acknowledgments
Thanks to all contributors and the open-source community for supporting this project.

🚀 For more details, visit the GitHub Repository.

markdown
Copy
Edit

---

Summary of Additions:
- **File Hierarchy**
- **Technology Stack**
- **Use Cases**
- **Version Control Log (Git-style commits)**
- **Contribution Guide**
- **Proper Markdown Formatting**

This README now looks professional, detailed, and structured. Let me know if you need modifications! 🚀






