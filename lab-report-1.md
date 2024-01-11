#Remote Access & FileSystem
This week we covered three terminal commands
`cd` , `ls` & `cat`

##The `cd` command
**Run with no arguments**
![Image](cd1.png)
*working directory was `home/lecture1/`*
When run with no arguments `cd` changed the working directory to `home/`. It moved one level outside the previous working directory
This was not an error, although most programmers prefer using the command `cd..` for the same result

**Run with directory as argument**
![Image](cd2.png)
*working directory was `home/`
When run with `lecture1` (a directory) as an argument, the `cd` command changed the working directory to `home/lecture1`.
This was not an error.

**Run with file as argument**
![Image](cd3.png)
*working directory was `home/lecture1`*
When run with `Hello.java` as an argument, the `cd` command printed text explaining that `Hello.java` was not a directory.
This is an error as the `cd` printed an error message and did not change the working directory.

##The `ls` command
**Run with no arguments**
![Image](ls1.png)
*working directory was `home/lecture1/`*
When run with no argument the command printed text in the terminal of all of the file names in the directory and printed other folders in blue.

