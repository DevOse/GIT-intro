# Part 3: Git-Bash and the Command Line

In our last lesson, we created a folder for our project files, and installed GIT. We also talked about the importance of version control and collaboration when building large projects.

This section is an introduction to the command line (also known as the terminal). At the end of this section, you will will be comfortable using Git Bash, a special terminal for working with Git on Windows.

## What's the Command Line?
Modern operating systems have what we call a Graphical User Interface (GUI)... nice pretty icons and fonts that convey meaning and can respond when we 'click' or 'tap' on them. 

Years back (more like decades), computer programs weren't that fanciful. Running computer programs was mostly a text-based activity - you had to type a bunch of commands into a program called a shell/terminal/command line. This required a lot of memorization, and people who learnt these programs were considered 'professionals'. Graphical User Interface made computers more user-friendly, much easier to use.

Needless to say, most programs and software written today have a graphical interface. You can use these programs by clicking on icons and buttons, and they usually come with menus and windows for doing stuff. Microsoft Word, Photoshop and the Chrome browser are good examples.

Programs designed to run in a terminal are called command-line programs. You interact with these programs using commands. GIT is a command-line program, although some programs now offer GUI interfaces for performing GIT functions. This tutorial won't be teaching you how to use those - learning the command line will require a more intensive effort, but is ultimately more rewarding.

## Opening the Git-Bash Terminal
To start Git-Bash, perform the following actions  
 - Click the Windows or Start icon
 - In the Programs list, open the Git folder
 - Click the option for Git Bash.  
You can also type 'git bash' in the Start menu, and click to start the program.  

![Using GitBash](./screenshots/11-GitBash.png)  
*starting Git Bash...*
<pre>
</pre>

If you see the screen below, we good...  you've successfully launced the Git Bash Terminal

![GitBash](./screenshots/12-GitBashPrompt.png)  
<pre>
</pre>


## Working With The Terminal
A terminal (also called a shell) is a program that lets you work with command-line programs. Think of it as a mediator, or house boy, waiting for you to give a command to execute.

The Git Bash shell is a special terminal designed to work with Windows. Below is a short tutorial to get you started using it.

### Where are we?
 If you have Git Bash opened, you should see a dark, blank screen with a few characters at the top.  

 
![GitBash](./screenshots/12-GitBashPrompt.png)  
<pre>
</pre>
On the first line, you have  

`awaji@harmattanhunter MINIGW64 `

This would probably be different on your system. The first part (before the @) is the my username on my PC. The part after the @ is the name of my computer. It's not important you know what MINIGW64 means, so we can ignore that.

So, the first line follows this format  

`user@computerName MINIGW64`

Hopefully, yours follows this format.

On the second line, we have a single character.  

` $ `

This is called a prompt. It's where you enter/type the commands into the shell.

Enough long story, let's learn a few shell commands.



## Basic Shell Commands

### Knowing where you are
The first command we will be introduced to is **pwd**. **pwd** is short for *print working directory*. The "working directory" is the folder the shell is currently residing it.

When you start a shell, the program takes a folder on your hard disk, and makes it its working directory. It's similar to the 'project folder' in GIT, a point where all work takes place. 

To view your working directory, type *pwd* at the prompt and press **Enter**.  

![GitBash](./screenshots/13-PWD.png)  
<pre>
</pre>

When you press **Enter**, the command runs and prints a result on the next line. In my case, the shell printed

` /c/Users/awaji `

A simple interpretation of this result is that it shows my current location on the disk. The files on your hard disk are not scattered randomly; rather they are organized in various categories using folders or directories.

The output of the 'pwd' program says (reading from right to left) I'm in a folder called 'awaji', which is in a folder called 'Users', which is stored on my hard disk, the C drive.

This means any program or command I run will use this location as a sort of reference. Let's learn a few more commands to throw some light on this.

## The LS command
The LS command (or list) shows the content of the current working directory. Enter **ls** at the command prompt to try it.

![GitBash](./screenshots/14-List.png)  
<pre>
</pre>

The ls command lists all the files and folders in our working directory. In my screenshot, it displays the contents of the 'awaji' folder. 

What if we would like to change our working directory, sort of move around or navigate through the folders on our disk?

Well, there is a command for that too. It's called 'cd'

## The CD command
This command is also known as the 'change directory' command. You use it to navigate through your filesystem (hard disk). Let's try it.

In our last example, we ran the LS command. To navigate to the "documents' folder, type

` cd Documents `

[screenshot cd documents]

Type **ls** to view the contents of documents. Our Git-It folder should be displayed in the result.

[Git it display]

Exercise:
    Using what you have learnt, can you navigate to the Git-It folder?
    Confirm you are in the Git-It folder by running the *pwd* command.

Other info:
    To go to a parent folder, use the 'cd ..' command. The ".." refers to parent folder.

We now know enough about the command line to begin working with GIT. In the next lesson, we will initialize our GIT repo and begin to build our homepage.

<!-- 

## The CD Command (move to documents)

## the mkdir command (make directory)

## a brief on filepath

## further study on the command line

## Initializing our GIT repository

## the git init command

## working directory, repo, and index/staging area
## the git add command

## the git commit
    seeing others (ls) (command line and modifiers)
    looking around
    moving out
    moving up
    moving down

 -->
