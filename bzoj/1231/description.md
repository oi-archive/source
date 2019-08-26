
# Description

<div class="content"><p><span style="font-size: medium">混乱的奶牛 [Don Piele, 2007] Farmer John的N(4 &lt;= N &lt;= 16)头奶牛中的每一头都有一个唯一的编号S_i (1 &lt;= S_i &lt;= 25,000). 奶牛为她们的编号感到骄傲, 所以每一头奶牛都把她的编号刻在一个金牌上, 并且把金牌挂在她们宽大的脖子上. 奶牛们对在挤奶的时候被排成一支&#34;混乱&#34;的队伍非常反感. 如果一个队伍里任意两头相邻的奶牛的编号相差超过K (1 &lt;= K &lt;= 3400), 它就被称为是混乱的. 比如说，当N = 6, K = 1时, 1, 3, 5, 2, 6, 4 就是一支&#34;混乱&#34;的队伍, 但是 1, 3, 6, 5, 2, 4 不是(因为5和6只相差1). 那么, 有多少种能够使奶牛排成&#34;混乱&#34;的队伍的方案呢? </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第 1 行: 用空格隔开的两个整数N和K </span></p>
<p><span style="font-size: medium">* 第 2..N+1 行: 第i+1行包含了一个用来表示第i头奶牛的编号的整数: S_i </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">第 1 行: 只有一个整数, 表示有多少种能够使奶牛排成&#34;混乱&#34;的队伍的方案. 答案保证是 一个在64位范围内的整数. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1<br/>
3<br/>
4<br/>
2<br/>
1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
输出解释:<br/>
<br/>
两种方法分别是:<br/>
3 1 4 2<br/>
2 4 1 3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

