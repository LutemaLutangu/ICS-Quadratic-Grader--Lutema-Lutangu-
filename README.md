# ICS Quadratic Grader - Lutangu Lutema 202405510
This single-page web app performs two functions:
1 . **Solves a quadratic equation (ax2 + bx
2. **Converts a numeric score (0-100) into a letter grade**
 Quadratic Solver
 lnPUtS.•
-	a, b, c Coefficients of the quadratic equation
-	Validation ensures:  a' cannot be 0
-	All inputs must be valid numbers
 Outputs:
-	Discriminant (D = b 2 - 4ac) - Nature of roots:
-	D > 0 -+ Two distinct real roots
-	D = 0 -+ One real repeated root
-	D < 0 -+ Two complex conjugate roots - Computed roots displayed with two decimal places.
## Grading System
 Input:
-	A single score (integer from 0 to 1 00)
 output:
-	The corresponding letter grade based on this scale:
I Score Range I Grade I
 
| 85-100 | A+ I
| 75-84 | A l
| 65-74 | B+ I
| 60-64 B I
| 55-59 | c+ I
| 50-54 | c I
| 0-49 | D I
## (O Edge Cases
-	Handles invalid or empty inputs gracefully.
-	Example:
_ 85 A+
 
## How to Run
1.	Download or clone this repository: https://github.com//ICS-Quadratic-GraderLutemaLutangu
2.	Make sure all three files are in the same folder: - index.html
- style.css
- script.js
3. Double-click 'index.html' to open it in your browser.
Works completely offline.
 Test Cases
### Quadratic Solver
I a l b I c I Expected Roots I
I l 1 -3 1 2 1 	I
I l 1 2 1 1 1 	1
I l 1 2 1 5 1 Complex roots I
 Grading System
I Score I Expected Grade I
| 100 A+ I
85 A+
1 75 1 A l
1 65 1 B+  
| 55 | c+ I
1 49 I D I
 Author
**Name•** Lutema Lutangu
**Course•** ICS
 202405510
**Project:** Quadratic Solver & Grading
System
