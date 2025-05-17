# EA_Project
# University Timetable Generator using Genetic Algorithm 

This project is a **University Timetable Generator** built using a **Genetic Algorithm (GA)** and a **Tkinter GUI** in Python. It allows users to input course, department, room, and faculty information and then generates a conflict-free weekly timetable that satisfies a set of basic scheduling constraints.

---

## 📌 Features

- Genetic Algorithm-based Scheduling
- Graphical User Interface using Tkinter
- Input Validation to ensure data integrity
- Automatic Timetable Generation
- Visual Display of Timetables ( Display whole timetable for professors OR Display it based on certain level )
- Dynamic GUI elements based on user-defined inputs (Each subject's professor, Number of student that have signed this subject )

---

## 🧬 How It Works

The application uses a Genetic Algorithm to search for optimal or near-optimal timetable solutions. The GA evaluates each candidate timetable based on how many conflicts (e.g., overlapping lectures, unavailable rooms or lecturers, conflects lectures within same level ) it contains and evolves the population over generations to minimize these conflicts.

---

