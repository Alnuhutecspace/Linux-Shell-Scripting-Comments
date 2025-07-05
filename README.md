# Linux-Shell-Scripting-Comments 

In Linux shell scripting, comments are used to explain code, make it more readable, and prevent execution of specific lines of code. They are not executed by the shell. 

## Adding Comments in Bash Scripts 

Comments are essential in programming, serving as notes to the programmer and anyone else who might read the code. 

They explain what the script or ports of the script do, making the code easier to understand and maintain. 

Comments help you keep track of what your script is doing. They are useful because they allow you to leave internal notes throughout your script to remind you of things like what the next command will do or its expected output. You’re essentially annotating your scripts. 

## What Are Comments? 

Comments are lines in a script that are not executed by the shell. They are used to:

- Explain what the code does.

- Make the script easier to read and understand.

- Leave notes for yourself or others who read your code.

- Temporarily disable a line of code for testing/debugging. 

## Shell Scripts

A comment starts with the **#** symbol. 

- The shell ignores everything after # on the same line.

- Comments do not affect how the script runs.

## Single-Line Comments 

Single-line comments in Bash start with the # symbol. Anything following the symbol on the same line is treated as a comment and not executed. 

![Diectory and File Creation](./img/01.%20Directory%20and%20File%20Creation.png) 

![Scripting Code](./img/02.%20Script%20Code.png) 

![File Save](./img/03.%20Save%20File.png) 

The 'chmod' command was run to get execute permission for owner.

![Script Code Permission](./img/04.%20Script%20Code%20Permission.png)

![Script Run](./img/05.%20Script%20Run.png) 

## Using Multiple-Single-Line-Comments: 

Hello World Script with Multiple Comments. A file was created the code was scripted with multple line comments. 

![Open File](./img/06.%20Open%20File.png) 

![Multple Comment Script Code](./img/07.%20Multiple%20Comment%20Script%20Code.png) 

This approach is straight forward and it's commonly used for adding brief descriptions or notes spanning multple lines. 

## Best Practice for Commenting 

- Clarity: Write clear and concise comments that explain the "why" behind the code, not just the "what". 

- Maintainability: Keep comments updated as you modify the code to ensure they remain relevant and helpful. 

- Usefullness: Comment on complex or non-obvious parts of the script to provide insights into your thought process and decision-making. 

- Avoid Overcommenting: Don't comment on every line of code, especially if the code itself-explanatory. Focus on parts that benefits from additional explanation. 
