
# Description

<div class="content"><div>Black Vienna是一种牌类推理游戏。有26张不同的牌用’A’-’Z&#39;来表示，其中3张被拿出来放到一边，被称为Bla</div>
<div>ck Vienna Circle。剩下的23张牌被随机地分配给两个玩家（并不要求分均匀，比如可以一个人有23张，另一个人</div>
<div>一张也没有）。现在有n个询问，每次问一个玩家有给定的两张牌中的几张（0,1,2）。询问有多少种满足上述询问</div>
<div>的Black Vienna Circle组合（注意，两个玩家的回答是有可能矛盾的，这时方案数为0）。</div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行有一个整数N(0&lt;=N&lt;=50)，表示询问个数。接下来N行，开头有一个长度为2的字符串（仅包含大写字母）表</div>
<div>示询问哪两张牌紧接着两个整数x，y，分别表示询问哪个玩家，和玩家的回答。</div>
</div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><p>仅一个整数，表示合法的方案数。</p>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1：<br/>
0<br/>
<br/>
样例输入2：<br/>
3<br/>
AB 1 1<br/>
AC 2 1<br/>
BC 2 1<br/>
<br/>
样例输入3：<br/>
3<br/>
AB 1 2<br/>
AC 2 1<br/>
BC 1 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1：<br/>
2600<br/>
<br/>
样例输出2：<br/>
506<br/>
<br/>
样例输出3：<br/>
0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

