# **Lab Report 3 - Week 6**

## **Streamlining ssh Configuration**

![](config_file.png)

Using VScode, I created a config file under `.ssh` directory.

![](ssh_alias.png)

Now, I am able to access the server using the alias `ieng6`

![](scp_alias.png)

Similarly, I can `scp` using the same alias, and I checked whether if the file copied successfully.

## **Setup Github Access from ieng6**

Public key stored on Github:
![](public_key_github.png)

Public key stored on user account:
![](public_key_user.png)

Private key store on user account:
![](private_key.png)


![](git_push.png)
Using the command `git push origin main` a new file HelloWorld.txt was successfully pushed to the main repository

Resulting Commit: [https://github.com/LuffySaito/cse15l-lab-reports/commit/2a93e46f380ff13cfa8d8d697ca47f1b53989f7f](https://github.com/LuffySaito/cse15l-lab-reports/commit/2a93e46f380ff13cfa8d8d697ca47f1b53989f7f)

## **Copy whole directories with `scp -r`**



