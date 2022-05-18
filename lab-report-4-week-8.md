# Lab Report 4 - More markdown-parser Scenarios

***

## markdown-parser repositories
[my markdown-parser](https://github.com/JSN3/markdown-parser)

[reviewed markdown-parser](https://github.com/grantcoz/markdown-parse) (repository reviewed in Week 7)

***

## Testing Snippet 1

__expectations for both java files__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%201a-2a.png)

__JUnit Tests in MarkdownParse.Test__

__my java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%201b.png)

__other java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%202b.png)

__Terminal Output__

__my java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%201c.png)

__other java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%202c.png)

***

## Testing Snippet 2

__expectations for both java files__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%203a-4a%20alt.png)

__JUnit Tests in MarkdownParse.Test__

__my java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%203b%20extra.png)

__other java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%204b%20extra.png)

__Terminal Output__

__my java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%203c%20extra.png)

__other java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%204c%20extra.png)

***

## Testing Snippet 3

__expectations for both java files__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%205a-6a.png)

__JUnit Tests in MarkdownParse.Test__

__my java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%205b.png)

__other java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%206b.png)

__Terminal Output__

__my java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%205c.png)

__other java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%206c.png)

***

# Analysis of the Snippet Tests

## code change for snippet 1
I do not believe there is a small code change (<10 lines) that will make my program work for snippet 1 and all related cases that use incline code with backticks due to my coding abilities and the way that I built my program. My suggested change might be longer, involved, and redundant through a conditional that will check for backticks and when the conditional is true, then the program will run a separate filter made for backticks where the `currentIndex` will start where the last ] is located and the program will use the parentheses and backtick indices to find a link in between. In addition, there may be an extra for loop and ArrayList to filter out the same links if necessary.

## code change for snippet 2
I do not believe there is a small code change (<10 lines) that will make my program work for snippet 2 and all related cases that use nested parentheses, brackets, and escape brackets due to like snippet 1 of my coding abilities and the way that I built my program. My suggest change might be longer, involved, and redundant through a conditional that will check what symbols are present for the program to run a seprate filter in which `currentIndex` should start from an open symbol and find a closing symbol and take the text between into a ArrayList for every symbol instance and have a another ArrayList that will take strings that have the "." in them as a valid link. In addition, there may be an extra for loop and ArrayList to filter out the same links if necessary.

## code change for snippet 3
I do not believe there is a small code change (<10 lines) that will make my program work for snippet 3 and all related cases that use newlines in brackets and parenthesis due to like other snippets of my coding abilities, the way that I built my program, and the randomness of a user's particular link format. My suggested change might be longer, involved, redundant, and fixed through identifying the string "https" as the start for `currentIndex` and to the end at a index of a new line which in string format would be "\n" where an ArrayList will take the text in between which supposedly is the link in  a fixed https format other formats may need me to use more conditionals. In addition, there may be an extra for loop and ArrayList to filter out the same links if necessary.
