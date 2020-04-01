
# Description

<div class="content">You are given a node-labeled rooted tree with n nodes. 

Define the query (x, k): Find the node whose label is k-th largest in the subtree of the node x. Assume no two nodes have the same labels. 



</div>

# Input

<div class="content">The first line contains one integer n (1 &lt;= n &lt;= 10^5). The next line contains n integers li (0 &lt;= li &lt;= 109) which denotes the label of the i-th node. 

Each line of the following n - 1 lines contains two integers u, v. They denote there is an edge between node u and node v. Node 1 is the root of the tree. 

The next line contains one integer m (1 &lt;= m &lt;= 10^4) which denotes the number of the queries. Each line of the next m contains two integers x, k. (k &lt;= the total node number in the subtree of x) 



</div>

# Output

<div class="content">
For each query (x, k), output the index of the node whose label is the k-th largest in the subtree of the node x. 
</div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 3 5 2 7<br/>
1 2<br/>
2 3<br/>
1 4<br/>
3 5<br/>
4<br/>
2 3<br/>
4 1<br/>
3 2<br/>
3 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
5<br/>
4<br/>
5<br/>
5<br/>
<br/>
<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p><br/>
Amber的play with tree系列的题.... <br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

