# Lab Report 3 - More SSH Stuff

***

## Choice 1 - Streamlining SSH Configuration
In the beginning, I did not have a .ssh/config path, so I had to use the Windows command `$null > config` in order to create a config file.

Here is my config file, initially the content of the file was empty, so I used VS Code in order to edit the config file.

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR3%20Choice%20A%20-%20Part%201.png)

After the config file is complete, I can log in to the remote computer with the new username I made.

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR3%20Choice%20A%20-%20Part%202.png)

I can copy a file much quicker to the remote computer when I use `copy.java` as an example java file to copy.

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR3%20Choice%20A%20-%20Part%203.png)

***

## Choice 2 - Setup Github Access from ieng6
Where the public key is stored in my Github:

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR3%20Choice%20B%20-%20Part%201a.png)

Where the public/private key is stored in my account:

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR3%20Choice%20B%20-%20Part%201.png)

Using git commands to commit and push a change to Github while logged in to ssh:

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/LR3%20Choice%20B%20-%20Part%202.png)

[Resulting Commit](https://github.com/JSN3/markdown-parser/commit/b3be8a18462b924657a8598edaffb6811f8b41fb)

## Choice 3 - Copying whole directories with `scp -r`
