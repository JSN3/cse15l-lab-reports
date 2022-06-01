# Lab Report 5 - MarkdownParse with Multiple Files

***

## markdown-parse repositories
[my markdown-parser](https://github.com/JSN3/markdown-parser)

[reviewed markdown-parser](https://github.com/nidhidhamnani/markdown-parser)

***

## Test Results

I found tests with different results using vimdiff.

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-5-photos/Part%201.png)

_For the results generated from my markdown-parse file, `[]` represents an IndexOutOfBoundsException, instead of printing out the long error statements I have simplified them to represent an empty ArrayList result as my most of my test files had an error or would not load with my MarkdownParse.java while for the other markdown-parse file `[]` represents a standard case of an empty ArrayList where nothing was added._

***

## Test-File with Different Results

I have chose to compare two test files 212.md and 230.md out of the 652 tests provided.

[212.md](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/212.md)

[230.md](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/230.md)

***

## Analysis of 212.md

my output vs. other output

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-5-photos/Part%204a1.png)

Both implementations are incorrect because 212.md contains no links, so the program should return an empty ArrayList.

expectations: both should share the same outcome

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/lab-report-5-photos/Part%204b.png)

