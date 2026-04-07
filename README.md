# Campus Event Placement System
### Java Project | Beginner-Friendly | Backtracking Algorithm

---

## Project Description

The **Campus Event Placement System** is a Java console application that schedules N college events across N venues such that **no two events interfere spatially**.

It is modeled after the classic **N-Queens problem** using a **recursive backtracking** algorithm. The program:
- Accepts a number of events from the user
- Finds **all valid placement layouts**
- Displays each layout as a visual grid
- Reports the total number of valid layouts

---

## Files Included

| File | Description |
|------|-------------|
| `CampusEventPlacement.java` | Main Java source code |
| `ProjectProposal.docx` | Project proposal (Word format) |
| `ProjectProposal.pdf` | Project proposal (PDF format) |
| `README.md` | This file — execution guide |

---

## Requirements

- Java JDK 8 or above
- Any terminal / command prompt
- Or any IDE: IntelliJ IDEA, Eclipse, VS Code

---

## Steps to Run

### Option 1: Command Line

**Step 1 — Compile the program:**
```bash
javac CampusEventPlacement.java
```

**Step 2 — Run the program:**
```bash
java CampusEventPlacement
```

**Step 3 — Enter input when prompted:**
```
Enter the number of events to place: 4
```

---

### Option 2: Using an IDE (IntelliJ / Eclipse)

1. Open your IDE and create a new Java project
2. Copy `CampusEventPlacement.java` into the `src` folder
3. Run the file (Shift + F10 in IntelliJ, or Ctrl + F11 in Eclipse)
4. Enter the number of events in the console

---

## Input Format

- A single positive integer representing the number of events
- Example: `4`

---

## Output Explanation

The program outputs:
- **Each valid layout** numbered as "Layout #1", "Layout #2", etc.
- A grid where:
  - `E` = Event is placed at this venue spot
  - `.` = Empty venue spot
- **Total count** of all valid layouts at the end

### Example Output (Input = 4):

```
Finding all valid event placements for 4 events...

Layout #1:
  Venue 1:  .  E  .  .
  Venue 2:  .  .  .  E
  Venue 3:  E  .  .  .
  Venue 4:  .  .  E  .

Layout #2:
  Venue 1:  .  .  E  .
  Venue 2:  E  .  .  .
  Venue 3:  .  .  .  E
  Venue 4:  .  E  .  .

----------------------------------------------
Total valid layouts found: 2
```

---

## Known Results

| Number of Events (N) | Valid Layouts |
|----------------------|---------------|
| 1 | 1 |
| 2 | 0 |
| 3 | 0 |
| 4 | 2 |
| 5 | 10 |
| 6 | 4 |
| 8 | 92 |

---

## Concepts Used

- Recursion
- Backtracking
- Arrays
- Loops and conditionals
- Console I/O with Scanner

---

*Developed as part of Java Programming coursework.*
