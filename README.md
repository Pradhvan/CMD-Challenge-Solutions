# CMD-Challenge-Solutions

This repository is for the for all the solutions and read-ups for the command line challenge. Since the challenges are one liners so with the solutions the following info on the command will be updated.  

Link to the challenge: https://cmdchallenge.com/

## Challenges and Solutions

### Question 1 - Print "hello world"

Command: [echo](http://linuxcommand.org/lc3_man_pages/echoh.html) 

Description: Echo the STRING(s) to standard output.

```
echo "hello world" 
```

### Question 2 - Print the current working directory

Command: [pwd](https://linux.die.net/man/1/pwd)

Description: Print the full filename of the current working directory.

```
pwd
```

### Question 3 - List names of all the files in the current directory

Command: [ls](https://linux.die.net/man/1/ls)

Description: List information about the FILEs (the current directory by default)

```
ls 
```

### Question 4 - There is a file named "access.log" in the current directory. Print the contents.

Command: [cat](https://linux.die.net/man/1/cat) 

Description: Concatenate FILE(s), or standard input, to standard output.

```
cat
```

### Question 5 -  Print the last 5 lines of "access.log".

Command: [tail](https://linux.die.net/man/1/tail)

Description: Print the last 10 lines of each FILE to standard output. With more than one FILE, precede each with a header giving the file name. With no FILE, or when FILE is -, read standard input.

```
tail -5 access.log
```

### Question 6 - There is a file named "access.log" in the current working directory. Print all lines in this file that contains the string "GET".

Command: [grep](https://linux.die.net/man/1/grep)

Description: grep searches the named input FILEs (or standard input if no files are named, or if a single hyphen-minus (-) is given as file name) for lines containing a match to the given PATTERN. By default, grep prints the matching lines.

```
grep "GET" access.log
```

