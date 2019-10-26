
# Content

*Data structure* is a fundamental course of Computer Science, so that each contestant is highly likely to solve this data structure problem.

A Heap data structure is a binary tree with the following properties:
1. It is a complete binary tree; that is, each level of the tree is completely filled, except possibly the bottom level. At this level, it is filled from left to right.
2. It satisfies the heap-order property: The key stored in each node is greater than or equal to the keys stored in its children.

So such a heap is sometimes called a max-heap. (Alternatively, if the comparison is reversed, the smallest element is always in the root node, which results in a min-heap.)

A binary search tree (BST), which may sometimes also be called an ordered or sorted binary tree, is a node-based binary tree data structure which has the following properties:
1. The left subtree of a node contains only nodes with keys less than (greater than) the node's key.
2. The right subtree of a node contains only nodes with keys greater than (less than) the node's key.
3. Both the left and right subtrees must also be binary search trees.

Given a complete binary tree with $N$ keys, your task is to determine the type of it.

Note that either a max-heap or a min-heap is acceptable, and it is also acceptable for both increasing ordered BST and decreasing ordered BST.

# Standard Input

The first line of the input is $T$ (no more than $100$), which stands for the number of test cases you need to solve.

For each test case, the first line contains an integer $N$ ($1 \leq N \leq 1000$), indicating the number of keys in the binary tree. On the second line, a permutation of $1$ to $N$ is given. The key stored in root node is given by the first integer, and the $2i\_{th}$ and $2i+1\_{th}$ integers are keys in the left child and right child of the $i\_{th}$ integer respectively.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and counts from $1$. Then output the type of the binary tree:
* `Neither` --- It is neither a Heap nor a BST.
* `Both` --- It is both a Heap and a BST.
* `Heap` --- It is only a Heap.
* `BST` --- It is only a BST.

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
<tr><td>4
1
1
3
1 2 3
3
2 1 3
4
2 1 3 4</td><td>Case #1: Both
Case #2: Heap
Case #3: BST
Case #4: Neither</td></tr></table>


# Constraints



# Note



# Source


