# Mini Programming Project

## 1. Group Information

**Class:** D
**Group:** 6

### Group Members

| No. | Name | Student ID | Role |
|---|---|---|---|
| 1 | Muhammad Syahril Ramadhan | 2610312109 | Project Coordinator |
| 2 | Gracia Agretta Br Silaen | 2610312116 | Algorithm |
| 3 | Asila Syukria Abdulrahman Al-Kaf | 2610312128 | Flowchart |
| 4 | Marselinus Christian Eka Jati |2610312129 | JavaScript |
| 5 |  Adinda Hanin Ardanty  | 26103121134 | Testing & Documentation |

---

## 2. Project Title

Time & Duration Calculator

---

## 3. Project Description

A program that calculates the elapsed time duration (hours and minutes) based on a start time and an end time entered by the user, in hours and minutes format. There is an option to recalculate the time. 

## 4. Objectives
This project is designed to apply the following programming concepts:

•	Variables

•	Data types (string, number)

•	Operators (arithmetic, comparison, modulo)

•	Conditional statements (if/else)

•	Loops (while)

•	String methods (split)

•	Type conversion (Number)

•	JavaScript (prompt, console.log, Math.floor)
  
---

## 5. Input
The program receives:

•	The choice to start the program (yes/no)

•	Start time (HH:MM format)

•	End time (HH:MM format)

•	The choice to repeat the calculation (yes/no)


---

## 6. Process
The program converts the start and end times into total minutes, then:

•	If the end time (in minutes) is less than the start time, it is assumed to pass midnight, so 1440 minutes are added


•	Duration = total end minutes − total start minutes

•	The duration is converted back into hours (division) and minutes (modulo)

•	The process repeats as long as the user answers "yes" when asked to calculate again

---

## 7. Output
The program displays:

•	The start time entered

•	The end time entered

•	The duration in "X hours Y minutes" format

•	The message "Program selesai." (Program finished) when the user stops repeating

•	The message "Program dihentikan." (Program stopped) if the user chooses "no" at the start


---

## 8. Algorithm

The algorithm used in the program is described in:

`pseudocode.txt`

---

## 9. Flowchart

The flowchart is created using Flowgorithm.

File: 
https://drive.google.com/file/d/1fsE7mnibxUMRc0xIOU2mE2BoZ1mPHhZt/view?usp=sharing

`flowchart.fprg`

---

## 10. JavaScript Implementation

The JavaScript implementation of the program is available in:
LINK:
https://www.programiz.com/online-compiler/47DoXYPvgOKJM 
`program.js`

---

## 11. Testing

The program is tested using several test scenarios.

Testing documentation:

`test-cases.md`
