## Step 4
Keys pressed: `<ctrl+v> <enter>` I copied my ssh login command `ssh cs15lfa23ry@ieng6.ucsd.edu` from my notes onto the terminal

## Step 5
Keys pressed: `git clone <ctrl+v> <enter>` I typed the git clone command and then pasted the lab7 `git@github.com:etw002/lab7.git` ssh url that I forked from lab 7.

## Step 6
Keys pressed: `cd lab7/ <enter>`, `ls <enter>`,`<ctrl+v> <enter>`,`<ctrl+v> <enter>` I went into the lab7 directory and listed the directories. Then I copy pasted the javac command from my notes `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` to compile the files. Then I ran the files by copy pasting and running `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests`

## Step 7
Keys pressed: `vim <shift+l> <tab> . <tab> <enter>`,`44j`,`k`,`e`,`x`,`i`,`2`,`<esc>`,`<shift+;>wq <enter>` I opened ListExamples.java using vim, then move to the line 44 by using `44j` because I saw that the error was on line 44. Then I moved up by one line using `k` and to the back of the first letter using `e`. I deleted the 1 with `x` and inserted a 2 with `i2`. I exited insert mode with `<esc>` and wrote the change and exited the file with `<shift+;>wq <enter>`. 

## Step 8
Keys pressed: `<up><up><up><enter>`, `<up><up><up><enter>` Since I already ran the compile and run commands 3 commands ago, I used `<up>` to access them.

## Step 9 
Keys pressed: `git add ListExamples.java <enter>`, `git commit -m "updated ListExamples.java" <enter>`,`git branch <enter>`,`git push origin main <enter` I typed out `git add ListExamples.java <enter>` to first stage the change for the commit. Then I typed out `git commit -m "updated ListExamples.java" <enter>` to commit the change with the commit message `"updated ListExamples.java"`. After that, I checked what the branch was with the command `git branch` and I saw that it was under `main`, so I used the command `git push origin main <enter` to push the changes onto main. 
