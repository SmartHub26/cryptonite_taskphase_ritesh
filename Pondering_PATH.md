# LINUX LUMINARIUM
## Pondering PATH

### Question 1

![Image Error](./images/Pondering_PATH/q1.png)

Solution:

`PATH=''` removes all cmds and files from the terminal and only `/challenge/run` can be executed. This gets me the flag

![Image Error](./images/Pondering_PATH/s1.png)

### Question 2

![Image Error](./images/Pondering_PATH/q2.png)

Solution:

PATH is set to the given address after which `/challenge/run` is executed after which the flag is displayed.
![Image Error](./images/Pondering_PATH/s2.png)

### Question 3

![Image Error](./images/Pondering_PATH/q3.png)

Solution:

Firstly, win file is created using `touch` .

`nano win` it is cmd which helps in editing the text in the file win. It is not mentioned in any of the modules.

`chmod a+x win` allows all to execute win.

PATH is set to the current workking directory and `/challenge/run ` is executed.This gives us the flag.


![Image Error](./images/Pondering_PATH/s3.png)

### Question 4

![Image Error](./images/Pondering_PATH/q4.png)

Solution:

The solution is similar to the previous problem.
Just like creating file win, I created a file rm here and followed the same steps as the last problem.

![Image Error](./images/Pondering_PATH/s4.png)

