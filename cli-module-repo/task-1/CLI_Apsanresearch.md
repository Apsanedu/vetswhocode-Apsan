# Research on the History of the Command Line Interface (CLI)

## Introduction

Until the 1960s, computers primarily used mechanical punch cards for inputting both computer programs and data. This required a trained individual to manually punch the cards, limiting the use of primitive languages like Assembly code, COBOL, and FORTRAN. The advent of magnetic tape for storage, combined with displays and keyboards, marked a significant shift in computing, leading to the creation of modern-day computers and command-line interfaces (CLI).

In the early 1960s, engineers attached a Cathode Ray Tube (CRT) monitor to the TeleTYpewriter (TTY) machine, allowing users to type commands and interact with the computer, laying the foundation for CLI as we know it today.

## Evolution of Command Line Interface

### 1970s: Emergence of Graphical User Interfaces (GUIs)

In the 1970s, early versions of Graphical User Interfaces (GUIs) were invented. The invention of the computer mouse further revolutionized computing, paving the way for personal computers and operating systems accessible to common people.

## Notable Figures

### Ken Thompson and Dennis Ritchie

- Founders of Unix, which laid the foundation for the modern CLI. They developed the Unix operating system at Bell Labs, featuring the command-line interface as a central component.

### Brian Kernighan

- Co-author of "The C Programming Language" and a key contributor to Unix. He played a significant role in shaping the design and development of Unix and its command-line interface.

### Richard Stallman

- Founder of the Free Software Foundation and the GNU Project, aiming to create a free Unix-like operating system. The GNU tools, including the GNU Compiler Collection (GCC) and bash shell, are critical components of the modern CLI.

### Stephen R. Bourne

- Developed the Bourne shell (sh), one of the earliest Unix shells, which served as the basis for subsequent shells and greatly influenced the evolution of CLI.

### Linus Torvalds

- Creator of the Linux kernel, which, when combined with GNU tools and utilities, resulted in the popular Linux operating system, utilizing the CLI extensively.

## Understanding Terminal vs. Shell

### Terminal or Terminal Emulator

The application or program where you enter commands. Common terminals include Terminal (Mac), Windows Command Prompt, Alacritty, st, etc.

### Shell

The shell is the language that your terminal uses. Today, Bash (and other shells like bash), Windows Command prompt, and PowerShell are the most popular shells. Zsh, based on Bash, is particularly popular among programmers.

## The Modern CLI and Its Advantages

Today, the majority of users opt for graphical programs to perform tasks. However, there's a thriving community of CLI program users. Various CLI-based utilities and tools like Ranger, Vim, Emacs, brew, chocolatey, apt, pacman, ffmpeg, cmus, tmux, Zathura, and more are popular within this community.

### Bash Commands

Bash (Bourne Again Shell) comes with basic commands to interact with your computer. These include viewing and moving between directories (cd, ls, mv, cp, rm, mkdir), creating, viewing, and editing text files (touch, cat, less, more), and compiling/sourcing config files (for example, source ~/.zshrc).

## Advantages of CLI over GUI

- CLI offers faster performance and does not have to render large graphical elements.
- Users can utilize command arguments to specify options, providing efficiency.
- CLI programs follow the UNIX philosophy of modularity, making them efficient and modular.
- Automation is simplified with scripting, allowing users to create and execute scripts for streamlined tasks.

## Works Cited

Montagnino, Marian. *Building Modern CLI Applications in Go*. Packt Publishing. Mar 2023.

