# AI-Based Exam Scheduler

An intelligent exam scheduling system built in **Python** using **backtracking** and **constraint satisfaction** techniques. This tool generates **conflict-free exam timetables** while satisfying constraints like student exam overlap, room capacities, and minimum time gaps between exams.

---

## Features

- Clash-free scheduling of exams  
- Room capacity management  
- Time gap enforcement between exams for students  
- Customizable input for courses, students, rooms, and time slots  
- Modular code with clear logic for constraints and backtracking  

---

## Tech Stack

- **Language:** Python  
- **Concepts:** Constraint Satisfaction Problems (CSP), Backtracking  
- **Input/Output:** Text-based files or dictionaries (easily adaptable to CSV or DB)

---

## File Structure

```
├── exam_scheduler.ipynb       # Main Python script
├── README.md                # Project documentation
└── 📁 dataset/               # Input files
    ├── courses.xlsx
    ├── studentCourse.xlsx
    ├── studentNames.xlsx
    └── teachers.xlsx

```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/exam-scheduler.git
   cd exam-scheduler
   ```

2. Place your input Excel files in the `dataset/` folder (or use the sample ones provided).

3. Run the script:
   ```bash
   python exam_scheduler.py
   ```

4. View the output schedule in the terminal or export it as needed.

---

## Dataset Files

| File               | Description                              |
|--------------------|------------------------------------------|
| `courses.xlsx`     | List of course codes/names               |
| `studentCourse.xlsx` | Mapping of students to enrolled courses |
| `studentNames.xlsx` | List of student IDs and names            |
| `teachers.xlsx`    | Teacher-course assignments                |

---

## Example Constraints

- A student cannot have two exams at the same time.  
- Each room has a limited capacity.  
- There must be a gap between two exams for the same student.  

---


## Credits

Developed as part of an **AI course project** at FAST NUCES – Spring 2024.  
Author: [Areej Zeb](https://www.linkedin.com/in/areejzeb)
