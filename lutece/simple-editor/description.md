
# Content

In our daily life, word processing is a very important kind of work. In order to complete the documents quickly, Fish had written a simple document editor.

But the document editor is too simple to do kinds of processing work. It just supports only three kinds of operations:
1. We can move the cursor left or right.
2. We can insert a character $X$ after the cursor. After inserting the character $X$, the cursor move to the right of $X$ immediately.
3. We can delete the character after the cursor, and the cursor isn't move.

Now give you some operation commands, Fish want to know the last sequence of characters.

# Standard Input

There is only one integer $T$($T\leq 20$) on the first line, which indicates the number of test cases.

In the first line of each test case, there is one integer $n$($1\leq n\leq 1,000,000$) indicates the number of commands in this case. Then n lines followed, each line represents a command having one of those formats:
* `Left`: the cursor moves one position to the left, if the cursor is on the leftmost position originally, ignore it.
* `Right`: the cursor moves one position to the right, if the cursor is on the rightmost position oritinally, ignore it.
* `Insert X`: insert the character $X$ after the cursor.
* `Delete`: delete the charactor on the right of the cursor, if there isn't any character on the right of the cursor, ignore it.

# Standard Output

For each test case, output one line. First ,output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then, output the last sequence of characters finally.

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
7
Insert e
Left
Insert H
Right
Insert l
Insert l
Insert o
13
Insert W
Insert e
Left
Delete
Insert r
Insert l
Insert d
Insert !
Left
Left
Left
Left
Insert o</td><td>Case #1: Hello
Case #2: World!</td></tr></table>


# Constraints



# Note



# Source


