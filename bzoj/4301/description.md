
# Description

<div class="content"><div>JRY is so rich that he bought too many trees and planted them in his yard. Because of his personal preference, all these trees have the same shape. At first, these trees were small and peaceful, but after growing for several years, they become huge and compete for the limited water and nutrition. Therefore, they become angry, and their common enemy is JRY, because it is JRY who planted them in such a &#34;small&#34; place (although his yard is the biggest in the world). </div>
<div></div>
<div>There are m angry trees, and each angry tree has n nodes and n−1 branches. All the angry trees decide to combine together, and they made extra m−1 branches so that they can be one. Moreover, they select the first node of the first tree to be the root of the whole huge tree. Now, there is a terribly enormous tree with nm nodes and nm−1 branches. </div>
<div></div>
<div>The trees come up with an idea to revenge. When JRY is sleeping, they drag JRY onto one of the nodes, and steal all JRY&#39;s money and put it onto one node too (the two nodes can be either same or different). When JRY wakes up, he definitely will go for these money. Every time JRY moves down along a branch (moving towards the root), he will spend 1 unit time, and when he moves up along a branch (moving away from the root), he will spend 2 unit time. Additionally, smart JRY will always move along the shortest path on the tree between him and his money. </div>
<div></div>
<div>One nightmare of the trees is to find the longest time that JRY need to find his money, and they also need to know how many different ways there are to get this longest time (two ways are considered different if and only if JRY&#39;s initial position is different or the money&#39;s position is different). Can you help them?</div>
<p></p></div>

# Input

<div class="content"><div>The first line of the input is a single integer T, indicating the number of testcases. </div>
<div>For each testcase, the first line is two integers n and m (1n,m50000). Each of the next n−1 lines contains two integers x and y, which represent one branch (x,y) in every tree. Each of the following m−1 lines contains four integers x,a,y,b, which means there is an additional branch connecting the a-th node of the x-th tree and the b-th node of the y-th tree. It is guaranteed that either every small tree or the whole tree is an acyclic connected undirected graph. Please be aware that the first node (the node numbered 1) of the first tree (the tree numbered 1) is the root of the whole tree. </div>
<div>It is guaranteed that for all the testcases, Siga(n)+Sigma(m)&lt;=1000000.</div>
<p></p></div>

# Output

<div class="content"><div>For each testcase, print two space-separated integers indicating the longest time JRY need to find his money and the ways of position to reach this upper bound.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 3<br/>
3 1<br/>
2 1<br/>
3 1 2 2<br/>
1 3 2 1<br/>
3 8<br/>
3 1<br/>
2 3<br/>
4 3 3 1<br/>
3 1 2 3<br/>
6 2 1 3<br/>
8 3 7 3<br/>
5 3 7 3<br/>
6 3 7 2<br/>
8 3 2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">11 2<br/>
22 3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

