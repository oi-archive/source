
# Description

<div class="content"><p><span style="font-size: medium">Isaac is tired of his daily trip to his office, using the same shortest route everyday. Although this saves his time, he must see the same scenery again and again. He cannot stand such a boring commutation any more. One day, he decided to improve the situation. He would change his route everyday at least slightly. His new scheme is as follows. On the first day, he uses the shortest route. On the second day, he uses the second shortest route, namely the shortest except one used on the first day. In general, on the k-th day, the k-th shortest route is chosen. Visiting the same place twice on a route should be avoided, of course. You are invited to help Isaac, by writing a program which finds his route on the k-th day. The problem is easily modeled using terms in the graph theory. Your program should find the k-th shortest path in the given directed graph. </span></p>
<p><span style="font-size: medium"><strong><span style="color: red"><em>n</em></span><span style="color: red">结点有向简单图中的简单</span><i><span style="color: red">k</span></i><span style="color: red">短路（结点不能重复经过）</span><span style="color: red">.</span><span style="color: red">路径长度相同时按照字典序排列</span><span style="color: red">.<i>n</i>&lt;=50, <i>k</i>&lt;=200, </span></strong></span></p></div>

# Input

<div class="content"><p>The input consists of multiple datasets, each in the following format. n m k a b x1 y1 d1 x2 y2 d2 … xm ym dm Every input item in a dataset is a non-negative integer. Two or more input items in a line are separated by a space. n is the number of nodes in the graph. You can assume the inequality 2 ≤ n ≤ 50. m is the number of (directed) edges. a is the start node, and b is the goal node. They are between 1 and n, inclusive. You are required to find the k-th shortest path from a to b. You can assume 1 ≤ k ≤ 200 and a ≠ b. The i-th edge is from the node xi to yi with the length di (1 ≤ i ≤ m). Both xi and yi are between 1 and n, inclusive. di is between 1 and 10000, inclusive. You can directly go from xi to yi, but not from yi to xi unless an edge from yi to xi is explicitly given. The edge connecting the same pair of nodes is unique, if any, that is, if i ≠ j, it is never the case that xi equals xj and yi equals yj. Edges are not connecting a node to itself, that is, xi never equals yi. Thus the inequality 0 ≤ m ≤ n(n − 1) holds. Note that the given graph may be quite unrealistic as a road network. Both the cases m = 0 and m = n(n − 1) are included in the judges’ data. The last dataset is followed by a line containing five zeros (separated by a space).</p></div>

# Output

<div class="content"><p>For each dataset in the input, one line should be output as specified below. An output line should not contain extra characters such as spaces. If the number of distinct paths from a to b is less than k, the string None should be printed. Note that the first letter of None is in uppercase, while the other letters are in lowercase. If the number of distinct paths from a to b is k or more, the node numbers visited in the k-th shortest path should be printed in the visited order, separated by a hyphen (minus sign). Note that a must be the first, and i must be the last in the printed line. In this problem the term shorter (thus shortest also) has a special meaning. A path P is defined to be shorter than Q, if and only if one of the following conditions holds. The length of P is less than the length of Q. The length of a path is defined to be the sum of lengths of edges on the path. The length of P is equal to the length of Q, and P’s sequence of node numbers comes earlier than Q’s in the dictionary order. Let’s specify the latter condition more precisely. Denote P’s sequence of node numbers by p1, p2, …, ps, and Q’s by q1, q2, …, qt. p1 = q1 = a and ps = qt = b should be observed. The sequence P comes earlier than Q in the dictionary order, if for some r (1 ≤ r ≤ s and r ≤ t), p1 = q1, …, pr − 1 = qr − 1, and pr &lt; qr (pr is numerically smaller than qr). A path visiting the same node twice or more is not allowed.</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 20 10 1 5<br/>
1 2 1<br/>
1 3 2<br/>
1 4 1<br/>
1 5 3<br/>
2 1 1<br/>
2 3 1<br/>
2 4 2<br/>
2 5 2<br/>
3 1 1<br/>
3 2 2<br/>
3 4 1<br/>
3 5 1<br/>
4 1 1<br/>
4 2 1<br/>
4 3 1<br/>
4 5 2<br/>
5 1 1<br/>
5 2 1<br/>
5 3 1<br/>
5 4 1<br/>
4 6 1 1 4<br/>
2 4 2<br/>
1 3 2<br/>
1 2 1<br/>
1 4 3<br/>
2 3 1<br/>
3 4 1<br/>
3 3 5 1 3<br/>
1 2 1<br/>
2 3 1<br/>
1 3 1<br/>
0 0 0 0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1-2-4-3-5<br/>
1-2-3-4<br/>
None<br/>
<br/>
<br/>
Hint<br/>
<br/>
In the case of the first dataset, there are 16 paths from the node 1 to 5. They are ordered as follows (The number in parentheses is the length of the path).<br/>
<br/>
1 (3) 1-2-3-5 9 (5) 1-2-3-4-5 <br/>
2 (3) 1-2-5 10 (5) 1-2-4-3-5 <br/>
3 (3) 1-3-5 11 (5) 1-2-4-5 <br/>
4 (3) 1-4-3-5 12 (5) 1-3-4-5 <br/>
5 (3) 1-4-5 13 (6) 1-3-2-5 <br/>
6 (3) 1-5 14 (6) 1-3-4-2-5 <br/>
7 (4) 1-4-2-3-5 15 (6) 1-4-3-2-5 <br/>
8 (4) 1-4-2-5 16 (8) 1-3-2-4-5 <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Japan 2006 K短路">Japan 2006 K短路</a></p></div>

