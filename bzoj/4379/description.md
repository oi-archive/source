
# Description

<div class="content"><p>给定一棵无根树，边权都是1，请去掉一条边并加上一条新边，定义直径为最远的两个点的距离，请输出所有可能的新树的直径的最小值和最大值</p></div>

# Input

<div class="content"><p>第一行包含一个正整数n(3&lt;=n&lt;=500000)，表示这棵树的点数。<br/>
接下来n-1行，每行包含两个正整数u,v(1&lt;=u,v&lt;=n)，表示u与v之间有一条边。</p></div>

# Output

<div class="content"><p>第一行输出五个正整数k,x1,y1,x2,y2，其中k表示新树直径的最小值，x1,y1表示这种情况下要去掉的边的两端点，x2,y2表示这种情况下要加上的边的两端点。<br/>
第二行输出五个正整数k,x1,y1,x2,y2，其中k表示新树直径的最大值，x1,y1表示这种情况下要去掉的边的两端点，x2,y2表示这种情况下要加上的边的两端点。<br/>
若有多组最优解，输出任意一组。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1 2<br/>
2 3<br/>
2 4<br/>
4 5<br/>
6 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 4 2 2 5<br/>
5 2 1 1 6<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris">鸣谢Claris</a></p></div>

