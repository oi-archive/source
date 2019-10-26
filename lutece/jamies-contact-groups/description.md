
# Content

Jamie is a very popular girl and has quite a lot of friends, so she always keeps a very long contact list in her cell phone. The contact list has become so long that it often takes a long time for her to browse through the whole list to find a friend's number. As Jamie's best friend and a programming genius, you suggest that she group the contact list and minimize the size of the largest group, so that it will be easier for her to search for a friend's number among the groups. Jamie takes your advice and gives you her entire contact list containing her friends' names, the number of groups she wishes to have and what groups every friend could belong to. Your task is to write a program that takes the list and organizes it into groups such that each friend appears in only one of those groups and the size of the largest group is minimized.

# Standard Input

There are multiple cases.The first line is an integer $T$ representing the number of test cases. Ease case starts with a line containing two integers $N$ and $M$. where $N$ is the length of the contact list and $M$ is the number of groups. $N$ lines then follow. Each line contains a friend's name and a integer $X$ represent the numbers of groups the friend could belong to,following $X$ numbers describe the groups the friend could belong to . You can assume $N$ is no more than $1000$ and $M$ is no more than $500$. The names will contain alphabet letters only and will be no longer than $15$ characters. No two friends have the same name. The group label is an integer between $0$ and $M - 1$.

# Standard Output

For each test case, output one line. First, output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then output a single integer, the size of the largest contact group.

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
3 2
John 2 0 1
Rose 1 1
Mary 1 1
5 4
ACM 3 1 2 3
ICPC 2 0 1
UESTC 3 0 2 3
Graph 2 1 2
Accepted 2 0 2</td><td>Case #1: 2
Case #2: 2</td></tr></table>


# Constraints



# Note



# Source


