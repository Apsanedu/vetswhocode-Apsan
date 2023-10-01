# Research on the History of the Command Line Interface (CLI)

## Introduction

Until the 1960s, computers primarily used mechanical punch cards as the main medium for input of both computer programs and data. Manual punching of cards required a trained individual to operate the system. Due to these limitations, only primitive languages like Assembly code, COBOL, and FORTRAN were available.

The shift happened when engineers figured out how to use magnetic tape for storage, alongside a display and keyboard, bringing in a new era of computing. "By the early 1960s, engineers had attached a Cathode Ray Tube (CRT) monitor to the TeleTYpewriter (TTY) machine." (Montagnino, Part-1) This combination of keyboard and monitor marked the beginning of modern-day computers. "Users would type a command, hit the Enter key, and the computer would respond. These were called command-line interfaces!" (Montagnino, Part-1).

In the 1970s, early versions of Graphical User Interfaces (GUIs) were invented. The invention of the computer mouse further revolutionized computing, leading to the development of personal computers and operating systems accessible to the general public, ultimately revolutionizing modern life.

## Notable Figures

### Ken Thompson and Dennis Ritchie
- Founders of Unix, which laid the foundation for the modern CLI. They developed the Unix operating system at Bell Labs, featuring the command-line interface as a central component.

### Richard Stallman
- Founder of the Free Software Foundation (FSF) and the GNU Project, aiming to create a free Unix-like operating system. The GNU tools, including the GNU Compiler Collection (GCC) and bash shell, are critical components of the modern CLI. Today Linux is actually GNU/ Linux because it relies on GNU tools.

### Stephen R. Bourne
- Developed the Bourne shell (sh), one of the earliest Unix shells, which served as the basis for subsequent shells and greatly influenced the evolution of CLI.

### Linus Torvalds
- Creator of the Linux kernel, which, when combined with GNU tools and utilities, resulted in the popular Linux operating system, utilizing the CLI extensively.

## Terminal vs. Shell

### Terminal or Terminal Emulator
- The application or program where you enter commands. Terminals like Terminal (Mac), Windows Command Prompt, Alacritty, st, etc., are common terminals.

### Shell
- The shell is the language that your terminal uses. (Use the command `echo $0` to see your shell language). Today, Bash (and other shells like bash), Windows Command prompt, and Powershell are the most popular shells. Zsh, based on Bash, is the most popular among programmers.

Today, the majority of users rely on graphical programs to perform tasks. However, there's also an active and vibrant community of CLI program users. Ranger is a popular file manager, Vim and Emacs for text editing, brew, chocolatey, apt, pacman for package management, ffmpeg for editing and converting video files, cmus for music player, tmux for a terminal server, Zathura for an ebook viewer, and many more.


## Bash Commands

Bash (Bourne Again Shell) comes with some basic commands to interact with your computer. You can view and move between directories (cd, ls, mv, cp, rm, mkdir), create, view, and edit text files (touch, cat, less, more), and compile/source config files (for example, source ~/.zshrc).



## Advantages of CLI over GUI

- CLI offers faster performance. CLI programs do not have to render large graphical elements.
- You can use command arguments to specify the options you need rather than clicking on GUI buttons to find what you need.
- CLI programs follow the UNIX philosophy of modularity, i.e., a program should be designed to do one specific task and should communicate with other programs. This is an important distinction that makes CLI pleasant, efficient, and much better than GUI.
- Automation with scripts. Since most of your work is just a set of commands, you can create a shell script and run it with a simple alias. No matter the size of the task, if you can write a script for it, it will run. You can also copy scripts from the Internet and use them for your work.

## Works Cited

Montagnino, Marian. *Building Modern CLI Applications in Go*. Packt Publishing, Mar 2023.

