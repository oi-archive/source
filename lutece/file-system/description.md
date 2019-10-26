
# Content

Taobao File System(`TFS`) is a famous distributed file system consisted of thousands of servers storing and serving more than $10$ billion files. A lot of experts worked for this project, they are specialized in distributed system, Linux kernel, algorithm, etc. `TFS` has been open-sourced since Sep 27th, 2010.

Totalfrank is studying Operation System recently, and he loves open-source project. He wants to work with talented people at Taobao TFS team. In order to get the offer, Totalfrank needs to finish a file system called Totax within 30 minutes. The file system should support the following operations:
1. `cd Directory_Name`<br/>
If there is a directory called `Directory_Name` in current path, then move to the directory; else output `No such directory!` and ignore this operation.
2. `cd ..`<br/>
If there is a parent directory of current path, then move to the parent directory; else output `No parent directory!` and ignore this operation.
3. `touch File_Name`<br/>
If there is a file called `File_Name` in current path, then output `File already exists!` and ignore this operation; else create that file.
4. `rm File_Name`<br/>
If there is a file called `File_Name` in current path, then remove it; else output `No such file!` and ignore this operation.
5. `mkdir Directory_Name`<br/>
If there is a directory called `Directory_Name` in current path, then output `Directory already exists!` and ignore this operation; else create that directory and the current path doesn’t change.
6. `rmdir Directory_Name`<br/>
If there is a directory called `Directory_Name` in current path, then remove it and all items in it; else output `No such directory!` and ignore this operation.
7. `ls`<br/>
Show the file and directory list of current path. Each Item is displayed in a line like `Item_Name <Type>`. `Item_Name` is the name of a file or a directory. `Type` is `D` when the item is a directory or `F` when it’s a file. Items created earlier come first.

Note that, directory and file are two different objects and they may have the same name in the same directory. Two directories or two files may also have the same name in different paths.

At the very start, the current path is at root directory which hasn’t parent directory.

# Standard Input

The first line of the input is an integer $T$ ($T\leq 100$), which stands for the number of test cases you need to solve.

Each test case begins with an integer $Q$ ($Q\leq 100$), indicating the number of operations.

Then $Q$ lines follow, every line is an operation specified before. Files’ name and directories’ name are consist of lowercase latin letters only and their length will be positive and no larger than $10$.

# Standard Output

For every test case, you should output `Case #k:` first in a single line, where $k$ indicates the case number and starts at $1$. Then output the result of the operations.

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
3
mkdir standy
touch totalfrank
ls
6
mkdir standy
cd standy
touch totalfrank
cd ..
rm totalfrank
ls</td><td>Case #1:
standy <D>
totalfrank <F>
Case #2:
No such file!
standy <D></td></tr></table>


# Constraints



# Note



# Source


