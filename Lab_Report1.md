# Lab Report 1
### cd with no argument:
![Image](CD_No_Args.png)

The current directory was the home directory. 
When cd is called without any arguments the user is returned to the home directory, however we were already in the home directory, so it didn’t do anything. 
This output was not an error since it technically changed the directory to the home directory. 

### cd with a path to a directory:
![Image](CD_Directory.png)

The current directory was the home directory.
I got that output because in changed the directory to lecture1 and so in the next line the directory i was in was the lecture1 directory.
This was not an error.

### cd with a path to a file:
![Image](CD_File.png)

The current directory was the lecture1 directory.
I got this output because Hello.java was not a directory. 
This is an error since cd didn’t change the directory and instead it returned that Hello.java is not a directory. 

### ls with no argument:
![Image](LS_No_Args.png)

The current directory was the home directory.
I got this output because lecture1 is the file under the home directory. 
This is not an error.

### ls with a path to a directory:
![Image](LS_Directory.png)

The current directory was the home directory.
I got this output because these were the files under the lecture1 directory.
This is not an error.

### ls with a path to a file:
![Image](LS_File.png)

The current directory was the lecture1 directory.
I got this output because Hello.java was the only file in Hello.java.
This is not an error.

### cat with no argument:
![Image](CAT_No_Args.png)

The current directory was the home directory.
I got no output at first, but once I typed “asdfjkl” and pressed “enter” it repeated what I typed. When cat is run without arguments, it just reads from stdin.
This is not an error.

### cat with a path to a directory:
![Image](CAT_Directory.png)

The current directory was the home directory.
The output I got was that lecture1 was a directory. I’m guessing this is because it cannot read the input as a directory.
This is an error since it didn’t read the content in lecture1 and output it.

### cat with a path to a file:
![Image](CAT_File.png)

The current directory was the lecture1 directory.
The output I got the contents of the Hello.java file.
This is not an error.
