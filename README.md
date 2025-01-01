# Timetable Scheduling Using Genetic Algorithm  

## Overview  
This project implements a **Timetable Scheduling System** for exam allocation using a **Genetic Algorithm (GA)**. The system efficiently schedules exams while adhering to predefined hard and soft constraints. It is designed for educational institutions to streamline their exam timetables.  

## Features  
- **Genetic Algorithm Implementation**:  
  - Population initialization, fitness evaluation, parent selection, crossover, and mutation.  
  - Iterative optimization to generate feasible and optimal schedules.  
- **Constraint Management**:  
  - **Hard Constraints**:  
    - No student or teacher exam clashes.  
    - Exams must be invigilated.  
    - No exams on weekends.  
  - **Soft Constraints**:  
    - Minimize exam days.  
    - Prioritize management courses before core subjects.  
- **Dynamic Scheduling**:  
  - Configurable parameters, including population size, number of generations, and mutation/crossover probabilities.  
- **Visual and Statistical Output**:  
  - Clear visual representation of schedules.  
  - Evaluation of constraint satisfaction and fitness metrics.  

## Technologies Used  
- **Programming Language**: Python  
- **Libraries**: NumPy, Collections, CSV, Colorama  
- **Backend Logic**: Genetic Algorithm-based optimization  

## Project Structure  
```plaintext
├── main.py                 # Main implementation of the Genetic Algorithm  
├── data/                   # Data files for courses, teachers, and students  
│   ├── courses.csv          # Course data  
│   ├── t_teachers.csv       # Teacher data  
│   ├── t_studentcourses.csv # Student and their courses data  
├── README.md               # Project documentation  
├── requirements.txt        # Python dependencies  
