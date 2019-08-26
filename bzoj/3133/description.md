
# Description

<div class="content"><p><span style="font-size: medium">有一个装球机器，构造可以看作是一棵树。有下面两种操作：</span></p>
<ul>
    <li><span style="font-size: medium">从根放入一个球，只要下方有空位，球会沿着树滚下。如果同时有多个点可以走，那么会选择编号最小的节点所在路径的方向。比如依次在树根<code>4</code>放2个球，第一个球会落到<code>1</code>，第二个会落到<code>3</code>： </span></li>
    <li><span style="font-size: medium"><img height="204" width="424" alt="" src="source/bzoj/3133/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNC8xKDcpLmpwZw==.jpg"/></span></li>
</ul>
<p></p>
<ul>
    <li><span style="font-size: medium">从某个位置拿走一个球，那么它上方的球会落下来。比如依次拿走<code>5, 7, 8</code>三个球： </span></li>
</ul>
<p><span style="font-size: medium"><img height="351" width="480" alt="" src="source/bzoj/3133/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNC8yKDEpLmpwZw==.jpg"/></span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行：球的个数<code>N</code>，操作个数<code>Q</code> （<code>N, Q &lt;= 100 000</code>）下面<code>N</code>行：第<code>i</code>个节点的父亲。如果是根，则为<code>0</code> 接下来<code>Q</code>行：<code>op num</code></span></p>
<ol>
    <li><span style="font-size: medium"><code>op == 1</code>：在根放入<code>num</code>个球 </span></li>
    <li><span style="font-size: medium"><code>op == 2</code>：拿走在位置<code>num</code>的球 </span></li>
</ol></div>

# Output

<div class="content"><p><span style="font-size: medium">保证输入合法</span></p>
<ol>
    <li><span style="font-size: medium"><code>op == 1</code>：输出最后一个球落到了哪里 </span></li>
    <li><span style="font-size: medium"><code>op == 2</code>：输出拿走那个球后有多少个球会掉下来 </span></li>
</ol></div>

# Sample Input

<div class="content"><span class="sampledata">8 4<br/>
0<br/>
1<br/>
2<br/>
2<br/>
3<br/>
3<br/>
4<br/>
6<br/>
1 8<br/>
2 5<br/>
2 7<br/>
2 8<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
2<br/>
2<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=abcdabcd987提供">abcdabcd987提供</a></p></div>

