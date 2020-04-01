
# Description

<div class="content"><p><img height="564" width="773" alt="" src="/source/bzoj/3266/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwOC8xKDMpLmpwZw==.jpg"/></p></div>

# Input

<div class="content"><div>第一行有三个整数V,E,P</div>
<div>接下来E行，每行四个整数x,y,a,b分别表示x与y有一无向边，</div>
<div>a(x,y)=a,b(x,y)=b。显然根据题意默认a(y,x)=-a</div>
<div>b(y,x)=b。输入数据保证没有自环和重边。</div>
<div>V&lt;=100,E&lt;=2000,P&lt;=10^18</div></div>

# Output

<div class="content"><div>一共E行，按输入数据给定边的顺序，输出最小的大于等于零的C(x,y)值。</div>
<div>很显然c(y,x)=-c(x,y) mod p.但是不需要输出c(y,x)</div>
<div>如果无解，输出-1</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 7<br/>
1 2 15 -6<br/>
2 3 22 8<br/>
3 1 1 -69</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 fzszzy制作数据">鸣谢 fzszzy制作数据</a></p></div>

