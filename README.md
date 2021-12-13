# 42-get_next_line
[![oabdalla's 42Project Score](https://badge42.herokuapp.com/api/project/oabdalla/get_next_line)](https://github.com/JaeSeoKim/badge42)

***Description:***

Get_next_line is used to collect line each line in a text file from multiple file descriptors. The size of the line and the buffer size used for read() is unknown. Get_next_line introduces the interesting new concept of static variables and their proper efficient usage.
- Calling your function get_next_line in a loop will then allow you to read the text available on the file descriptor one line at a time until the end of it.
- The function will return the line that has just been read. If there is nothing else to read or if an error has occurred it will return NULL.
- The program will compile with the flag -D BUFFER_SIZE=xx which will be used as the buffer size for the read calls in your get_next_line.

***Objectives:***
- Unix logic

***Skills:***
- Unix
- Rigor
- Algorithms & AI
