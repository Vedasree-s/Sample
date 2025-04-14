# Sample
```cobol
    IDENTIFICATION DIVISION.
    PROGRAM-ID. AddNaturalNumbers.
    DATA DIVISION.
    WORKING-STORAGE SECTION.
    01  N           PIC 9(4) VALUE 0.
    01  I           PIC 9(4) VALUE 0.
    01  SUM         PIC 9(8) VALUE 0.
    PROCEDURE DIVISION.
    BEGIN.
        DISPLAY "Enter the value of N: ".
        ACCEPT N.
        PERFORM VARYING I FROM 1 BY 1 UNTIL I > N
         ADD I TO SUM
        END-PERFORM.
        DISPLAY "The sum of the first ", N, " natural numbers is: ", SUM.
        STOP RUN.
```
#hello 
