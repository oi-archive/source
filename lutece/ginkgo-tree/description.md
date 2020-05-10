
# Content

Ginkgo attracts a huge number of visitors to come to the Park of Electronic Science and Technology of China, though it's a kind of REALLY smelly tree. Kanade takes the responsibility of managing the main ginkgo tree, making the tree beautiful but not malodorous.

The main ginkgo tree in PESTC, Shahe is quite weird. Kanade knows that the tree consists of $n$ nodes and $n-1$ edges. The root of the tree is node $1$. Each node has a beauty value, indicating its smelly level. When the beauty value of one node changes, all the nodes in its subtree whose  distance to the node is a Fibonacci number changes the same. Formally, if the beauty value of node $x$ adds $y$, all the nodes $z$ in the subtree of $x$ which $d(x,z)\in f$ adds $y$. Where, $f$ refers to the set of Fibonacci numbers, $d(x,y)$ refers to the edge number of the shortest path from $x$ to $y$.

Sometimes Kanade will trim the tree, so she wants to know the sum of beauty value which holds $d(x,z)\in f$, where $z$ is a node in the subtree of $x$. But Kanade think it a really troublesome work. She's not actually going to trim the trees.

Kanade is busy with writing the report of Machine Learning and Its Application. Please help her.

# Standard Input

The first line of the input contains two integer $n,m$, indicating the number of nodes and query.

The second line contains $n$ integer $a_i$. The $i$ - th number indicates the beauty value of node $i$ at the beginning.

The third line contains $n-1$ integer $p_i$. The $i$ - th number indicates the parent of $i+1$.

The next $m$ lines, contains two or three integers, formatted as follows:

- $\texttt{1 x y}$: all the nodes in the subtree of $x$ which hold $d(x,i)\in f$ adds y;
- $\texttt{2 x}$: output the sum of beauty value of the nodes in the subtree of $x$ which hold $d(x,i)\in f$.

# Standard Output

For all query of type $2$, output an integer in a line, indicating the answer.

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
<tr><td>6 5
1 1 4 5 1 4
5 2 1 4 2
1 1 4
2 1
1 2 2
1 5 -3
2 4</td><td>24
21</td></tr></table>


# Constraints

$2\le n\le 2\times 10^5,1\le m\le 2\times 10^5, 1\le p_i,x\le n,1\le |a_i|,|y|\le 10^6$, and the $p_i$ can construct a tree.

# Note



# Source


