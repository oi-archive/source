
# Description

<div class="content"><p>你的任务是计算一个函数F(x, y)，其中x和y是两个正整数序列。F的定义如下： boolean F(x, y) if W(x) ≠ W(y) then return 0 else if |W(x)| = |W(y)| = 1 then return 1 else return F(p(x), p(y))  and  F(s(x), s(y)). W(x)表示序列x中元素的集合。（元素的顺序和出现次数将被无视） p(x)表示序列x的最长前缀，满足：W(x) ≠ W(p(x)) s(x)表示序列x的最长后缀。满足：W(x) ≠ W(s(x)) |Z|表示集合Z中元素个数</p></div>

# Input

<div class="content"><p>第一行k表示数据组数。对于每组数据，第一行n,m分别表示x序列的长度与y序列的长度，第二行n个数表示xi，第三行m个数表示yi 1&lt;=k&lt;=13 1&lt;=n,m&lt;=100000 1&lt;=xi,yi&lt;=100</p></div>

# Output

<div class="content"><p>k行，对于每组数据，若F(x,y)为真输出1，否则输出0。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
4 5<br/>
3 1 2 1<br/>
1 3 1 2 1<br/>
7 7<br/>
1 1 2 1 2 1 3<br/>
1 1 2 1 3 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1</span></div>

# Hint

<div class="content"><p></p><p>感谢MT大牛贡献译文.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

