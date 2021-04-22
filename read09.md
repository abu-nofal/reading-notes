#  What is a text editor?

A text editor is a piece of software that you download and install on your computer, or you access online through your web browser, that allows you to write and manage text, especially the text that you write to build a web site. 
The text editor has to be one of the most important tools you can use as an aspiring web developer.
What features should you look for in a text editor? I would say some of the most important features are: 

1.) code completion; 

2.) syntax highlighting; 

3.) a nice variety of themes (to reduce eye strain and
fatigue); 

4.) the ability to choose from a healthy selection of
extensions available when you need them. 

You might find some other features that are must-have’s, but I think these features are a good start.

A great feature of any text editing software is code completion.

Code completion allows you to start typing, and the code completion feature will display possible suggestions based on what you originally typed.

This saves you time by providing a choice, rather than allowing you to finish typing and possibly encounter typos.

Also, some code completion includes the closing of tags when you open them, or the closing of brackets when you open them, or the closing of quotation marks when you open them, thus making sure you’re always writing your code.

Another nice feature is being able to write your HTML and CSS more efficiently. 

There is a kind of shorthand language called Emmet that
can help. 
Emmet will speed up your code writing faster than you can
imagine. 

Some text editors come with Emmet built right in, or
Emmet can be added by the means of an extension.

Another feature you should definitely look into is called syntax highlighting. 

Syntax highlighting is a feature that takes the text you
type, and makes it more noticeable by colorizing the text. *Attributes* are a different color than elements. And elements are a different color than copy. 
This makes it so much easier when you’re looking for an
error and you can’t find it. 
As well as making your text easier to read.


## Party Options:

> NotePad++

NotePad++ is a free text editor for Windows Computers only.
NotePad++ has been around for many years and many web
developers swear by NotePad++. 
It has syntax highlighting and code completion, as well as word completion and function completion. 
It has a zoom in an out feature, it’s own online community, and its own chat room for questions that may arise. 
It even has its own searchable wiki page for more assistance

> Visual Studio Code

Visual Studio Code is a free text editor made by the folks at Microsoft.
It is available for Windows computers, Mac computers and Linux computers. 
VS Code has the Emmet shorthand for HTML and CSS already built-in with no additional work from you at all. 
VS Code has everything: syntax highlighting, themes, extensions and code completion. 
It seems like VS Code has a very healthy following in the
web developing community

> Atom

Atom is a free text editor that’s available for download for Windows computers, Mac computers and Linux computers. Atom is brought to you by the folks at GitHub . GitHub is a great service online where you can host and review code, or you can post and get help with the development of your own projects. 
Atom also ticks all the right boxes.
It has syntax highlighting, themes, extensions, the works! Atom is definitely a software to check out and test drive for yourself

> Brackets

Brackets is a free text editor that’s available for download for Windows computers, Mac computers and Linux computers. 
It’s made and maintained by the good folks at Adobe—yep, the Photoshop people. 
Brackets only supports HTML, CSS and JavaScript, though
more coding capabilities can be added through extensions. Being that Brackets only supports HTML, CSS and JavaScript, this might be a great choice to start with. But still the choice is yours.
Brackets includes all of the features one may want when using a text editor including something called “Live Preview” which updates your website once you make a change automatically. So, you can’t go wrong with Brackets.

> Sublime Text

Sublime Text 3 is a premium software that can be purchased in full for $70. Otherwise you’ll use the free version. Sublime Text enjoys a history of being fast and responsive while being extensible as well.
There’s no doubt that Sublime Text will tick the check boxes of what to look for in a text editor. It has syntax highlighting, 
it has code completion, it has themes and extensions. And will definitely get the job done no matter how advanced you get with your coding.



# The Command Line!

