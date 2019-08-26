
# Description

<div class="content"><div>Chandra 是一个魔法天才。</div>
<div>从一岁时接受火之教会洗礼之后， Chandra 就显示出对火元素无与伦比的亲和力，轻而易举地学会种种晦涩难解</div>
<div>的法术。这也多亏 Chandra 有着常人难以企及的语言天赋，让她能轻松流利地说出咒语中那些极其拗口的魔法词</div>
<div>汇。直到十四岁，开始学习威力强大的禁咒法术时， Chandra 才遇到了障碍。根据火之魔法规则，禁咒的构成单</div>
<div>位是 N 个基本词汇。施法时只要凝聚精神力，说出一段用这些词语组成的长度恰好等于 L 的语言，就能释放威力</div>
<div>超乎想象的火法术。过去的魔法师们总结了几种表达起来最连贯的组合方式，方便施法者以最快语速完成法术。但</div>
<div>具有魔法和语言双重天才的 Chandra 不满足于这几种流传下来的禁咒，因为她可以毫无困难地说出普通人几乎不</div>
<div>可能表达的禁咒语句。然而，在实际施法时， Chandra 发现有些自创禁咒念出后不但没有预期效果，反而会使自</div>
<div>己的精神力迅速枯竭，十分难受。这个问题令 Chandra 万分不解。她大量阅读典籍，到处走访魔法学者，并且不</div>
<div>顾精神折磨一次又一次尝试新咒语，希望找出问题的答案。很多年过去了，在一次远古遗迹探险中， Chandra 意</div>
<div>外闯进了火之神艾利克斯的不知名神殿。根据岩土特征分析，神殿应该有上万年的历史，这是极其罕见的。 Chand</div>
<div>ra 小心翼翼地四处探索，沿着魔力流动来到一间密室。她看见密室中央悬浮着一本书籍。在魔法保护下书籍状况</div>
<div>完好。精通上古语言的 Chandra 读过此书，终于解开了多年的困惑。禁咒法术之所以威力强大，是因为咒语借用</div>
<div>了火之神艾利克斯的神力。这本书里记载了艾利克斯生平忌讳的 M 个词语，比如情敌的名字、讨厌的植物等等。</div>
<div>使用禁咒法术时，如果语言中含有任何忌讳词语，就会触怒神力而失效，施法者也一并遭受惩罚。例如，若 ”ban</div>
<div>ana” 是唯一的忌讳词语， “an”、 ”ban”、 ”analysis” 是基本词汇，禁咒长度须是 11， 则“bananalys</div>
<div>is” 是无效法术， ”analysisban”、 ”anbanbanban”是两个有效法术。注意：一个基本词汇在禁咒法术中可</div>
<div>以出现零次、 一次或多次；只要组成方式不同就认为是不同的禁咒法术，即使书写形式相同。谜题破解， Chandr</div>
<div>a 心情大好。她决定计算一共有多少种有效的禁咒法术。由于答案可能很大，你只需要输出答案模 1,000,000,007</div>
<div> 的结果。</div></div>

# Input

<div class="content"><div>第一行，三个正整数 N, M, L。</div>
<div>接下来 N 行，每行一个只含小写英文字母的字符串，表示一个基本词汇。</div>
<div>接下来 M 行，每行一个只含小写英文字母的字符串，表示一个忌讳词语。</div>
<div><span style="font-family: arial, verdana, helvetica, sans-serif; background-color: rgb(215, 235, 255);">对于60%的数据1&lt;=N,M&lt;=50,L&lt;=100</span><br style="font-family: arial, verdana, helvetica, sans-serif; background-color: rgb(215, 235, 255);"/>
<span style="font-family: arial, verdana, helvetica, sans-serif; background-color: rgb(215, 235, 255);">对于另40%数据基本词汇长度不超过2,L&lt;=10^8</span></div></div>

# Output

<div class="content"><div>仅一行，一个整数，表示答案（模 10^9+7）。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 2 10<br/>
boom<br/>
oo<br/>
ooh<br/>
bang<br/>
ob<br/>
mo</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
【样例解释 】<br/>
有效的禁咒法术共有 14 种：boom/bang/oo，oo/oo/oo/oo/oo，oo/oo/ooh/ooh，<br/>
oo/ooh/oo/ooh， oo/ooh/ooh/oo， ooh/oo/oo/ooh， ooh/oo/ooh/oo，<br/>
ooh/ooh/boom， ooh/ooh/oo/oo， ooh/ooh/bang， ooh/bang/ooh，<br/>
bang/oo/oo/oo， bang/ooh/ooh， bang/bang/oo。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

