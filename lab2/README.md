# Redhat-LINUX-
![1](https://www.redhat.com/themes/custom/rhdc/img/red-hat-social-share.jpg)
<html></br></html>
1. Create a user account with the following attribute
username: islam
Fullname/comment: Islam Askar
Password: islam

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q1.png?raw=true)
<html></br></html>
2. Create a user account with the following attribute
Username: baduser
Full name/comment: Bad User
Password: baduser

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q2.png?raw=true)
<html></br></html>
3. Create a supplementary (Secondary) group called pgroup with group ID of 30000
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q3.png?raw=true)
4. Create a supplementary group called badgroup
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q4.png?raw=true)

5. Add islam user to the pgroup group as a supplementary group
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q5.png?raw=true)

6. Modify the password of islam's account to password
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q6.png?raw=true)

7. Modify islam's account so the password expires after 30 days
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q7.png?raw=true)

8. Lock bad user account so he can't log in
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q8.png?raw=true)

9. Delete bad user account
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q9.png?raw=true)

10. Delete the supplementary group called badgroup.
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q10.png?raw=true)

13. Create a folder called myteam in your home directory and change its permissions to
read only for the owner.
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q13.png?raw=true)

14. Log out and log in by another user
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q14.png?raw=true)

15. Try to access (by cd command) the folder (myteam)
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q15.png?raw=true)

16. Using the command Line
 Change the permissions of oldpasswd file to give owner read and write
permissions and for group write and execute and execute only for the others
(using chmod in 2 different ways)
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q16.a.png?raw=true)

 Change your default permissions to be as above.
![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q16.b.png?raw=true)


 What is the maximum permission a file can have, by default when it is just
created? And what is that for directory.
<html></br></html>

when a file is just created it has permissions of 666 (read and write for owner, group,
and others). For directories, the default is usually 777 (read, write, and execute
for owner, group, and others).


 Change your default permissions to be no permission to everyone then create a
directory and a file to verify.

<html></br></html>


18. What are the minimum permission needed for:
 Copy a directory (permission for source directory and permissions for target
parent directory)
<html></br></html>


 Copy a file (permission for source file and and permission for target parent
directory)
<html></br></html>
source         --x
<html></br></html>
distination    -wx

 Delete a file
<html></br></html>
delete         ---
<html></br></html>

 Change to a directory
<html></br></html>


 List a directory content (ls command)
<html></br></html>

 View a file content (more/cat command)
<html></br></html>

 Modify a file content
<html></br></html>

19. Create a file with permission 444. Try to edit in it and to remove it? Note what
happened.
<html></br></html>

![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q18.1.png?raw=true)
![1](https://github.com/NooranTarek/RedhatLinux/blob/main/lab2/lab2_q18.2.png?raw=true)



21. What is the difference between the “x” permission for a file and for a
directory?
<html></br></html>

For regular files the "x" permission allows the file to be executed as a program. If a user has execute permission on a file, they can run the file as a command.
For directories, the "x" permission has a different meaning. If a user has execute permission on a directory, it allows them to traverse (cd) into the directory and access its contents.
