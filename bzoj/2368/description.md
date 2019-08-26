
# Description

<div class="content"><p><font face="Times New Roman" size="3">定义树A与B同构，当且仅当树A的顶点经过一定的重新标号，树A的顶点集合边集完全与树B一一对应。 <br/>
Your Task <br/>
给定两棵树T1与T2，判断是否存在T1的子树T3，使得T3与T1同构。 <br/>
</font></p></div>

# Input

<div class="content"><p><font face="Times New Roman" size="3">第一行T表示数据组数 <br/>
对于每组数据，第一行n表示T1的点数 <br/>
接下来n-1行每行a b描述T1的一条边 <br/>
接下来一行m表示T2的点数 <br/>
再接下来m-1行每行a b描述T2的一条边 <br/>
</font></p></div>

# Output

<div class="content"><p><font face="Times New Roman" size="3">对于每组数据，在一行中输出YES表示存在T3，NO表示不存在 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">51 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
4<br/>
1 2<br/>
1 3<br/>
1 4<br/>
5<br/>
1 2<br/>
1 3<br/>
1 4<br/>
4 5<br/>
4<br/>
1 2<br/>
2 3<br/>
3 4<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">	NO<br/>
	YES<br/>
</span></div>

# Hint

<div class="content"><p></p><p>样例解释<br/><br/>
 第一组数据中T2的点1度数为3，而T1是一条链，没有度数为3的点，显然NO。<br/><br/>
 第二组数据中T2是一条4个点的链，与T1中的2-1-4-5同构。</p><br/>
<p><br/><br/>
数据范围</p><br/>
<p> 100%：T≤10，1≤m&lt;=N&lt;=100<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=google code jam 2008 APAC Onsites  ">google code jam 2008 APAC Onsites  </a></p></div>

