## Project description
The projects directory contains files and folders that require the file permissions to be updated. Right now, the permissions do not correspond to the appropriate level of authority. Their system will remain secure if these permissions are checked and updated. I completed the following tasks in order to finish this task:

### Check file and directory details 

The code that follows shows how I was able to find the current permissions assigned for a particular directory in the file system using Linux commands.

<img src="https://i.imgur.com/xoNnfMZ.png">

The command I typed is shown in the first line of the screenshot, and the output is shown in the remaining lines. The projects directory's contents are all listed in the code. I was able to see a comprehensive list of the file contents—which included hidden files—by using the ls program with the -la option. 

The company came to the conclusion that no one else should be able to write to any of their files. I used the file permissions that I had previously returned to comply with this. I found that the write access to project_k.txt needs to be deleted for other users.

<img src="https://i.imgur.com/yGLq8wP.png">

The commands I typed are shown in the first two lines of the screenshot, and the result of the second command is shown in the remaining lines. The permissions of files and directories can be modified with the chmod command. 

