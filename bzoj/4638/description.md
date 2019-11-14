
# Description

<div class="content"><div>一日，BY大神黄犇黄大组长打完羽毛球回来，发现博士正在用魔兽地图编辑器做一个</div>
<div>计算器的软件。</div>
<div>因为最近总是一些取模取模的，所以想非常快速的算出来。简而言之，就是对以下3</div>
<div>个问题进行讨论。</div>
<div>1．给定Y、Z、P，计算的值Y^Z mod P；</div>
<div>2．给定Y、Z、P，计算满足的Y^X ≡ Z (Mod P)最小非负整数。</div>
<div>3．给定Y、Z、P，计算C(z,y) Mod P 的值。（意义为Z中取Y的组合）</div>
<div></div></div>

# Input

<div class="content"><div>
<div>第一行一个正整数N，描述数据组数。</div>
<div>接下来的N行，每行4个正整数Sum，y，z，p。</div>
<div>Sum表述询问类型，如上所述。对于第2种要求，若X不存在，则输出“MathError”</div>
<div>若P不为质数，那么 P=P1^k1 *P2^k2 * …… PL^KL，保证Pi^ki &lt;=10^5</div>
<div>操作数1的操作个数小于501，保证Y,Z,P小于10^9</div>
<div>操作数2的操作个数小于31，保证Y,Z,P小于10^9，而且P为质数</div>
<div>操作数3的操作个数小于31，保证Y,Z,P小于10^7，而且P为质数,P&lt;10^5</div>
</div>
<div>
<div></div>
</div></div>

# Output

<div class="content"><p>要求有N行输出，每行一个整数，为询问的答案</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2 10 1000<br/>
2 3 1 1000<br/>
2 2 3 4<br/>
3 2 7 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">24<br/>
0<br/>
Math Error<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

