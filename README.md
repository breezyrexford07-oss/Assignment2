
# 🔊 Arduino Assignment 2 – Beeping Countdown

## Project Overview

This repository contains my submission for **Assignment 2** in the **Programming C++ for Engineers Using Arduino** course.

The project demonstrates how to combine a **passive buzzer** and a **single-digit 7-segment display** to create a countdown system. The display counts down from **9 to 0**, producing a short beep at every number. When the countdown reaches **0**, the buzzer plays a longer tone to indicate completion.

---

## Features

- Countdown from **9 to 0**
- Short beep for every countdown step
- Long completion tone at the end
- Serial Monitor displays countdown progress
- Uses reusable functions for cleaner code
- Demonstrates arrays, loops, and Arduino output devices

---

## Hardware Components

- Arduino Uno
- Passive Piezo Buzzer
- Single-Digit Common Cathode 7-Segment Display
- 220Ω Resistor
- Breadboard
- Jumper Wires
- USB Cable

---

## Pin Connections

### Buzzer

| Component | Arduino Pin |
|-----------|-------------|
| Positive (+) | D8 |
| Negative (-) | GND |

### 7-Segment Display

| Segment | Arduino Pin |
|---------|-------------|
| a | D2 |
| b | D3 |
| c | D4 |
| d | D5 |
| e | D6 |
| f | D7 |
| g | D9 |
| COM | GND (through 220Ω resistor) |

---

## Concepts Demonstrated

- Arduino `tone()` function
- `noTone()` function
- Arrays and 2D Arrays
- Functions with parameters
- `while` loops
- `for` loops
- Serial Monitor output
- 7-Segment display control
- Digital output programming

---

## Program Flow

1. Initialize the Arduino and Serial Monitor.
2. Configure the buzzer and display pins.
3. Count down from **9** to **1**.
4. Display each digit on the 7-segment display.
5. Play a short beep for each countdown step.
6. Display **0**.
7. Play a longer completion tone.
8. Print **"Countdown Complete"** on the Serial Monitor.

---

## How to Run

1. Open the `.ino` file in the Arduino IDE.
2. Connect the Arduino Uno to your computer.
3. Select:

   - **Board:** Arduino Uno
   - **Port:** Your correct COM port

4. Upload the code.
5. Open the **Serial Monitor** (9600 baud).
6. Watch the countdown while listening to the buzzer.

---

## Expected Output

### 7-Segment Display

```
9
8
7
6
5
4
3
2
1
0
```

### Serial Monitor

```
=== Beeping Countdown Starting ===
Counting: 9
Counting: 8
Counting: 7
Counting: 6
Counting: 5
Counting: 4
Counting: 3
Counting: 2
Counting: 1
=== Countdown Complete ===
```

---

## Learning Outcomes

Through this project, I learned how to:

- Generate sounds using a passive buzzer
- Control a 7-segment display
- Use lookup tables with 2D arrays
- Build reusable Arduino functions
- Combine multiple hardware outputs into one project
- Improve Arduino programming using loops and arrays

---

## Author

**Name: AKPENE BRIGHT ALBERT**

**Index Number:2526400957** 

**Course BCE/GRP B** 

---





This version is cleaner, looks more professional on GitHub, and should earn a better presentation impression than the basic template provided in the assignment.
