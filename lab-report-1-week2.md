
## Installing VScode ##

- Go to the Visual Studio Code website [https://code.visualstudio.com/](https://code.visualstudio.com/) to download and install VScode into your computer

- When it is installed, it should look something similar to the image below

![](https://github.com/LuffySaito/cse15l-lab-reports/blob/5956297647c4e1e12c18004d4ed38914bd02eb39/vscode.png)

## Remotely Connecting ##

- First install OpenSSh into your computer (use [Install OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse) for help)

- Open a new terminal in VScode and type the command `ssh cs15lsp22zz@ieng6.ucsd.edu` where `zz` is replaced with your letters in your course-specific acount

- enter password and you should see something similar to the image below

![](https://github.com/LuffySaito/cse15l-lab-reports/blob/e4b7144675a7c3ead4d94820f4fb12bfe30c5375/remote_connect.png)

## Trying Some Commands ##

- In the terminal, try running some commands, including:
    - `ls` : list files
    - `pwd` : print working directory 
    - `mkdir` : make directory
    - `cd` : change directory
    - `cp` : copy
    - `rm` : remove
    - `touch` : creat a file
    - `cat` : view or create a file

- Try exploring different commands on both your computer and the remote computer using `ssh`

![](https://github.com/LuffySaito/cse15l-lab-reports/blob/5956297647c4e1e12c18004d4ed38914bd02eb39/some_command.png)

## Moving Files with `scp` ##

- Run the command `scp` in the client to copy a file from your computer to the local computer

- In the terminal run the command `scp (file name) cs15lsp22zz@ieng6.ucsd.edu:~/`

- Then try logging in to the remote computer to see if the file successfully copied

![](https://github.com/LuffySaito/cse15l-lab-reports/blob/5956297647c4e1e12c18004d4ed38914bd02eb39/scp.png)

## Setting an SSH Key ##

- `

## Optimizing Remote Running ##

- 