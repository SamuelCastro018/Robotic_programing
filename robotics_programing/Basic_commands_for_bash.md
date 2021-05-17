# Commands to create directorys ( Bash )

## ls — List directory contents

ls is probably the most common command. A lot of times, 
you’ll be working in a directory and you’ll need to know what files are located there. 
The ls command allows you to quickly view all files within the specified directory.

Syntax: ls [option(s)] [file(s)]

Common options: -a, -l

## touch — Creates a file

touch is going to be the easiest way to create new files, 
but it can also be used to change timestamps on files and/or directories. 
You can create as many files as you want in a single command 
without worrying about overwriting files with the same name.

Syntax: touch [option(s)] file_name(s)

Common options: -a, -m, -r, -d

## grep — search

grep is used to search text for patterns specified by the user. 
It is one of the most useful and powerful commands. 
There are often scenarios where you’ll be tasked to find a particular string or pattern within a file, 
but you don’t know where to start looking, that is where grep is extremely useful.

## man — Print manual or get help for a command

The man command is your manual and is very useful when you need to figure out what a command does. 
For example, if you didn’t know what the command rmdir does, you could use the man command to find that out.

Syntax: man [option(s)] keyword(s)

Common options: -w, -f, -b

## pwd — Print working directory

pwd is used to print the current directory you’re in. As an example,
if you have multiple terminals going and you need to remember the exact directory you’re working within,
then pwd will tell you.

## cd — Change directory 

cd will change the directory you’re in so that you can get info, manipulate,
read, etc. the different files and directories in your system.

Syntax: cd [option(s)] directory.

Common options: options aren’t typically used with cd.

## mv — Move or rename directory

mv is used to move or rename directories. 
Without this command, you would have to individually rename each file which is tedious.
mv allows you to do batch file renaming which can save you loads of time.

Syntax: mv [option(s)] argument(s)

Common options: -i, -b

## locate — Locate a specific file or directory

This is by far the simplest way to find a file or directory. 
You can keep your search broad if you don’t know what exactly it is you’re looking for, 
or you can narrow the scope by using wildcards or regular expressions.

Syntax: locate [option(s)] file_name(s)

Common options: -q, -n, -i

## less — view the contents of a text file

The less command allows you to view files without opening an editor.
It’s faster to use, and there’s no chance of you inadvertently modifying the file.

## cat — Read a file, create a file, and concatenate files

cat is one of the more versatile commands and serves three 
main functions : displaying them, combining copies of them, and creating new ones.
