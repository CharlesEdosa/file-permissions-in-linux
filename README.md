## Project description
The projects directory contains files and folders that require the file permissions to be updated. Right now, the permissions do not correspond to the appropriate level of authority. Their system will remain secure if these permissions are checked and updated. I completed the following tasks in order to finish this task:

### Check file and directory details 

The code that follows shows how I was able to find the current permissions assigned for a particular directory in the file system using Linux commands.

<img src="https://i.imgur.com/xoNnfMZ.png">

The command I typed is shown in the first line of the screenshot, and the output is shown in the remaining lines. The projects directory's contents are all listed in the code. I was able to see a comprehensive list of the file contents—which included hidden files—by using the ls program with the -la option. 

### Change file permission

The company came to the conclusion that no one else should be able to write to any of their files. I used the file permissions that I had previously returned to comply with this. I found that the write access to project_k.txt needs to be deleted for other users.

<img src="https://i.imgur.com/yGLq8wP.png">

The commands I typed are shown in the first two lines of the screenshot, and the result of the second command is shown in the remaining lines. The permissions of files and directories can be modified with the chmod command. 

### Change file permission on a hidden file

The following code demonstrates how i used the linux commands to change the permission of the achived project_x.txt. i removed the write access to this project but the user and group continues to have read access

<img src="https://i.imgur.com/zM6Qy8l.png">

The commands I typed are shown in the first two lines of the screenshot, and the result of the second command is shown in the remaining lines. Since project_x.txt begins with a period (. ), it is a hidden file. I gave the group read permissions and took away the user's and group's write capabilities. I took away the user's u-w write permissions. Next, I gave the group with g+r read capabilities and withdrew write permissions from it. 

### Change directory permission

The following code demonstrates how I used Linux commands to change the permissions. Only research2 user was granted access to the "drafts directory" 

<img src="https://i.imgur.com/viJTnSC.png">

The commands I typed are shown in the first two lines of the screenshot, and the result of the second command is shown in the remaining lines. I used the chmod command to remove the group's execute permissions after discovering earlier that they were there. It was not necessary to add execute rights because the researcher2 user already has them.

### Summary

To summarise, I made numerous changes to permissions to files and directories in the "projects directory" according to the amount of access that was required. Checking the directory's permissions with ls -la was the initial step in this process. This helped me make decisions about what to do next. I then changed the permissions of files and directories several times using the chmod command.
