# Digital Stopwatch Logic Simulation (Core Java & OOP)

A console-based **Digital Stopwatch Logic Simulation** built using **Core Java** and **Object-Oriented Programming (OOP)** concepts.  
This project demonstrates clean OOP design, encapsulation, and accurate stopwatch timing using internal state management.

---

## Author
**Yash Kumar Singh**  
ERP: **RU 25 11630**

---

## Features
- ✅ Start Stopwatch
- ✅ Stop / Pause Stopwatch (elapsed time is preserved)
- ✅ Resume Stopwatch (continue timing)
- ✅ Reset Stopwatch (elapsed time becomes 0)
- ✅ Display elapsed time in **milliseconds**

---

## Technologies Used
- **Java (Core Java)**
- **OOP Concepts**
  - Encapsulation
  - Class design
  - Method-based state transitions

---

## Project Logic
The stopwatch functionality is implemented using a `Stopwatch` class that encapsulates:
- `startTime`
- `elapsedTime`
- `isRunning`

It uses `System.currentTimeMillis()` to calculate elapsed time correctly during multiple start/stop cycles.

---

## How to Run
1. Clone the repository
2. Open the project in any Java IDE (Eclipse / IntelliJ / VS Code)
3. Run the `main` method in the demo class (e.g., `StopwatchDemo` / `Main`)

---

## Project Structure (Typical)
- `Stopwatch` class
  - `start()`
  - `stop()`
  - `reset()`
  - `getElapsedTime()`
- `StopwatchDemo` / `Main` class
  - console interaction (optional menu)

---

## Sample Output
```text  
Stopwatch Started...  
Elapsed Time: 2500 ms  

Stopwatch Paused...  
Elapsed Time: 2500 ms  

Stopwatch Reset...  
Elapsed Time: 0 ms  
