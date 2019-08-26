
# Description

<div class="content"><div>【故事背景】</div>
<div>JSOI王国的地铁又涨价了！正在JSOI旅游的JYY非常不开心L。这次票价改革后，乘客并不是按照乘坐的距离收费，</div>
<div>而是按照换乘次数进行收费的！JYY也要按此更新他的线路搜索软件了。JYY心想，在支付同样票价的前提下，岂不</div>
<div>是坐的站数越多，自己就赚的越多嘛！于是JYY希望开发一个线路搜索软件，使得自己总能够“赚”的最多！JSOI</div>
<div>地铁一共有N条线路S个车站。第i条地铁线路包含Li个站。所有地铁线路都是一条从首发站到终点站的直线型线路</div>
<div>（不存在例如北京地铁2号线或者10号线那样奇葩的环线）。同时，每一条地铁线路都是双向运行的。如果有不同</div>
<div>的线路经过同一个地铁站，那么乘客就可以在那个地铁站进行换乘。根据JSOI地铁的最新收费方式，每当乘客进入</div>
<div>一列正在运行的地铁列车，都需要支付1的费用。因此，假设乘客一共换乘了x次，那么就需要总共支付x+1的乘车</div>
<div>费用。由于地铁线路都是双向运行的，因此在任意一站都可以换乘该线地铁反方向运行的列车。不过，需要注意的</div>
<div>是，即使是换乘同样线路的反方向列车，也是需要付费的（因为总是需要先下车，再重新上车的）。JYY现在要从A</div>
<div>站坐地铁前往B站。假设对于任意一条地铁线路，相邻两站间地铁的运行时间均为1分钟，并且列车停站和换乘均不</div>
<div>耗时间，JYY想知道</div>
<div>1)他最少需要支付的票价是多少钱；</div>
<div>2)在支付最少票价的前提下，他最多可以乘坐多少分钟的地铁。</div></div>

# Input

<div class="content"><div>第一行包含两个正整数N和S；</div>
<div>第二行包含S个由空格隔开的字符串，表示S个站点的站名；每个字符串长度不超过40，</div>
<div>并且仅包含字母，数字，以及横线‘-’；</div>
<div>接下来N行，每行描述一条地铁线路；</div>
<div>对于其中第i行，首先包含一个正整数Li，接下来Li个字符串，表示这条地</div>
<div>铁线路上的站点名称；一条线路允许多次停靠同一个站点。</div>
<div>第N+3行，包含两个不同的字符串A和B，表示JYY目前在A站，希望坐地铁前往B站。</div>
<div>2&lt;=N&lt;=50,000,S&lt;=3?10N,Sigma(iLi)&lt;=8*10^5</div></div>

# Output

<div class="content"><p>第一行包含一个整数C，表示JYY最少需要支付的乘车费用；<br/>
第二行包含一个整数T，表示JYY在花费C的前提下，可以乘坐地铁的最长时间。<br/>
如果不存在两个站点之间的路线，第一行输出“-1”，第二行输出“0”（均不包含引号）。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 5 <br/>
A B C D E <br/>
4 A B C D <br/>
3 C D E <br/>
A D </span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

