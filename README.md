# CC 101 Computing Portfolio
 
This repository contains my laboratory outputs and documentation for *CC 101 Introduction to Computing* at **Sorsogon State University – Bulan Campus**.
 
## About Me
 
- **Name:** [JOHN SHIEN LITON. FORTE]
- **Program and Section:** [BSCS 1-1]
- **Interests:** [Hanging out with friends: Gaming: Combat Sports]
- **Goal:** [To become cybersecurity in the AFP]
 
## Course Information
 
| Item | Details |
| --- | --- |
| Course | CC 101 Introduction to Computing |
| Instructor | [JOHN MARK D. GABRENTINA] |
| Academic Year | 2026–2027 |
 
## Portfolio Contents
 
1. [Week 7 – Pseudocode and Flowcharts](week07-algorithms/)
2. More activities will be added each week.
 
## Sample Pseudocode: Decimal to Binary
 
```text
START
INPUT decimalNumber
IF decimalNumber = 0 THEN
    DISPLAY "0"
ELSE
    SET binaryResult = ""
    WHILE decimalNumber > 0 DO
        SET remainder = decimalNumber MOD 2
        SET binaryResult = remainder + binaryResult
        SET decimalNumber = decimalNumber DIV 2
    ENDWHILE
    DISPLAY binaryResult
ENDIF
END