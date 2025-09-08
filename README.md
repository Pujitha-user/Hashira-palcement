# Hashira Placements Assignment - Java Solution

This repository contains a Java solution for the **Hashira Placements Assignment**. The program reads polynomial root test cases from JSON files, decodes values in various bases, and calculates the constant term \(C\) of the polynomial using Lagrange interpolation.

---

## Problem Summary

Given JSON input files with roots in different base notations, decode these values and find the constant term \(C\) of the polynomial defined by the roots. The polynomial degree and number of roots needed are provided in the JSON.

---

## Features

- Reads JSON test cases from file without using external JSON parsing libraries.
- Decodes roots from arbitrary bases (2 to 16+).
- Uses Lagrange interpolation to solve for the constant term \(C\).
- Suitable for fixed-format JSON inputs as provided in assignment.
- Can be executed easily in Eclipse or any Java IDE.

---

## Files Included

- `HashiraSolverNoLib.java` - Java source code solving the assignment.
- `input1.json` - Sample test case 1 JSON file with roots and bases.
- `input2.json` - Sample test case 2 JSON file with roots and bases.

---

## Usage Instructions

1. Clone or download this repository.
2. Place the JSON files `input1.json` and `input2.json` in the root folder of your project.
3. Open the project in Eclipse or your preferred Java IDE.
4. Compile and run `HashiraSolverNoLib.java`.
5. The console will display the constant term \(C\) for each test case.

---

## Example Output
File: input1.json | Constant term (C): 3
File: input2.json | Constant term (C): -6290016743746478048

---

## Notes

- This solution uses manual string parsing with regex to extract information from JSON files due to the constraint of no external libraries.
- Input JSON file format should follow the samples provided exactly.
- The result is rounded to the nearest integer for output.

---

## License

This project is open source and available for educational use.

---

Feel free to reach out for questions or improvements!


