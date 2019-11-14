
# Content

In software development, Make is a utility that automatically builds executable programs and libraries from source code by reading files called makefiles which specify how to derive the target program. Though integrated development environments and language-specific compiler features can also be used to manage a build process, Make remains widely used, especially in Unix.

Now let's have a look at the grammar of makefile. Please note that in this problem, we have simplified the problem a lot, so read carefully, especially when you are familiar with such things.

In this problem, makefile contains three kinds of statements:

1. `Target: [component ...]`
<br/>
This is a statement to define a target. To build `Target`, you have to generate all the files in `[component ...]` at first. Here is an example:
```
a.o: a.cc b.cc
```
Which means if you want to generate file `a.o`, you have to make sure that there are already file `a.cc` and `b.cc` in the directory.
<br/>
Each component(including the target itself) will be a string which is a legal file's name, as `aaa` or `aaa.bbb`. 
They will be separated by some spaces.
<br/>
A legal file's name will only contain letters (upper case and lower case), numbers and only contain one dot (`.`).
<br/>
There won't be two Targets sharing a same file name. Also relations between files won't form a circle.
2. `Commands`
<br/>
This is a command shows how to build the Target, usually written after statement $1$. Here is an example:
```
    g++ a.o b.o -o main
```
Note this kind of commands will have **`FOUR SPACES`** at the front of the line.
<br/>
There maybe two or more commands after statement $1$.
3. `Comments`
<br/>
Comments begin with character `#`, which should be ignored. Note that `#` can appear in any place in the line, and all character after `#` in the line shall be ignored. Here is an example:
```
a.o: a.cc b.cc #hello world!
```
This should be regarded as 
```
a.o: a.cc b.cc
```

Sometimes you may find a statement is too long to be written in a single line. You can add a `\` at the end of the line, indicating that there are still part of statement at the next line. Here is an example:
```
main: a.o\
    b.o
	g++ a.o b.o -o main
```
This equals to the statement
```
main: a.o    b.o
    g++ a.o b.o -o main
```
Notice that `\` will only appear at end of the line and not appear in comments.

Now this is all a makefile will have.

You have a makefile, and you will execute $Q$ `make` commands one by one. There are already some files in the directory.

The make command is like this:

```
make Target
```

Which will try to generate a file named `Target`.

If there are no such `Target` defined in the makefile, or it cannot be built since lack of files. This command will not get executed.

Your task is, after executing each command, how many new files will appear in the directory?

# Standard Input

The first line has a number $T$ ($T\leq 10$) , indicating the number of test cases.

Then some lines come, indicating the content of makefile. A string `====` indicating the end of makefile. 
each line is no longer than $1000$ characters.
the size of makefile will not exceed $1MB$.

There are at most $500$ target in the Makefile.

Then comes a single line with a number $N$($N\leq 500$). Which is the number of files that are already in the directory.

Then come $N$ lines each with a file name.

Then comes a single line with a number $Q$($Q\leq 500$). Which is the number of command you are going to execute.

Then come $Q$ lines each with a command, within the pattern `make Target`.

# Standard Output

For test case $X$, output `Case #X: ` first, in a single line.

Then for each command, output the number of newly built files in a single line. If the command are not executed, output $0$.

There should be a blank line **`BETWEEN`** each test case.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>2
main: a.o\
    b.o
    g++ a.o b.o -o main
a.o: a.cc
    g++ a.cc -o a.o -c
b.o: b.cc
    g++ b.cc -o b.o -c
main2: a.o c.o
    g++ a.o c.o -o main2
====
3
a.cc
b.cc
c.o
2
make main
make main2

main: a.o b.o
    g++ a.o b.o -o main
a.o: a.cc
    g++ a.cc -o a.o -c
b.o: b.cc
    g++ b.cc -o b.o -c
main2: a.o c.o
    g++ a.o c.o -o main2
====
2
a.cc
b.cc
2
make main
make main2</td><td>Case #1:
3
1

Case #2:
3
0</td></tr></table>


# Constraints



# Note



# Source


