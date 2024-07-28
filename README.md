## COBOL Sample Scripts


## Purpose

This codebase implements a comprehensive test suite for COBOL inter-program communication features, including CALL statements, parameter passing, and program state management. It tests various aspects of subprogram calls, data sharing between programs, and program initialization/termination behaviors.

## Overview of Files

| File | Description |
|------|-------------|
| IC101A.CBL | Main program testing basic CALL functionality |
| IC102A.CBL | Subprogram called by IC101A |
| IC103A.CBL | Tests multiple EXIT PROGRAM statements and parameter passing |
| IC104A.CBL | Subprogram for testing parameter passing |
| IC105A.CBL | Subprogram with multiple EXIT PROGRAM statements |
| IC106A.CBL | Tests index data items and table handling in subprograms |
| IC107A.CBL | Subprogram for index and table operations |
| IC108A.CBL | Tests a sequence of subprogram calls |
| IC109A.CBL | First subprogram in a call sequence |
| IC110A.CBL | Second subprogram in a call sequence |
| IC111A.CBL | Third subprogram in a call sequence |
| IC112A.CBL | Tests file handling operations in subprograms |
| IC113A.CBL | Subprogram for file record validation |
| IC114A.CBL | Tests file operations across multiple subprogram calls |
| IC115A.CBL | Subprogram for file creation and verification |
| IC116M.CBL | Tests CALL without USING phrase |
| IC117M.CBL | Subprogram called without parameters |
| IC118M.CBL | Nested subprogram call |
| IC201A.CBL | Tests various CALL statement features |
| IC202A.CBL | Subprogram for parameter passing tests |
| IC203A.CBL | Tests CALL and CANCEL statements |
| IC204A.CBL | Subprogram for testing program state |
| IC205A.CBL | Tests CANCEL statement and subprogram state |
| IC206A.CBL | Subprogram for CANCEL tests |
| IC207A.CBL | Tests variable-length tables in subprograms |
| IC208A.CBL | Subprogram for table operations |
| IC209A.CBL | Tests subprogram calls and cancellations |
| IC210A.CBL | First subprogram in a call/cancel sequence |
| IC211A.CBL | Second subprogram in a call/cancel sequence |
| IC212A.CBL | Third subprogram in a call/cancel sequence |
| IC213A.CBL | Tests BY CONTENT parameter passing |
| IC214A.CBL | Subprogram for BY CONTENT tests |
| IC215A.CBL | Subprogram for CANCEL tests |
| IC216A.CBL | Tests data item redefinition in subprogram calls |
| IC217A.CBL | Subprogram for data redefinition tests |
| IC222A.CBL | Subprogram for computational data tests |
| IC223A.CBL | Another subprogram for computational data tests |
| IC224A.CBL | Tests BY CONTENT with computational data |
| IC225A.CBL | Tests various combinations of BY REFERENCE and BY CONTENT |
| IC226A.CBL | Tests EXTERNAL data items |
| IC227A.CBL | Tests operations on external files |
| IC228A.CBL | Tests GLOBAL data items |
| IC233A.CBL | Tests USE procedures across nested programs |
| IC234A.CBL | Another test for USE procedures in nested programs |
| IC235A.CBL | Tests complex parameter passing scenarios |
| IC237A.CBL | Tests data item redefinition in parameter passing |
| IC401M.CBL | Tests flagging of high subset features in inter-program communication |

## File Interactions

1. IC101A calls IC102A to test basic CALL functionality.
2. IC103A calls IC104A and IC105A to test parameter passing and multiple EXIT PROGRAM statements.
3. IC106A calls IC107A to test index data items and table handling.
4.

