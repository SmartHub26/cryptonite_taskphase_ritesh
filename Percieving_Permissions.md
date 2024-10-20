# Linux Luminarium
## Perceiving Permissions

### Question 1

![Image Error](./images/Perceiving_Permissions/q11.png)
![Image Error](./images/Perceiving_Permissions/q12.png)

Solution:

![Image Error](./images/Perceiving_Permissions/s1.png)

### Question 2

![Image Error](./images/Perceiving_Permissions/q21.png)
![Image Error](./images/Perceiving_Permissions/q22.png)

Solution:
`chgrp hacker flag`

this helped me to change the current user from root to hacker after which i was able to read the file.

![Image Error](./images/Perceiving_Permissions/s2.png)

### Question 3

![Image Error](./images/Perceiving_Permissions/q3.png)


Solution:

For this problem, I ran through all the usernames hand the username grp12013 worked and enabled me to cat the /flag.

![Image Error](./images/Perceiving_Permissions/s3.png)

### Question 4

![Image Error](./images/Perceiving_Permissions/q41.png)
![Image Error](./images/Perceiving_Permissions/q42.png)
![Image Error](./images/Perceiving_Permissions/q43.png)
![Image Error](./images/Perceiving_Permissions/q44.png)

Solution:

`chmod o+r /flag`

The above command helped me to make it readable for all the users without changinh the current user who owned the file.

![Image Error](./images/Perceiving_Permissions/s4.png)

### Question 5

![Image Error](./images/Perceiving_Permissions/q5.png)


Solution:

`chmod u+x /flag`

The above command helped me to make the file /flag executable for the current user who is the owner of the file. This helped me execute the cmd /challenge/run and I was able to read the flag.

![Image Error](./images/Perceiving_Permissions/s5.png)

### Question 6

![Image Error](./images/Perceiving_Permissions/q6.png)


Solution:

After solving the 8 rounds continuously and correctly , the owner of the file /flag is changed. 
So, I changed the the permissions of the file as read all in order to read the flag.

![Image Error](./images/Perceiving_Permissions/s6.png)

### Question 7

![Image Error](./images/Perceiving_Permissions/q7.png)


Solution:

After rigorously setting different permissions for /challenge/pwn , I make the /flag file readable and get  the flag.

![Image Error](./images/Perceiving_Permissions/s7.png)

### Question 8

![Image Error](./images/Perceiving_Permissions/q8.png)

Solution:

I allowed to user to execute the file but with SUID permission. This was the only task here that let me read the flag.

![Image Error](./images/Perceiving_Permissions/s8.png)

