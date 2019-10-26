
# Content

![title](/source/lutece/hyacinth/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTExOS8yMDE1MDUxNjIyMTY0MjUzNDgyLmpwZw==.jpg)

As a new employee at the Northwestern Europe Routing Company (NWERC), you do a lot of thinking about wireless network architectures. Lately you learned about a multi-channel mesh network architecture (called Hyacinth) that equips each mesh network node with multiple network interface cards (NICs) to increase the network throughput. You can choose a channel frequency for each NIC. In order to communicate, for every two network nodes that are in range of each other, their NICs must share at least one common frequency. The theoretical throughput is optimal when the total number of used frequencies in the network is maximal.

Your bosses at NWERC want you to figure out a procedure for assigning frequencies to the NICs such that the number of frequencies in use is maximized, subject to the constraint that all pairs of adjacent nodes must be able to communicate. A frequency is considered used if any pair of nodes within range of each other share that frequency. In the mesh network that you will be dealing with, each node is equipped with exactly two NICs (i.e., each node can use at most two frequencies). Since you are new at NWERC, your bosses further restrict the network layouts to make your job easier: the network graph will form a tree.

# Standard Input

The input consists of:

>#####one line with one integer n $(2≤n≤10000)$, the number of nodes in the network;
>#####n−1 lines, each with two space-separated integers i and j, with $1≤i,j≤n$ signifying that the (one-indexed) network nodes i and j are in range of each other.

# Standard Output

Output a frequency assignment for each of the $2n$ NICs such that all adjacent nodes can communicate and the number of used frequencies is maximized. You should output $n$ lines, where the ith line contains the two frequencies of network node i. Valid frequencies are nonnegative integers less than $10^9$.

`If there are several correct answers, you can output any of them. `

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
1 2</td><td>23 42
42 23</td></tr><tr><td>14
1 2
1 3
1 4
2 5
2 6
3 7
4 8
4 9
4 10
7 11
7 12
7 13
7 14</td><td>4711 815
666 4711
4711 42
815 7
47 666
666 54
23 42
7 2
7 1
7 3
23 4
42 5
23 6
42 8</td></tr></table>


# Constraints



# Note

`Sample Output is not the only answer of Sample Input.` Any answer satisfying the conditions will be considered correct.

For example, in the first case, the following output is also find.

>#####42 23
>#####23 42

# Source


