
# Content

In this problem, a neural net is represented by a rooted tree with weighted edges. The neural net processes information by a cascade of signals that begins at the leaf nodes: Each node in the tree computes an output value based on its upstream neighbors, and passes this value on to its downstream neighbor. The output value computed by a node is the sum of the output of each of its upstream neighbors multiplied by the weight of the edge from the upstream neighbor to the node itself. A node with no upstream neighbors (leaf nodes) always has $1$ as output. All neural nets in this problem have exactly one final output node (the root node).

Sometimes, a neural net can go haywire and become what is more commonly known as a neurotic network. Consider this your chance to launch a second career in psychiatry. The scenario is that someone just came in with a neurotic network in their head. What this means is that if the output of their neural net is an even number, the person will freak out and will set fire to a kitten. Therefore, it is of vital importance that you can know ahead of time whether or not a given person is safe. If it is safe, print their neural output modulo $1,000,000,007$. If you wouldn't trust the person to be around kittens who're not wrapped in fire retardant, print the string `FREAK OUT` (without the quotes).

# Standard Input

The first line of input is $T$, the number of test cases. For each of the $T$ cases, the first line will be the integer $N$, the number of nodes in the tree. The next line contains $N -1$ integers $a\_1,a\_2,\cdots ,a\_{N-1}$ where $a\_i$ is the downstream neighbour of the node with ID $i$.Then follows a line with $N - 1$ integers $w\_1,w\+2,\cdots ,w\_{N-1}$ where $w\_i$ is the weight of the neural connection going out from the node with ID $i$. Note that the node with ID $0$ will always be the output node.

$0 < T \le 50$

$0 < N \le 10000$

$0 < w\_i \le 10$

$0 \le a\_i < N$

The graph is guaranteed to be a tree.

This is an I/O-heavy problem. For Java programmers, this means that you should
use `BufferedReader` for input reading (not `Scanner`).

# Standard Output

Output `FREAK OUT` (without the quotes) if the final value of the neural net's output node is even. Otherwise, output the final value of the output node, modulo $1,000,000,007$.

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
4
0 0 2
7 7 1
4
0 0 2
6 7 2
11
0 1 2 3 4 5 6 7 8 9
9 9 9 9 9 9 9 9 9 3</td><td>1
FREAK OUT
FREAK OUT
162261460</td></tr></table>


# Constraints



# Note



# Source


