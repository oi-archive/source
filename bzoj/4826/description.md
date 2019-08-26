
# Description

<div class="content"><div>影魔,奈文摩尔,据说有着一个诗人的灵魂。事实上,他吞噬的诗人灵魂早已成千上万。千百年来,他收集了各式各样</div>
<div>的灵魂,包括诗人、牧师、帝王、乞丐、奴隶、罪人,当然,还有英雄。每一个灵魂,都有着自己的战斗力,而影魔,靠</div>
<div>这些战斗力提升自己的攻击。奈文摩尔有 n 个灵魂,他们在影魔宽广的体内可以排成一排,从左至右标号 1 到 n。</div>
<div>第 i个灵魂的战斗力为 k[i],灵魂们以点对的形式为影魔提供攻击力,对于灵魂对 i,j(i&lt;j)来说,若不存在 k[s](i</div>
<div>&lt;s&lt;j)大于 k[i]或者 k[j],则会为影魔提供 p1 的攻击力(可理解为:当 j=i+1 时,因为不存在满足 i&lt;s&lt;j 的 s,从</div>
<div>而 k[s]不存在,这时提供 p1 的攻击力;当 j&gt;i+1 时,若max{k[s]|i&lt;s&lt;j}&lt;=min{k[i],k[j]} , 则 提 供 p1 的 攻</div>
<div> 击 力 ); 另 一 种 情 况 , 令 c 为k[i+1],k[i+2],k[i+3]......k[j-1]的最大值,若 c 满足:k[i]&lt;c&lt;k[j],或</div>
<div>者 k[j]&lt;c&lt;k[i],则会为影魔提供 p2 的攻击力,当这样的 c 不存在时,自然不会提供这 p2 的攻击力;其他情况的</div>
<div>点对,均不会为影魔提供攻击力。影魔的挚友噬魂鬼在一天造访影魔体内时被这些灵魂吸引住了,他想知道,对于任</div>
<div>意一段区间[a,b],1&lt;=a&lt;b&lt;=n,位于这些区间中的灵魂对会为影魔提供多少攻击力,即考虑 所有满足a&lt;=i&lt;j&lt;=b 的灵</div>
<div>魂对 i,j 提供的攻击力之和。顺带一提,灵魂的战斗力组成一个 1 到 n 的排列:k[1],k[2],...,k[n]。</div></div>

# Input

<div class="content"><div>第一行 n,m,p1,p2</div>
<div>第二行 n 个数:k[1],k[2],...,k[n]</div>
<div>接下来 m 行,每行两个数 a,b,表示询问区间[a,b]中的灵魂对会为影魔提供多少攻击力。</div>
<div>1 &lt;= n,m &lt;= 200000;1 &lt;= p1,p2 &lt;= 1000</div></div>

# Output

<div class="content"><div>共输出 m 行,每行一个答案,依次对应 m 个询问。</div></div>

# Sample Input

<div class="content"><span class="sampledata">10 5 2 3 <br/>
7 9 5 1 3 10 6 8 2 4 <br/>
1 7 <br/>
1 9 <br/>
1 3 <br/>
5 9<br/>
1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">30<br/>
39<br/>
4<br/>
13<br/>
16<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

