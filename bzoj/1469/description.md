
# Description

<div class="content"><div>给你一个由N*N个小方块构成的纸片，且N是2的次幂。每个小方格从左到右，从上到下依次编号。每个小方格只放</div>
<div>入它自己的编号。这张纸片不断地对半折叠，先是上下折叠，还是左右折叠。直到纸片的大小变成了1*1。显然，</div>
<div>折叠后的纸片变成了N*N的一行。我们定义S=&lt;s1,s2,s3...,sp,...,sn*n&gt;,串S由这一行的数字构成，其元素依次为</div>
<div>折叠后的纸片从最下方的元素到最上方的数字值。正在参加无聊会议的IT专家一时兴起开始叠纸片，然后通过上述</div>
<div>方法得到一串字符串。为了打发时间，专家决定找到以下两种问题的答案：</div>
<div>问题类型1：给出一个确定的数字x，问x和字符串S的第几个元素值相同？</div>
<div>问题类型2：给出一个确定的位置p，问字符串中第p个位置上的元素值为？</div>
<div></div></div>

# Input

<div class="content"><div>第一行包括一个数字Q，问题的数量。</div>
<div>接下来的Q行包括3个用空格隔开的数字,T,K,V</div>
<div>T - 表示问题的类型( T = 1 或 2 )</div>
<div>K - 表示纸片的规格N是2^k</div>
<div>V - 如果是问题类型1，则是数字x；如果是问题类型2，则是数字p</div>
<div>1 &lt;= Q &lt;= 10^5</div>
<div>1 &lt;= T &lt;= 2</div>
<div>0 &lt;= K &lt;= 31</div>
<div>1 &lt;= x , p&lt;= N*N ,其中N=2^K</div>
<div></div></div>

# Output

<div class="content"><div>输出应该包含Q行，每行分别为对应问题的答案</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 1 4<br/>
2 2 14<br/>
1 2 16</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
15<br/>
3<br/>
样例解释<br/>
K=1时纸片上的数字为<br/>
1 2<br/>
3 4<br/>
则S=&lt; 1, 3, 4, 2 &gt;<br/>
K=2时纸片上的数字为<br/>
1  2  3  4<br/>
5  6  7  8<br/>
9  10 11 12<br/>
13 14 15 16<br/>
则S=&lt; 1, 13, 16, 4, 8, 12, 9, 5, 6, 10, 11, 7, 3, 15, 14, 2 &gt;</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

