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

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%203a-4a.png)

__JUnit Tests in MarkdownParse.Test__

__my java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%203b.png)

__other java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%204b.png)

__Terminal Output__

__my java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%203c.png)

__other java file__

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-4-photos/LR4%20-%20Part%204c.png)

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
I do not believe there is a small code change (<10 lines) that will make my program work for snippet 1 and all related cases that use incline code with backticks due to my coding abilities. My suggested change might be longer and involved through a conditional that will check for backticks and when the conditional is true, then the program will run a separate filter made for backticks where the currentIndex will start where the last ] is located and the program will use the parentheses and backtick indices to find a link. In addition, there may be an extra for loop to filter out the same links if necessary.

## code change for snippet 2
s
