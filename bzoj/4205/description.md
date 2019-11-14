
# Description

<div class="content"><div>现在有一种卡牌游戏，每张卡牌上有三个属性值：A,B,C。把卡牌分为X,Y两类，分别有n1,n2张。</div>
<div>两张卡牌能够配对，当且仅当，存在至多一项属性值使得两张卡牌该项属性值互质，且两张卡牌类别不同。</div>
<div>比如一张X类卡牌属性值分别是225,233,101，一张Y类卡牌属性值分别为115,466,99。那么这两张牌是可以配对的，因为只有101和99一组属性互质。</div>
<div>游戏的目的是最大化匹配上的卡牌组数，当然每张卡牌只能用一次。</div>
<p></p></div>

# Input

<div class="content"><div>数据第一行两个数n1，n2，空格分割。</div>
<div>接下来n1行，每行3个数，依次表示每张X类卡牌的3项属性值。</div>
<div>接下来n2行，每行3个数，依次表示每张Y类卡牌的3项属性值。</div>
<p></p></div>

# Output

<div class="content"><div>输出一个整数：最多能够匹配的数目。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
2 2 2<br/>
2 5 5<br/>
2 2 5<br/>
5 5 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
【提示】<br/>
样例中第一张X类卡牌和第一张Y类卡牌能配对，第二张X类卡牌和两张Y类卡牌都能配对。所以最佳方案是第一张X和第一张Y配对，第二张X和第二张Y配对。<br/>
另外，请大胆使用渐进复杂度较高的算法！</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据，n1,n2≤ 30000，属性值为不超过200的正整数</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

