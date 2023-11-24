# Redhat-LINUX-
![1](https://www.redhat.com/themes/custom/rhdc/img/red-hat-social-share.jpg)
<html></br></html>

1. Using vi write your CV in the file mycv. Your CV should include your name, age, school,
college, experience,...
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab3/lab3_q1.png?raw=true)

2. Open mycv file using vi command then: Without using arrows state how to:
a. Move the cursor down one line at time.
<html></br></html>
press j
<html></br></html>
b. Move the cursor up one line at time.
<html></br></html>
Press k
<html></br></html>
c. Search for word age
<html></br></html>
type /age and press Enter
d. Step to line 5 (assuming that you are in line 1 and file is more than 5 lines).
<html></br></html>
type :5 and press Enter
<html></br></html>
e. Delete the line you are on and line 5.
<html></br></html>
type dd to delete the line i am in ,type :5dd to delete line 5
<html></br></html>
f. How to step to the end of line and change to writing mode in one-step.
<html></br></html>
press $ ,press a to enter insert mode.
<html></br></html>


3. List the available shells in your system.
<html></br></html>

![1]( https://github.com/NooranTarek/RedhatLinux/blob/main/lab3/lab3_q3.png?raw=true)

4.List the environment variables in your current shell.
<html></br></html>

![1]( https://github.com/NooranTarek/RedhatLinux/blob/main/lab3/lab3_q4.1.png?raw=true)
<html></br></html>

![1](  https://github.com/NooranTarek/RedhatLinux/blob/main/lab3/lab3_q4.2.png?raw=true)

5.List all of the environment variables for the bash shell.
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab3/lab3_q5.png?raw=true)

6. What are the commands that list the value of a specific variable?
<html></br></html>

![1]( https://github.com/NooranTarek/RedhatLinux/blob/main/lab3/lab3_q6.png?raw=true)


7. Display your current shell name.
<html></br></html>

![1](  https://github.com/NooranTarek/RedhatLinux/blob/main/lab3/lab3_q7.png?raw=true)


8.State the initialization files of: sh, ksh, bash.
<html></br></html>

    sh (Bourne Shell):
        The Bourne Shell (sh) typically reads the system-wide profile file, such as /etc/profile. Additionally, it may read a user's personal initialization file, such as ~/.profile.

    ksh (Korn Shell):
        The Korn Shell (ksh) can read system-wide files like /etc/profile. For individual users, it may read ~/.profile or ~/.kshrc.

    bash (Bourne Again Shell):
        The Bash Shell (bash) reads different files depending on whether it is invoked as a login shell or a non-login shell.
            Login Shell:
                /etc/profile: System-wide initialization file.
                /etc/bashrc: System-wide resource file for non-login shells.
                ~/.bash_profile: User-specific login configuration.
                ~/.bash_login: Used if ~/.bash_profile doesn't exist.
                ~/.profile: Used if neither ~/.bash_profile nor ~/.bash_login exists.
            Non-login Shell:
                /etc/bashrc: System-wide resource file.
                ~/.bashrc: User-specific configuration.


9. Edit in your profile to display date at login and change your prompt permanently.
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab3/lab3_q9.png?raw=true)

<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab3/lab3_q91.png?raw=true).

<html></br></html>

10.Execute the following command :
echo \ then press enter
What is the purpose of \ ?
Notice the prompt ”>” what is that? and how can you change it from “>” to “:”.
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab3/lab3_q10.2.png?raw=true)

<html></br></html>

the shell is expecting more input to complete the command because the previous line ended with a backslash (\)
(>) is indicating that the command is not yet complete. The shell is waiting for you to provide additional 
input to finish the command.If you want to change from > to :,use the PS2 variable.

 <html></br></html>

11.Create a Bash shell alias named ls for the “ls –l” command
<html></br></html>

![1]( https://github.com/NooranTarek/RedhatLinux/blob/main/lab3/lab3_q11.png?raw=true)

