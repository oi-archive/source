
# Description

<div class="content"><div>给一棵大小为(n&lt;=100000)的树，每个点有权值vi。要求支持以下操作：</div>
<div>子树加、子树对某数取max/min、链加、链对某数取max/min、子树修改、链修改、链权值翻转、子树求和、链求和。输出对10^9+7取模的非负结果即可。</div>
<div>树有根为1。保证输入中的链权值翻转操作的i为j的祖先。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入第一行一个正整数n，第二行n个整数v，第三行到第n+1行每行两个数u、v代表u和v之间有一条边。</div>
<div>接下来一行一个整数(m&lt;=100000)，下面m行每行一个操作。操作格式如下：</div>
<div>SUBADD i v i的子树加上v</div>
<div>SUBMAX i v i的子树对v取max</div>
<div>SUBMIN i v i的子树对v取min</div>
<div>CHAINADD i j v i到j的路径上每个点加上v</div>
<div>CHAINMAX i j v i到j的路径上每个点对v取max</div>
<div>CHAINMIN i j v i到j的路径上每个点对v取min</div>
<div>SUBXGW i v i的子树修改为v</div>
<div>CHAINXGW i j v i到j的路径上每个点修改为v</div>
<div>CHAINREV i j i到j的路径进行权值翻转</div>
<div>SUBQUE i 输出i的子树和</div>
<div>CHAINQUE i j 输出i到j路径上的权值和</div>
<div>操作中所有v和点的初始权值v满足v&lt;=1000000，保证全程不会有点权值超过10^9+7</div>
<p></p></div>

# Output

<div class="content"><p>对于每个求和操作输出一行代表对应权值和。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
-3 -2 1 3 1 -2 0 -5 1 4 <br/>
2 1<br/>
3 1<br/>
4 1<br/>
5 2<br/>
6 4<br/>
7 3<br/>
8 2<br/>
9 3<br/>
10 2<br/>
19<br/>
SUBADD 4 2<br/>
SUBXGW 9 -5<br/>
CHAINQUE 1 1<br/>
SUBQUE 9<br/>
SUBMAX 7 -1<br/>
SUBMIN 10 2<br/>
CHAINQUE 6 9<br/>
SUBQUE 1<br/>
CHAINADD 9 3 4<br/>
CHAINXGW 5 7 5<br/>
CHAINQUE 7 7<br/>
SUBQUE 1<br/>
CHAINMAX 8 7 -5<br/>
CHAINMIN 5 3 4<br/>
CHAINQUE 3 1<br/>
SUBQUE 5<br/>
CHAINREV 1 7<br/>
CHAINQUE 3 2<br/>
SUBQUE 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">1000000004<br/>
1000000002<br/>
1000000005<br/>
1000000001<br/>
5<br/>
26<br/>
8<br/>
4<br/>
13<br/>
4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By DpDarkFantasy">By DpDarkFantasy</a></p></div>

