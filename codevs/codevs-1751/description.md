<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　小Y和小Z最近迷上了一种叫梭哈的扑克游戏。梭哈又称沙蟹，是英文Show Hand的音译，是一种使用黑桃、红心、梅花、方片的A到K共52张牌(没有大小王）来进行的扑克牌游戏。</span><br><span>　　和其他扑克游戏一样，梭哈的目的是得到最大的牌型并赢得牌局：每名玩家首先需要下基本的注额，之后将获得一张底牌，这张牌只有自己知道。普通梭哈游戏的规则是，在发完底牌后的第一轮时，每个玩家都将得到一张明牌（明牌是摆在台面上的，所有人都能看见），拥有最大明牌的玩家首先发言，他可以下注、不下注（让牌）或盖牌（放弃）也可以全压（梭哈），其他玩家可以跟注（有玩家全压时必须全压）、加注或盖牌（放弃），放弃的玩家将无法继续游戏，并且之前押的筹码无法取回。而全压之后将直接把每个人的手牌补充至5张进行最后的判定；第二圈、第三圈和第四圈的进程与第一圈是类似的。最后，每位玩家要比牌型的大小以确定赢家。牌最大的玩家赢得牌局。</span><br><span>　　所有五张牌的组合，按以下秩序，<strong><em><span style="text-decoration: underline;">由大至小</span></em></strong>排行分为不同牌型：</span><br><span>　　1、<span style="text-decoration: underline;">同花顺（Straight Flush）</span>：同一花色，顺序的牌。 例： Q♦ J♦ 10♦ 9♦ 8♦；</span><br><span>　　2、<span style="text-decoration: underline;">四条（Four of a Kind）</span>：有四张同一点数的牌。 例： 10♣ 10♦ 10♥ 10♠ 9♥；</span><br><span>　　3、<span style="text-decoration: underline;">满堂红（Full House）</span>：三张同一点数的牌，加一对其他点数的牌。 例： 8♣ 8♦ 8♠ K♥ K♠；</span><br><span>　　4、<span style="text-decoration: underline;">同花（Flush）</span>：五张同一花色的牌。 例： A♠ K♠ 10♠ 9♠ 8♠；</span><br><span>　　5、<span style="text-decoration: underline;">顺子（Straight）</span>：五张顺连的牌。 例： K♦ Q♥ J♠ 10♦ 9♦；</span><br><span>　　6、<span style="text-decoration: underline;">三条（Three of a kind）</span>：有三张同一点数的牌。 例： J♣ J♥ J♠ K♦ 9♠；</span><br><span>　　7、<span style="text-decoration: underline;">两对（Two Pairs）</span>：两张相同点数的牌，加另外两张相同点数的牌。 例： A♣ A♦ 8♥ 8♠ Q♠；</span><br><span>　　8、<span style="text-decoration: underline;">一对（One Pair）</span>：两张相同点数的牌。 例： 9♥ 9♠ A♣ J♠ 8♥；</span><br><span>　　9、<span style="text-decoration: underline;">无对（Zilch）</span>：不能排成以上组合的牌，以点数决定大小。例： A♦ Q♦ J♠ 9♣ 8♣。</span><br><span>　　若牌型一样则<span style="text-decoration: underline;"><em><strong>利用点数和花色决定胜负</strong></em></span>。（<span style="text-decoration: underline;"><em><strong>点数</strong></em></span>优先）</span><br><span>　　<strong></strong><span style="text-decoration: underline;"><em><strong>点数的顺序（从大至小）</strong></em></span>为：A&gt;K&gt;Q&gt;J&gt;10&gt;9&gt;8&gt;7&gt;6&gt;5&gt;4&gt;3&gt;2。（注：当5张手牌是5 4 3 2 A的时候，A可以看作最小的牌，此时的牌型仍然为顺子，是顺子里面最小的一个）。</span><br><span>　　<em><strong><span style="text-decoration: underline;">花色的顺序（大至小）</span></strong></em>为：黑桃(♠)&gt;红心(♥)&gt;梅花(♣)&gt;方块(♦)。</span><br><span>　　举例说明：</span><br><span>　　1、Q♦ J♦ 10♦ 9♦ 8♦ &gt; 8♣ 8♥ 8♠ K♥ K♠ （前者牌型为同花顺，比后者大）；</span><br><span>　　2、9♣ 9♦ 9♠ Q♥ Q♠ &gt; 8♣ 8♦ 8♠ K♥ K♠ （两者牌型均为满堂红，比较牌型中三张同一点数的牌9比8大）；</span><br><span>　　3、A♣ A♦ 8♥ 8♠ Q♠ &gt; A♠ A♥ 7♥ 7♠ K♠ （两者牌型均为两对，且最大的对子相同，此时比较次大的对子，8比7大）；</span><br><span>　　4、A♠ Q♠ J♥ 9♥ 8♥ &gt; A♦ Q♦ J♠ 9♣ 8♣ （两者牌型均为无对，所有数码均相同，此时比较最大牌的花色，A♠ &gt; A♦）。</span><br><span>　　5、4♠ 4♥ A♦ Q♦ 5♦ &gt; 4♣ 4♦ A♠ Q♠ 5♠ （两者牌型均为一对，所有数码均相同，此时对4为牌型里最大的部分，因此比较4♠ &gt; 4♣）</span><br><span>　　在小Y和小Z玩梭哈的过程中，小Y总希望能够实时了解目前的形势，即根据自己手上的牌算出自己的胜率。但是他的编程能力有限，你能帮他完成这个任务么？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第一行包含1个正整数N，表示小Y自己手上牌的数量。</span><br><span>　　接下来N行每行用两个整数描述一张小Y手上的牌：第一个数表示牌的数码（1表示A，13表示K，12表示Q，11表示J），第二个数表示牌的花色（1表示黑桃，2表示红心，3表示梅花，4表示方块）。</span><br><span>　　接下来 N – 1行每行用两个整数描述一张小Z手上的明牌：第一个数表示牌的数码（1表示A，13表示K，12表示Q，11表示J），第二个数表示牌的花色（1表示黑桃，2表示红心，3表示梅花，4表示方块）。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　输出一行，格式为A/B形式。A,B为两个互质的自然数，A/B表示了小Y当前局面下的获胜可能性。特别的，若A为0，则应输出0/1。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>5</span><br><span>2 1</span><br><span>2 2</span><br><span>2 3</span><br><span>2 4</span><br><span>3 1</span><br><span>1 1</span><br><span>1 2</span><br><span>1 3</span><br><span>3 2</span></p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>42/43</span></p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　小Y手上牌的牌型是4条，小Z若底牌是方块A则也能构成4条，并通过数码大获胜。其他情况下都是小Y获胜。</span></p>
<p><span><span>　　对于10%的数据，N = 5;</span><br><span>　　对于30%的数据，3 ≤ N ≤ 5;</span><br><span>　　对于100%的数据，1 ≤ N ≤ 5.</span></span></p>
</div>
</div>