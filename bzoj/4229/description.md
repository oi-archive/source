
# Description

<div class="content"><div>现在，我想知道自己是否还有选择。</div>
<div>给定n个点m条边的无向图以及顺序发生的q个事件。</div>
<div>每个事件都属于下面两种之一：</div>
<div>1、删除某一条图上仍存在的边</div>
<div>2、询问是否存在两条边不相交的路径可以从点u出发到点v</div>
<p></p></div>

# Input

<div class="content"><div>第一行三个整数n,m,q</div>
<div>接下来m行，每行两个整数u,v，表示u和v之间有一条边</div>
<div>接下来q行，每行一个大写字母o和2个整数u、v，依次表示按顺序发生的q个事件：</div>
<div>当o为’Z’时，表示删除一条u和v之间的边</div>
<div>当o为’P’时，表示询问是否存在两条边不相交的路径可以从点u出发到点v</div>
<p></p></div>

# Output

<div class="content"><div>对于每组询问，如果存在，输出Yes,否则输出No</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 8 7<br/>
1 2<br/>
1 3<br/>
1 4<br/>
2 3<br/>
3 4<br/>
3 7<br/>
7 4<br/>
5 6<br/>
Z 1 4<br/>
P 1 3<br/>
P 2 4<br/>
Z 1 3<br/>
P 1 3<br/>
Z 6 5<br/>
P 5 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
Yes<br/>
No<br/>
No</span></div>

# Hint

<div class="content"><p></p><div>对于全部数据，max(n,m,q)&lt;=100000</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

