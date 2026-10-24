# README Audit

## README Fact-Check Table

| Claim Made in README | True? | Evidence / Correction Made |
|---|---|---|
| Program stores student names and marks | Yes | The list `d` contains five student records with names and three subject marks. |
| Program calculates total marks | Yes | Function `f(x)` adds the values from index `1` onward. |
| Program calculates each student's average | Yes | `a = s / 3` divides the total by three subjects. |
| Program assigns grades based on averages | Yes | The `if-elif-else` statements assign grades A, B, C, D, or F. |
| Program calculates the class average | Yes | `t2` accumulates student averages, which are divided by `len(d)`. |
| Program identifies the topper | Yes | The comparison `if a > h` updates the highest average and student's name. |
| Program uses nested lists | Yes | `d` contains lists of student names and marks. |
| Program uses a function | Yes | `def f(x):` defines the function that calculates total marks. |
| Program uses loops | Yes | `for` loops process student records and calculate results. |
| Program uses conditional statements | Yes | The grade assignment and topper comparison use `if` statements. |
| Program processes five students | Yes | The list `d` contains five student records. |
| Program accepts marks from user input | No | The student data is predefined in `d`; no `input()` call exists. |
| Program stores data in a dictionary | No | The student records are stored in lists, not dictionaries. |
| Program uses the `math` module for calculations | No | `import math` is present, but no function or constant from `math` is used. |
| Program requires external Python packages | No | No external packages are imported. |
| Program displays student reports | Yes | The code prints `REPORT` and prints each student's details. |
| Student details are printed with clear labels and separators | No | `print(d[i][0] + "" + str(s) + "" + str(a) + "" + g)` concatenates values without spaces or labels. |
| Program prints the class average | Yes | The code prints the result using `Class average:`. |
| Program prints the topper's name and average | Yes | The final statement prints `Topper:` followed by the name and highest average. |
| Program handles invalid marks or missing data | No | No input validation or explicit error-handling logic is present. |
| The Python file is named `messy.py` | Yes | The uploaded file is named `messy.py`. |
| The repository contains `README.md` and `README_AUDIT.md` | Cannot Verify | The uploaded Python file alone cannot confirm the repository's complete file structure. |
| The project has no license | Cannot Verify | The code does not establish the repository's license status. |

## Audit Conclusion

The README's main claims about calculating totals, averages, grades, the class average, and the topper are supported by the code.

The program uses predefined student data and does not accept user input. The `math` module is imported but unused. Student details are printed without clear separators, which may reduce readability.

Repository structure and license information require separate verification.
