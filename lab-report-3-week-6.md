# **Lab Report 3 - Week 6**

## **Streamlining `ssh` Configuration**

How I created and edited the `.ssh/config` file:

![.ssh/config](Lab5sshconfig.png)

Contents of `.ssh/config`:

![ssh/configcontents](sshconfigcontents.png)

`ssh` command logging into account using alias:

![sshieng6](ssh%20ieng6.png)

`scp` using an alias:

![scpusingalias](scpusingalias.png)

## **Setup Github Access from ieng6**

Public key stored on Github:

![KeyOnGitHub](KeyOnGitHubAcc.png)

Public key you stored in your user account:

![KeyOnUser](KeyOnUserAcc.png)

Private key on user account:

![PrivKeyOnUser](PrivKeyOnUser.png)

Running `git` commands to commit and push a change to Github while logged into ieng6 account:

![GitCommandsOnieng6](GitCommandsOnieng6.png)

Link for resulting commit:

[LinkForCommit](https://github.com/sanjithdevineni/markdown-parser/commit/e71ad887ff60f771de1c331d7c1023d6305e0d24)

## **Copy whole directories with `scp -r`**

Copying whole markdown-parse directory to ieng6 account:

![SCPDirToRemote1](SCPDirToRemote1.png)

![SCPDirToRemote2](SCPDirToRemote2.png)

![SCPDirToRemote3](SCPDirToRemote3.png)

![SCPDirToRemote4](SCPDirToRemote4.png)

Logging into ieng6 account and compiling and running the tests for repository:

![RunningTestsOnRemote](RunningTestsOnRemote.png)

Combining `scp`, `;`, and `ssh` to copy the whole directory and run the tests in one line:

![MultipleCommandsToRemote1](MultipleCommandsToRemote1.png)

![MultipleCommandsToRemote2](MultipleCommandsToRemote2.png)

![MultipleCommandsToRemote3](MultipleCommandsToRemote3.png)

![MultipleCommandsToRemote4](MultipleCommandsToRemote4.png)