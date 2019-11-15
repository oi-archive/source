<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Our engineers have designed a communication network that consists of nodes and unidirectional direct <br>communication channels (links) between some pairs of nodes. We say that a node q is reachable from node p on a <br>path, if there is a sequence of different nodes p1,p2,…,pk with p=p1 and q=pk, such that there is a link that transmits <br>data from pi to pi+1 for every i=1,…,k-1. This network has a central node r, such that any other node p can be reached <br>from r via a path, and for any pair of nodes p and q there is at most one path on which q can be reached from p. The <br>maintainers plan to improve on the network, but have not yet decided how. One idea they are considering is to <br>reassign the central node, therefore they want to know for each node how many nodes are reachable from it on a path. <br>Another idea is to just decentralize the network, so they also want to know how they could introduce new links so that <br>for any pair of nodes p and q, there is exactly one path on which the node q can be reached from p, and vice versa.</p>
<p>Task <br>You are to write a program that computes the number of reachable nodes for every node (Subtask A), and also <br>computes the minimum number of new links needed to make every node reachable in a unique way from every other <br>node. Your program must give the list of new links, too (Subtask B).</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The first line of the input contains three integers, N (1 ≤ N ≤ 100 000) the number of nodes, M (1 ≤ M ≤ 500 000)<br>the number of links, and r (1 ≤ r ≤ N) the central node. Nodes are numbered from 1 to N. The next M lines contain the<br>description of the links. Each line contains two integers p and q separated by space, that corresponds to a link, which<br>can transmit data from p to q.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>The first line of the output contains the solution to Subtask A: N integers separated by space, where the ith number <br />is the number of reachable nodes from node i (including i itself). The remaining lines contain the solution for Subtask <br />B: The second line of the output contains one integer K, the minimum number of new links needed to achieve the <br />above property of the network. The next K lines list the new links: each of lines contains two integers u and v <br />separated by space, that corresponds to a new link transmitting data from node u to node v. If there are multiple <br />solutions, your program should output only one; it does not matter which one.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>11 12 3</p>
<p><span style="">3 2 </span></p>
<p>2 1 <br>2 4 <br>4 5 <br>4 6 <br>6 2 <br>6 7 <br>3 8 <br>8 9 <br>9 10 <br>9 11 <br>10 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 6 11 6 1 6 1 4 4 4 1<br>5 <br>1 3 <br>5 4 <br>7 6 <br>11 9 <br>8 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>In 50% of the test cases N is at most 10 000. <br>Subtask A is worth 40% of the points, Subtask B is worth the other 60% of the points. <br>If you only solve Subtask B, you must write N integers in the first line.</p>
</div>
</div>