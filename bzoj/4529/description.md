
# Description

<div class="content"><div>小强和阿米巴是好朋友。小强要出一套题目。</div>
<div>他的题目以涉及面广（偏）、考察深入（怪）、思维</div>
<div>强度大（难）著称。他为了出题，一共攒了M个本质不同的想法，每个想法形</div>
<div>成了一个题目。不过，他觉得拿这些题目去考察选手会把比赛搞的太过变态，</div>
<div>所以，想请阿米巴来帮忙调整一下他的题目。</div>
<div>阿米巴指出，为了让一场考试的题目的考察点尽量全面，有一个通用的做</div>
<div>法叫做“组合”。如果把两个题目A和B组合在一起，那么组合而成的题目涉</div>
<div>及到的想法的集合就是A涉及到的想法的集合和B涉及到的想法的集合的并。</div>
<div>并且，题目是可以反复组合的。</div>
<div>例如，小强现在有三个想法1,2,3，分别对应了题目P1,P2,P3。</div>
<div>现在，小强把P1和P2组合得到P4。P4涉及的想法的集合是{1,2}。</div>
<div>之后，小强把P2和P3组合得到P5。P5涉及的想法的集合是{2,3}。</div>
<div>最后，小强把P4和P5组合得到P6。P6涉及的想法的集合是{1,2,3}。</div>
<div>现在，小强告诉你每个题目都是如何组合而来的。你要回答的就是，每个</div>
<div>题目涉及的想法的集合有多大。</div>
<div>不过，这个问题是很难的。于是，你只需要能够以比较高的概率回答的比较准确即可。</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个整数N，M，依次表示小强的题目数量和想法的数量</div>
<div>接下来N-M行，每行两个整数，依次表示小强组合出来的题目都是由哪两</div>
<div>个题组合而成的。M个想法对应的题目依次编号为1~M。之后，小强组合出来</div>
<div>的第一个题编号为M+1，组合出来的第二个题编号为M+2，依次类推。</div>
<div>M≤100000,N≤1000000</div>
<div></div></div>

# Output

<div class="content"><p>输出N-M行，每行一个整数表示小强组合出来的每个题都涉及了几个想法。</p>
<div></div>
<div></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
1 2<br/>
2 3<br/>
4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
2<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

