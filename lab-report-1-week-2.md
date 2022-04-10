# Lab Report 1
## Part 1: Setting Up Visual Studio Code
Using a browser, I searched online to install [Visual Studio Code](https://code.visualstudio.com/).

Since my laptop uses Windows, I downloaded VSCode for Windows x64.

I went to my downloads in file explorer and ran VSCodeUserSetup-x64 to install and launch VSCode for the first time.

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/Lab%201%20-%20Part%201.png)
***
## Part 2: Remotely Connecting
In order for my laptop to be connected to a remote computer, I installed the [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh) extension in VSCode. On the other hand, I could of also installed OpenSSH for Windows.

I would access the terminal tab to generate a new terminal and type/enter `ssh cs15lsp22zz@ieng6.ucsd.edu` (where `zz` replaced by my account username).

Then I would type/enter `yes` to the first time prompt and enter my `Password:` _hidden while typing_--that was [changed](https://sdacs.ucsd.edu/~icc/index.php) prior for setup--to be logged into the remote computer.

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/Lab%201%20-%20Part%203.png)
***
## Part 3: Trying Some Commands
In the terminal, I will type/enter the following commands.
The following commands that I typed/enter involves `cd`, `ls`, `cp`, and `cat`.

`cd ~`

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/Lab%201%20-%20Part%204a.png)

`cd`

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/Lab%201%20-%20Part%204b.png)

`ls -lat`

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/Lab%201%20-%20Part%204c.png)

`ls -a`

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/Lab%201%20-%20Part%204d.png)

`ls <directory>`

![Image](https://github.com/JSN3/cse15l-lab-reports/blob/main/Lab%201%20-%20Part%204e.png)

`cp /home/linux/ieng6/cs15lsp22/public/hello.txt ~/`

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/Lab%201%20-%20Part%204f.png)

`cat /home/linux/ieng6/cs15lsp22/public/hello.txt`

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/Lab%201%20-%20Part4g.png)
***
# Part 4: Moving Files with `scp`
Using VSCode, I would create the file `WhereAmI.java` with the provided code.

![Image](https://github.com/JSN3/cse15l-lab-reports/blob/main/Lab%201%20-%20Part%205a.png)

Then I will type/enter the provided code into the terminal `scp WhereAmI.java cs15lsp22zz@ieng6.ucsd.edu:~/` (where `zz` is replaced by my account username) to log in and enter `ls` in the terminal to check if the file has been successfully copied.

![Image](https://github.com/JSN3/cse15l-lab-reports/blob/main/Lab%201%20-%20Part%205b.png)
***
# Part 5: Setting an SSH Key
To set an SSH Key, I would type/enter the provided code into the terminal `ssh-keygen` and hit enter twice for no passphrase.

Then I would enter the provided code into the terminal `$ ssh cs15lsp22zz@ieng6.ucsd.edu` (where `zz` is replaced by my account username) to log in to type/enter the provided code into the terminal `mkdir .ssh` and then `CTRL + D` to log out.

Finally, I would type/enter the provided code into the terminal `$ scp /Users/<user-name>/.ssh/id_rsa.pub cs15lsp22zz@ieng6.ucsd.edu:~/.ssh/authorized_keys` (where `<user-name>` is replaced by the result that was given from typing/entering `ssh-keygen` and `zz` is replaced by my account username) to generate an SSH key to bypass entering my password.

![Image](https://raw.githubusercontent.com/JSN3/cse15l-lab-reports/main/Lab%201%20-%20Part%206.png)
***
# Part 6 - Optimizing Remote Running
