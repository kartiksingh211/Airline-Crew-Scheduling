# Airline Crew Scheduling – Backtracking & Constraint Satisfaction  
**Course:** ENCA351 — Design and Analysis of Algorithms (Lab Assignment 4)  
**Name:** Kartik Singh  
**Semester:** V  

---
## Problem Description
This project models a simplified airline crew scheduling problem.
We assign flights to crew members while ensuring:
- No overlapping flights for the same crew member
- A minimum rest time between consecutive flights

## Approach
- Represent flights as `(FlightID, StartTime, EndTime)` tuples.
- Use a constraint checker to validate assignments.
- Apply a recursive backtracking algorithm to assign flights to crew members.
- Perform basic profiling using `time` and `memory_profiler`.

## How to Run
1. Create a virtual environment (optional but recommended).
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