The command line is an interesting beast, and if you've not used one before, can be a bit daunting. Don't worry, with a bit of practice you'll soon come to see it as your friend. Don't think of it as leaving the GUI behind so much as adding to it. While you can leave the GUI alltogether, most people open up a command line interface just as another window on their desktop (in fact you can have as many open as you like). This is also to our advantage as we can have several command lines open and doing different tasks in each at the same time. We can also easily jump back to the GUI when it suits us. Experiment until you find the setup that suits you best. As an example I will typically have 3 terminals open: 1 in which I do my working, another to bring up ancilliary data and a final one for viewing Manual pages (more on these later).

>  So what are they exactly?

A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

>  The Shell, Bash

Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell. This tutorial will assume you are using bash as your shell.

If you would like to know which shell you are using you may use a command called echo to display a system variable stating your current shell. echo is a command which is used to display messages.

>  Shortcuts

The terminal may seem daunting but don't fret. Linux is full of shortcuts to help make your life easier. You'll be introduced to several of them throughout this tutorial. Take note of them as not only do they make your life easier, they often also save you from making silly mistakes such as typos.

## Basic Navigation!

> So where are we?

The first command we are going to learn is pwd which stands for Print Working Directory. (You'll find that a lot of commands in linux are named as an abbreviation of a word or words describing them. This makes it easier to remember them.) The command does just that. It tells you what your current or present working directory is. 

>  What's in Our Current Location?

It's one thing to know where we are. Next we'll want to know what is there. The command for this task is ls. It's short for list.

> Paths

n the previous commands we started touching on something called a path. I would like to go into more detail on them now as they are important in being proficient with Linux. Whenever we refer to either a file or directory on the command line, we are in fact referring to a path. ie. A path is a means to get to a particular file or directory on the system.

There are 2 types of paths we can use, absolute and relative. Whenever we refer to a file or directory we are using one of these paths. Whenever we refer to a file or directory, we can, in fact, use either type of path (either way, the system will still be directed to the same location).

To begin with, we have to understand that the file system under linux is a hierarchical structure. At the very top of the structure is what's called the root directory. It is denoted by a single slash ( / ). It has subdirectories, they have subdirectories and so on. Files may reside in any of these directories.

> Let's Move Around a Bit

In order to move around in the system we use a command called cd which stands for change directory. 

The command cd may be run without a location as we saw in the shortcut above but usually will be run with a single command line argument which is the location we would like to change into. The location is specified as a path and as such may be specified as either an absolute or relative path and using any of the path building blocks mentioned above.

>  Spaces in names 

Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items. They are how we know what is the program name and can identify each command line argument.

What happens is that Holiday Photos is seen as two command line arguments. cd moves into whichever directory is specified by the first command line argument only. To get around this we need to identify to the terminal that we wish Holiday Photos to be seen as a single command line argument. There are two ways to go about this, either way is just as valid.

>  Quotes

The first approach involves using quotes around the entire item. You may use either single or double quotes (later on we will see that there is a subtle difference between the two but for now that difference is not a problem). Anything inside quotes is considered a single item.

> Escape Characters

Another method is to use what is called an escape character, which is a backslash ( \ ). What the backslash does is escape (or nullify) the special meaning of the next character.

>  Hidden Files and Directories 

Linux actually has a very simple and elegant mechanism for specifying that a file or directory is hidden. If the file or directory's name begins with a . (full stop) then it is considered to be hidden. You don't even need a special command or action to make a file hidden. Files and directories may be hidden for a variety of reasons. Configuration files for a particular user (which are normally stored in their home directory) are hidden for instance so that they don't get in the way of the user doing their everyday tasks.

To make a file or directory hidden all you need to do is create the file or directory with it's name beginning with a . or rename it to be as such. Likewise you may rename a hidden file to remove the . and it will become unhidden. The command ls which we have seen in the previous section will not list hidden files and directories by default. We may modify it by including the command line option -a so that it does show hidden files and directories.

[refrance](https://ryanstutorials.net/linuxtutorial/commandline.php)



