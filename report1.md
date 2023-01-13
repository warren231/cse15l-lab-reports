# How to log into a course-specific account on ieng6
## 1. If you don't know what your course-specific account even is, search it up [here](https://sdacs.ucsd.edu/~icc/index.php) by using your main UCSD account username and PID.
## 2. If there isn't a password set yet for the course-specific account, set it according to the instructions.
## 3. Open up a terminal such as the one found in VS Code.
## 4. If you want to use VS Code for the terminal and don't have it, download it from [here](https://code.visualstudio.com/)
- Personally I just used the lab computer's VS Code for this first lab but I previously installed it on my own computer.
![image](https://user-images.githubusercontent.com/110417554/211932381-3765cb3a-e859-438a-98fb-b0f873193de0.png)

## 5. Open the VS Code terminal. One way of finding it is using the Terminal part of the menu bar.

![image](https://user-images.githubusercontent.com/110417554/211931557-db7938aa-9a8d-40d7-80f7-1cab31fb465b.png)

## 6. Type `ssh [your username here]@ieng6.ucsd.edu` ex. `ssh cs15lwi23owo@ieng6.ucsd.edu`
- If this is your first time connecting to ieng6.ucsd.edu on the terminal you're using, type `yes` when prompted to continue connecting. You won't have to do this in the future if the host stays the same.

![image](https://user-images.githubusercontent.com/110417554/211932477-851f52ac-5ac9-4057-a433-2052d269be31.png)

## 7. Try commands such as:
`mkdir (directory name)` to make a new folder

`cp (origin) (destination)` to copy a file or folder to a destination.

`cd (directory path)` to change directory

`ls` to list the files in your working directory or `ls (directory)` to list the files in a specific directory.

`pwd` to print your current working directory

![image](https://user-images.githubusercontent.com/110417554/211932255-eb435874-c498-487a-84a6-53a5180d056e.png)

- Here, I made a directory named `Hi!` and tried to copy a file from the ieng6/cs15lwi23/public directory to my home directory but it didn't exist. Then, I listed what files were in that public directory.
