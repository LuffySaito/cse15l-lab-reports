# **Lab Report 3 - Week 6**

## **Streamlining ssh Configuration**

Using VScode, I created a config file under `.ssh` directory.

![](config_file.png)

Now, I am able to access the server using the alias `ieng6`

![](ssh_alias.png)

Similarly, I can `scp` using the same alias, and I checked whether if the file copied successfully.

![](scp_alias.png)

## **Setup Github Access from ieng6**

Public key stored on Github:
![](public_key_github.png)

Public key stored on user account:
![](public_key_user.png)

Private key stored on user account:
![](private_key.png)

Using the command `git push origin main` a new file HelloWorld.txt was successfully pushed to the main repository

![](git_push.png)

Resulting Commit: [https://github.com/LuffySaito/cse15l-lab-reports/commit/2a93e46f380ff13cfa8d8d697ca47f1b53989f7f](https://github.com/LuffySaito/cse15l-lab-reports/commit/2a93e46f380ff13cfa8d8d697ca47f1b53989f7f)

## **Copy whole directories with `scp -r`**

Successfully copied the directory markdown-parse onto the server using `scp -r`

![](scp_markdownparse.png)

Test successfully runs on the server.

![](run_markdown.png)

Combining `scp`, `ssh`, and the run commmands, I am able to copy the directory, log in to the server, and run the test on the server in one line.

![](multiple_commands.png)