<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>众所周知，麻将是我们国家的国粹。这段时间，小D也迷上了麻将这个老少皆宜的游戏。<br>小D觉得这些不同规则的麻将太麻烦了，所以他集合了很多种麻将规则创造出了一套D麻将。下面是D麻将的几个特点：<br>D麻将中有三种花色，万（w）索（s）筒（t），每个花色下有9张牌，每张牌有4个。<br>D麻将中没有杠牌，只有顺子和刻子。顺子的含义是相同花色的三张连在一起的牌型（比如说2w3w4w）；刻子的含义是三张花色和数字都相同的牌型（比如说2s2s2s）。<br>D麻将的胡牌的时候手上往往有14张牌，14张牌凑成了四个顺子或刻子和两张一样的牌做雀头就可以胡牌了。<br>D麻将胡牌的时候有很多种不同的牌型，不同的牌型会有不一样的番数。你的一种牌型可能满足了多个加番牌型，满足多个的情况下就把所有满足的牌型的番数全部加起来计算。<br>D麻将中有如下牌型可以加番：<br>平和（一番）：4个顺子组成；<br>断幺九（一番）：胡牌的时候手上只有2-8的数字组成的牌型；<br>一杯口（一番）：同花色同数值的顺子两组；<br>混全带幺九（一番）：全部的顺子，刻子中都含有数字1或9；<br>三色同顺（一番）：三种花色同数值的顺子各一组；<br>一气贯通（一番）：由同花色一至九组成顺子；<br>一色三顺（两番）：同花色同数值顺子三组；<br>对对和（两番）：四组刻子；<br>两杯口（三番）：由两组不同的一杯口组成；<br>三色同刻（三番）：三种花色同数值的刻子各一组；<br>清一色（六番）：全部由同一种花色的顺子，刻子及雀头组成；<br>清老头（六番）：全部由1或9的刻子和雀头组成；<br>比如说一个牌型为1s2s3s4s5s6s7s8s9s1s2s3s9s9s的牌，它满足了平和、一杯口、一气贯通、清一色四个牌型，所以它的番数是9番。<br>小D希望为D麻将做一个程序来帮忙判断这个牌型的番数是多少。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行一个测试组数T。<br>接下来T行每行一个字符串s，表示需要判断番数的牌型。length(s)=28</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出有T行每行一个整数，表示判断牌型的番数为多少。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1<br>1s2s3s4s5s6s7s8s9s1s2s3s9s9s</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>T&lt;=10</p>
</div>
</div>