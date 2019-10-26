
# Content

Tree Lover loves trees crazily.

One day he invents an interesting game which is named Tree Maker.

In this game, all trees are **binary trees**.

Initially, there is a tree with **only one** vertex and a cursor on it. Tree Lover can control the cursor to apply 5 operations to build a tree, and their formats are following:

0  : Jump to the parent of the current vertex.

1  : Jump to the left child of the current vertex.

2  : Jump to the right child of the current vertex.

3 x : Generate a tree with x vertices arbitrarily and make it the left subtree of the current vertex.

4 x : Generate a tree with x vertices arbitrarily and make it the right subtree of the current vertex.

When applying an operation, the log system will log down a record of it.

Tree Lover played this game for a whole day yesterday. As a forgetful man, although Tree Lover knew the shape of the tree  while playing, after a sleep he forgot it.

All he has now is the logs of operations.

Tree Lover wants to know: how many possible shapes of the tree can have yesterday according to the logs?

Can you answer this question?

# Standard Input

The input consists of multiple test cases.

For each test case:

The first line is an integer n (1 <= n <= 500), denoting the lines of logs.

Then follow n lines of logs. The formats of logs are as described above.

The integer x of operation 3 and 4 is positive.

In each case, the number of vertices of the tree will never exceed 500.

You can assume that **the cursor will never jump to a non-existent vertex**.

If the left child of a vertex exists, operation 3 will not be applied on this vertex, and operation 4 is similar.

# Standard Output

For each test case, ouput a single line “Case #x: y”, where x is the case number, starting from 1, and y is the answer to Tree Lover’s question.

Because the answer can be large, please output the answer mod 1000000007.

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
3 3
4 3
2
3 3
1
</td><td>Case #1: 25
Case #2: 5</td></tr></table>


# Constraints



# Note

Because the tree is a binary tree, if left and right subtrees of a vertex are of different shapes, after swapping them, the new tree is considered different from the original one.

# Source


