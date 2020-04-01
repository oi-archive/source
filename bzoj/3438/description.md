
# Description

<div class="content"><div>小M在MC里开辟了两块巨大的耕地A和B（你可以认为容量是无穷），现在，小P有n中作物的种子，每种作物的种子</div>
<div>有1个（就是可以种一棵作物）（用1...n编号），现在，第i种作物种植在A中种植可以获得ai的收益，在B中种植</div>
<div>可以获得bi的收益，而且，现在还有这么一种神奇的现象，就是某些作物共同种在一块耕地中可以获得额外的收益</div>
<div>，小M找到了规则中共有m种作物组合，第i个组合中的作物共同种在A中可以获得c1i的额外收益，共同总在B中可以</div>
<div>获得c2i的额外收益，所以，小M很快的算出了种植的最大收益，但是他想要考考你，你能回答他这个问题么？</div>
<p></p></div>

# Input

<div class="content"><div>第一行包括一个整数n</div>
<div>第二行包括n个整数，表示ai第三行包括n个整数，表示bi第四行包括一个整数m接下来m行，</div>
<div>对于接下来的第i行：第一个整数ki，表示第i个作物组合中共有ki种作物，</div>
<div>接下来两个整数c1i，c2i，接下来ki个整数，表示该组合中的作物编号。输出格式</div></div>

# Output

<div class="content"><p>只有一行，包括一个整数，表示最大收益</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
4 2 1<br/>
2 3 2<br/>
1<br/>
2 3 2 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
样例解释A耕地种1，2，B耕地种3，收益4+2+3+2=11。<br/>
1&lt;=k&lt; n&lt;= 1000,0 &lt; m &lt; = 1000 保证所有数据及结果不超过2*10^9。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Kpmcup#0 By Greens">Kpmcup#0 By Greens</a></p></div>

