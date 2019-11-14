
# Content

A club wants to take its members camping. In order to organize the event better the club directors decided to partition the members into several groups.

Club member i has a responsibility value $r\_i$ and an age value $a\_i$. A group is a non-empty subset of club members with one member known as group leader. A group leader should be one of the most responsible members of the group (his responsibility value is not less than responsibility of any other group member) and his age absolute difference with any other group member should not exceed $k$.

Some club members are friends and want to be in the same group. They also like their group to be as large as possible. Now you should write a program that answers a series of questions like "What's the largest size of a group containing club member x and club member y?". It's possible for $x$ or $y$ to be the group leader.

# Standard Input

The first line contains two integers $n$ and $k$ $(2\le n\le 10^5,0\le k\le 10^9)$ — the number of club members and the age restriction for one group.

The next line contains integer numbers $r\_1,r\_2,\dots,r\_n (1\le r\_i\le 10^9)$ separated by space: $r\_i$ denotes the i-th club member's responsibility. In the same way there are integers $a\_1,a\_2,\dots,a\_n$ (1\le a\_i\le 10^9) in the third line: $a\_i$ denotes the i-th club member's age.

The next line contains an integer q denoting the number of questions that you should answer $(1\le q\le 10^5)$. The next q lines describe the questions. Each line contains two space-separated integers $x\_i$ and $y\_i$ $(1\le x\_i,y\_i\le n,x\_i\ne y\_i) $— the indices of the club members that should end up in the same group.

# Standard Output

For each question print the maximum size of the group in a line. If making such a group is impossible print -1 instead.

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
<tr><td>5 1
1 5 4 1 2
4 4 3 2 2
4
5 3
2 3
2 5
4 1</td><td>4
3
-1
4</td></tr></table>


# Constraints



# Note



# Source


