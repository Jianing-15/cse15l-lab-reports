
![s1](screenshot1.png)
This is the screen where I open Visual Studio Code and I can use the keys on the left to create a file or open an already existing file. I can also use the keyboard input shortcuts in this screen to create new files or terminals. But here I used the above program dock to create the new terminal.
![s2](screenshot.png)
After creating a new terminal, follow the lab instruction and use the ssh command to get the terminal to connect to another computer to run the command and after entering your account you will be asked to enter your password. After entering the password a message will appear that the previous login or login failed, then the login place will be displayed along with some system information.
![s3](screenshot2.png)
Once I had successfully logged into my account I proceeded to the next step. Then i logged in to the account I used the command to test, I used the command ls -lat and ls -a, Enter two commands separately, press return on the keyboard after entering the command to run the command, then the computer will return some data according to the command. After getting the return value, I proceeded to the next step.

![s4](screenshot3.png）
![s5](screenshot4.png)
![s6](screenshot5.png)
![s7](sreenshot6.png)
Then enter javac and java to compile and call the existing java program, and after a successful run the Java program returns the name of the current user, the user name and the location of the current file. Then use exit to exit the login, after successfully logging out will return logout and connection interruption prompt, then use scp to copy the target file and add their account name, then the system will again ask for a password, after entering the password the system prompted no such file, so after this tried pwd and cd command to determine their location, after adjusting to the correct location I tried the scp command again, after entering the password again the system returned the download success information, including, file name, network speed, and time. After successfully copying the file, try to set up a password-free login, use the ssh-keygen command, follow the lab instructions to do so, and enter continuously to eliminate the password. After success, get the returned message, then try again to log in, use the scp command, randomly notify the system to enter the password, try to enter, successfully log in, and return the correct message, proving that the password change was successful. Then run the hint locally and get the return data as local computer information. use $ ssh cs15lfa22@ieng6.ucsd.edu "ls".
