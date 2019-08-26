
# Description

<div class="content"><div>小L最近沉迷于塞尔达传说：荒野之息（The Legend of Zelda: Breath of The Wild）无法自拔</div>
<div>他尤其喜欢游戏中的迷你挑战。</div>
<div></div>
<div>游戏中有一个叫做“LCT”的挑战，它的规则是这样子的：现在有一个N个点的树（Tree），每条边有一个整数边权</div>
<div>vi，若vi&gt;=0，表示走这条边会获得vi的收益；若vi&lt;0，则表示走这条边需要支付-vi的过路费。小L需要控制主角L</div>
<div>ink切掉（Cut）树上的恰好K条边，然后再连接K条边权为0的边，得到一棵新的树。接着，他会选择树上的两个点p</div>
<div>;q，并沿着树上连接这两点的简单路径从p走到q，并为经过的每条边支付过路费/获取相应收益。海拉鲁大陆之神T</div>
<div>emporaryDO想考验一下Link。他告诉Link，如果Link能切掉合适的边、选择合适的路径从而使总收益-总过路费最</div>
<div>大化的话，就把传说中的大师之剑送给他。小L想得到大师之剑，于是他找到了你来帮忙，请你告诉他，Link能得</div>
<div>到的总收益-总过路费最大是多少。</div></div>

# Input

<div class="content"><div>输入第一行包含两个正整数N;K，保证0&lt;=K&lt;N&lt;=3*10^5</div>
<div>接下来N-1行，每行包含三个整数xi;yi;vi，表示第i条边连接图中的xi;yi两点，它的边权为vi。</div>
<div>1 &lt;= N &lt;= 3 * 10^5</div>
<div>1 &lt;= xi; yi &lt;= N; |vi| &lt;= 10^6</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，表示答案。</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 1<br/>
1 2 3<br/>
2 3 5<br/>
2 4 -3<br/>
4 5 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
一种可能的最优方案为：切掉(2,4,-3) 这条边，连接(3,4,0) 这条边，选择(p,q) = (1; 5)<br/>
</span></div>

# Hint

<div class="content"><p></p><div>请不要提交！数据如下:https://begin.lydsy.com/JudgeOnline/upload/lct.rar</div><br/>
<div>原题面:www.lydsy.com/JudgeOnline/upload/201804/day2(3).pdf</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

