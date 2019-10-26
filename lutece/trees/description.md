
# Content

On Bertown's main street $n$ trees are growing,the tree number $i$ has the height of $a\_i$ meters ($1\leq i\leq n$). By the arrival of the President of Berland these trees were decided to be changed so that their heights formed a beautiful sequence. This means that the heights of trees on ends (the $1\_{st}$ one and the $n\_{th}$ one) should be equal to each other, the heights of the $2\_{nd}$ and the $(n-1)\_{th}$ tree must also be equal to each other, at that the height of the $2\_{nd}$ tree should be larger than the height of the first tree by $1$,and so on. In other words, the heights of the trees, standing at equal distance from the edge (of one end of the sequence) must be equal to each other, and with the increasing of the distance from the edge by $1$ the tree height must also increase by $1$.For example, the sequences `2 3 4 5 5 4 3 2` is beautiful, and `1 3 3 1` and `1 2 3 1` are not.

<b class="font-danger">Changing the height of a tree is a very expensive operation, using advanced technologies invented by Berland scientists. In one operation you can choose any tree and change its height to any number, either increase or decrease. Note that even after the change the height should remain a positive integer, i. e, it can't be less than or equal to zero. Identify the smallest number of changes of the trees' height needed for the sequence of their heights to become beautiful.<b>

# Standard Input

The first line contains integer $T$($T\leq 100$) which is the number of test cases. The following line contains integer $n$ ($1\leq  n\leq 10^5$) which is the number of trees. The following line contains integers $a\_i$ ($1\leq  a\_i \leq 10^5$) which are the heights of the trees.

# Standard Output

Print a single number which is the minimal number of trees whose heights will have to be changed for the sequence to become beautiful.

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
2 2 2
4
1 2 2 1</td><td>1
0</td></tr></table>


# Constraints



# Note



# Source


