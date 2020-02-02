# Usage of Vi

This section explains the usage of Vi with some examples shown in the figures. These commands can be useful to manage the file system.

## cd  
This will allow user to **change the directory**. Instead of, moving and clicking around different folders, this is very convenient approach to change directory. As shown below, the user initially was on home directory, but then he navigated to Desktop using `cd ` command.

![cd Example](/images/cd.PNG)

## mkdir
This command is also very useful and it allows users to **create a new directory**. As shown below, user created new directory for videos within MiniProject1 folder. With `mkdir`command, it becomes very convenient to make new directories as needed.

![mkdir Example](/images/mkdir.PNG)

## cp
**Copying files** can be done using `cp` command. It copies the contents listed from file#1 to file#2. As shown in the example below, user is trying to copy README.md file and place it under videos folder with name of COPY_README.md. This single line command can reduce time and allows users to copy files instantly.

![cp Example](/images/cp.PNG)

## pwd
This command **prints out the present working directory** to user. If the user is not sure about the location, then this ‘pwd’ command comes in very handy. As shown below, the user performed pwd command and it provided working directory as following: `/C/Users/bhaga/Desktop/WebSystems/MiniProject1`

![pwd Example](/images/pwd.PNG)

## mv
This command comes in the very handy if user wants to **rename a file** or **move files around to different directories**. As shown in the example, user is moving COPY_README.md file from videos folder to MiniProject1 folder. 

![mv Example](/images/mv.PNG)

## rm
**To remove specific files in directory**, user needs to use `rm` command. In addition, if user opts to **remove a directory**, then `rmdir` can also be used. As shown below, first, user removed COPY_README.md file from MiniProject1 folder. When user tried to delete videos folder, it prompted an error as it is a directory. These commands are very easy to utilize during software development process. 

![rm Example](/images/rm.PNG)

## history 
This command will **print out previously executed commands**. This can also be very useful to keep track of all executed commands. As shown below, this examples shows different commands that user executed while working on this assignment. In addition, by using up and down arrow, user can navigate through these commands on terminal window as well. 

![history Example](/images/history.PNG)

These commands shown in the examples above are very helpful to **manage the file system** during software development lifecycle. User can **perform any tasks** from terminal window, instead of clicking and going around different folders. It can definitely **speed up the process**. The sign of `~`, represents home directory and user can easily navigate there by using change of directory command. Moreover, user can also utilize **tab key** to complete file paths **to avoid any repetitive typing**. When the user prints out first few characters of the name of the file, and then press Tab key, then it will complete the name for you.