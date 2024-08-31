# How to Create a File Using Terminal

**Terminal** is an app for advanced users and developers that lets you communicate with the Mac operating system using a command line interface (CLI). [Apple definiition](https://support.apple.com/guide/terminal/what-is-terminal-trmld4c92d55/mac)

The **command line interface** is a method of entering textual commands into the shell.

The **shell** is a command line interpreter that processes commands.

![Computer with terminal window open](https://images.unsplash.com/photo-1493020258366-be3ead1b3027?q=80&w=1480&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

## Open Terminal on your Mac

1. Open ___finder___ and search for `terminal`
1. Open the *terminal* app
1. Type in `pwd` to determine that you are in the correct user folder. (pwd stands for *print working directory*).

### Example

> [-> ~ pwd
>>/Users/valeriehavey

Next, type in `ls`

`ls` stands for "list directories"

Here, you will see a list of directors that might include:

* Desktop
* Downloads
* Movies
* Pictures
* Documents
* Library
* Music
* Public
* code

To ***change directories*** into the `code` directory, type in `cd code`

In this example, we are changing directories into the **code** directory. You can cd into any of your listed directories.

>Tip: If you want to see the directories within the **code** directory, type in, `ls`

Continue to `cd` into the final directory in which you want to create a new file. In this example, we want to reach the `intro-to-markdown-lab` directory:

>cd code
>>cd ga
>>>cd labs
>>>>cd intro-to-markdown-lab

Here, in the ***intro-to-markdown-lab*** we want to create a new file.

Next, type in `touch` and then the name of your new file:

`touch index.html`

Viola! You have created a new file using Terminal.

You did it! 👏


