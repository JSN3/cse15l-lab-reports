# Lab Report 2 - Commits and Fixing
***
*The default markdown style of embedded links is `[name](website link)`.*

## Problem 1 - Retrieving links when the format is `[name][website link]`
[Failure-Inducing Input Test File](https://github.com/JSN3/markdown-parser/blob/main/test-file2.md)

Commit of the output produced from the terminal
![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR2%20-%20Part%201c.png)

Commit of the fixed solution
![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR2%20-%20Part%201a.png)

The failure inducing input would be the corrupt markdown file in which there is a incorrect format of a link markdown that differs to requirements of the original program. The input prompts a bug when there is a logic error present in the while loop where after the program finds the initial `"[" and "]`, the program should be searching for another `"[" and "]"` rather than `"(" and ")"`. The bug results in a symptom of a faulty behavior (*IndexOutOfBounds*) where the program is unable to finish correctly.
