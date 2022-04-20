# Lab Report 2 - Commits and Fixing
***
*The default markdown style of embedded links is `[name](website link)` provided in the default test-file.md.*
## Problem 1 - Retrieving links when the format is `[name][website link]`
[Failure-Inducing Input Test File](https://github.com/JSN3/markdown-parser/blob/main/test-file2.md)

Commit of the incorrect output produced from the terminal
![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR2%20-%20Part%201c.png)

Commit of the fixed solution
![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR2%20-%20Part%201a.png)

The failure-inducing input would be the corrupt markdown file in which there is a incorrect format of a link markdown that differs to requirements of the original program. The input prompts a bug when there is a logic error present in the while loop where after the program finds the initial `"[" and "]`, the program should be searching for another `"[" and "]"` rather than `"(" and ")"`. The bug results in a symptom of a faulty behavior (*IndexOutOfBounds*) where the program is unable to finish correctly.

***

## Problem 2 - Retrieving links when the format is `(name)[website link]`
[Failure-Inducing Input Test File](https://github.com/JSN3/markdown-parser/blob/main/test-file3.md)

Commit of the incorrect output produced from the terminal
![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR2%20-%20Part%202c.png)

Commit of the fixed solution
![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR2%20-%20Part%202a.png)

The failure-inducing input would be the corrupt markdown file in which there is a incorrect format of a link markdown that differs to the requirements of the original program. The input prompts a bug when there is a logic error present in the while loop where after the program finds the inital `"(" and ")"` program is unable to end and grab the links properly because it has to find `"[" and "]"` in which the program is intended to find first. The bug results in a symptom of a faulty behavior (*OutOfMemoryError*) where the program cannot end and if used `break` the links are not grabbed.

***

## Problem 3 - Retrieving links when the format is `(website link)`
[Failure-Inducing Input Test File](https://github.com/JSN3/markdown-parser/blob/main/test-file4.md)

Commit of the incorrect output produced from the terminal
![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR2%20-%20Part%203c.png)

Commit of the fixed solution
![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR2%20-%20Part%203a.png)

The failture-inducing input would be the corrupt markdown file in which there is a incorrect format of a link markdown that differs to the requirements of the original program. The input prompts a bug when there is a logic error present in the while loop where the program tries to find `"[" and "]"` and since unable to, the indexes result in -1 which can never end the while loop. The bug results in a symptom of a faulty behavior (*OutOfMemoryError*) where the program cannot end and if used `break` all of the links are not grabbed.
