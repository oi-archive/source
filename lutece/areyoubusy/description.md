
# Content

Happy New Term!

As having become a junior, xiaoA recognizes that there is not much time for her to AC problems, because there are some other things for her to do, which makes her nearly mad.

What's more, her boss tells her that for some sets of duties, she must choose at least one job to do, but for some sets of things, she can only choose at most one to do, which is meaningless to the boss. And for others, she can do of her will. We just define the things that she can choose as `jobs`. A job takes time , and gives xiaoA some points of happiness (which means that she is always willing to do the jobs).So can you choose the best sets of them to give her the maximum points of happiness and also to be a good junior(which means that she should follow the boss's advice)?

# Standard Input

There are several test cases, each test case begins with two integers $n$ and $T (0 \leq n,T \leq 100)$ , $n$ sets of jobs for you to choose and $T$ minutes for her to do them. Follows are $n$ sets of description, each of which starts with two integers $m$ and $s (0 < m \leq 100)$, there are $m$ jobs in this set , and the set type is $s$, ($0$ stands for the sets that should choose at least $1$ job to do, $1$ for the sets that should choose at most $1$ , and $2$ for the one you can choose freely).then m pairs of integers $c\_i,g\_i$ follows $(0 \leq c\_i,g\_i  \leq 100)$, means the $i\_{th}$ job cost $c\_i$ minutes to finish and $g\_i$ points of happiness can be gained by finishing it. One job can be done only once.

# Standard Output

One line for each test case contains the maximum points of happiness we can choose from all jobs .if she can’t finish what her boss want, just output `-1` .

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
<tr><td>3 3
2 1
2 5
3 8
2 0
1 0
2 1
3 2
4 3
2 1
1 1

3 4
2 1
2 5
3 8
2 0
1 1
2 8
3 2
4 4
2 1
1 1

1 1
1 0
2 1

5 3
2 0
1 0
2 1
2 0
2 2
1 1
2 0
3 2
2 1
2 1
1 5
2 8
3 2
3 8
4 9
5 10</td><td>5
13
-1
-1</td></tr></table>


# Constraints



# Note



# Source


