# Remote Access & FileSystem <br>
This week we covered three terminal commands<br>
`cd` , `ls` & `cat`<br>

## The `cd` command<br>
**Run with no arguments**<br>
![Image](cd1.png)<br>
*working directory was `home/lecture1/`*<br>
When run with no arguments `cd` changed the working directory to `home/`. It moves to the home directory regardless of the working directory<br>
This was not an error, although most programmers prefer using the command `cd ..` to move one directory backward <br>

**Run with directory as argument**<br>
![Image](cd2.png)<br>
*working directory was `home/`*<br>
When run with `lecture1` (a directory) as an argument, the `cd` command changed the working directory to `home/lecture1`.<br>
This was not an error.<br>

**Run with file as argument**<br>
![Image](cd3.png)<br>
*working directory was `home/lecture1`*<br>
When run with `Hello.java` as an argument, the `cd` command printed text explaining that `Hello.java` was not a directory.<br>
This is an error as the `cd` printed an error message and did not change the working directory.<br>

## The `ls` command<br>
**Run with no arguments**<br>
![Image](ls1.png)<br>
*working directory was `home/lecture1/`*<br>
When run with no argument the command printed text in the terminal of all of the file names in the working directory and printed other folders in blue.<br>
This is not an error.<br>

**Run with directory as argument**<br>
![Image](ls2.png)<br>
*working directory was `home/`<br>
When run with `lecture1` (a directory) as an argument, the `ls` command printed all of the file names within the directory `home/lecture1` and made all folders blue. <br>
This is not an error.<br>

**Run with file as argument**<br>
![Image](ls3.png)<br>
*working directory was `home/lecture1`*<br>
When run with `Hello.java` as an argument, the `ls` command printed `Hello.java` alone. However when run with the absolute path to `Hello.java` the command printed the path of the file.<br>
This is not an error.<br>

## The `cat` command<br>
**Run with no arguments**<br>
![Image](cat1.png)<br>
*working directory was `home/lecture1/`*<br>
When run with no argument the command waits for user input in the terminal, and then repeats the string given by the user. This continues until `cat` is deliberately stopped by using `cmd+d` or `ctrl+d`.<br>
This is not an error.<br>

**Run with directory as argument**<br>
![Image](cat2.png)<br>
*working directory was `home/`*<br>
When run with `lecture1` (a directory) as an argument, the `cat` command printed text explaining that `lecture1/` was a directory. <br>
This is an error as `cat` is used to read contents of files, however it can not for a directory .<br>

**Run with file as argument**<br>
![Image](cat3.png)<br>
*working directory was `home/lecture1/messages`*<br>
When run with `en-us.txt` as an argument, the `cat` command printed the contents of the `en-us.txt` file, which is "Hello World!".<br>
This is not an error.<br>
# Fin






