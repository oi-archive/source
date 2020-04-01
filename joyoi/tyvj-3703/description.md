# 

 
 # 题目描述 
<p>小&nbsp;Y&nbsp;和小&nbsp;Z&nbsp;最近迷上了一种叫梭哈的扑克游戏。梭哈又称沙蟹，是英文&nbsp;Show&nbsp;Hand&nbsp;的音译，是一种使用黑桃、红心、梅花、方片的&nbsp;A&nbsp;到&nbsp;K&nbsp;共&nbsp;52&nbsp;张牌(没有大小王）来进行的扑克牌游戏。&nbsp;</p>

<p>和其他扑克游戏一样，梭哈的目的是得到最大的牌型并赢得牌局：每名玩家首先需要下基本的注额，之后将获得一张底牌，这张牌只有自己知道。普通梭哈游戏的规则是，在发完底牌后的第一轮时，每个玩家都将得到一张明牌（明牌是摆在台面上的，所有人都能看见），拥有最大明牌的玩家首先发言，他可以下注、不下注（让牌）或盖牌（放弃）也可以全压（梭哈），其他玩家可以跟注（有玩家全压时必须全压）、加注或盖牌（放弃），放弃的玩家将无法继续游戏，并且之前押的筹码无法取回。而全压之后将直接把每个人的手牌补充至&nbsp;5&nbsp;张进行最后的判定；第二圈、第三圈和第四圈的进程与第一圈是类似的。最后，每位玩家要比牌型的大小以确定赢家。牌最大的玩家赢得牌局。&nbsp;</p>

<p>所有五张牌的组合，按以下秩序，由大至小排行分为不同牌型：&nbsp;</p>

<ol>
	<li>同花顺（Straight&nbsp;Flush）：同一花色，顺序的牌。&nbsp;例：&nbsp;Q&diams;&nbsp;J&diams;&nbsp;10&diams;&nbsp;9&diams;&nbsp;8&diams;；&nbsp;</li>
	<li>四条（Four&nbsp;of&nbsp;a&nbsp;Kind）：有四张同一点数的牌。&nbsp;例：&nbsp;10&clubs;&nbsp;10&diams;&nbsp;10&hearts;&nbsp;10&spades;&nbsp;9&hearts;；&nbsp;</li>
	<li>满堂红（&nbsp;Full&nbsp;House&nbsp;）：三张同一点数的牌，加一对其他点数的牌。&nbsp;例：&nbsp;8&clubs;&nbsp;8&diams;&nbsp;8&spades;&nbsp;K&hearts;&nbsp;K&spades;；&nbsp;</li>
	<li>同花（Flush）：五张同一花色的牌。&nbsp;例：&nbsp;A&spades;&nbsp;K&spades;&nbsp;10&spades;&nbsp;9&spades;&nbsp;8&spades;；&nbsp;</li>
	<li>顺子（Straight）：五张顺连的牌。&nbsp;例：&nbsp;K&diams;&nbsp;Q&hearts;&nbsp;J&spades;&nbsp;10&diams;&nbsp;9&diams;；&nbsp;</li>
	<li>三条（Three&nbsp;of&nbsp;a&nbsp;kind）：有三张同一点数的牌。&nbsp;例：&nbsp;J&clubs;&nbsp;J&hearts;&nbsp;J&spades;&nbsp;K&diams;&nbsp;9&spades;；&nbsp;</li>
	<li>两对（Two&nbsp;Pairs&nbsp;）：两张相同点数的牌，加另外两张相同点数的牌。&nbsp;例：&nbsp;A&clubs;&nbsp;A&diams;&nbsp;8&hearts;&nbsp;8&spades;&nbsp;Q&spades;；&nbsp;</li>
	<li>一对（One&nbsp;Pair）：两张相同点数的牌。&nbsp;例：&nbsp;9&hearts;&nbsp;9&spades;&nbsp;A&clubs;&nbsp;J&spades;&nbsp;8&hearts;；&nbsp;</li>
	<li>无对（Zilch）：不能排成以上组合的牌，以点数决定大小。例：&nbsp;A&diams;&nbsp;Q&diams;&nbsp;J&spades;&nbsp;9&clubs;&nbsp;8&clubs;。&nbsp;</li>
</ol>

<p>若牌型一样则利用点数和花色决定胜负。（点数优先）&nbsp;</p>

<p>点数的顺序（从大至小）为：A&gt;K&gt;Q&gt;J&gt;10&gt;9&gt;8&gt;7&gt;6&gt;5&gt;4&gt;3&gt;2。（注：当&nbsp;5张手牌是&nbsp;5&nbsp;4&nbsp;3&nbsp;2&nbsp;A&nbsp;的时候，A&nbsp;可以看作最小的牌，此时的牌型仍然为顺子，是顺子里面最小的一个）。&nbsp;</p>

<p>花色的顺序（大至小）为：黑桃(&spades;)&gt;红心(&hearts;)&gt;梅花(&clubs;)&gt;方块(&diams;)。&nbsp;</p>

<p>举例说明：&nbsp;<br />
1、Q&diams;&nbsp;J&diams;&nbsp;10&diams;&nbsp;9&diams;&nbsp;8&diams;&nbsp;&gt;&nbsp;8&clubs;&nbsp;8&hearts;&nbsp;8&spades;&nbsp;K&hearts;&nbsp;K&spades;&nbsp;（前者牌型为同花顺，比后者大）；&nbsp;</p>

<p>2、9&clubs;&nbsp;9&diams;&nbsp;9&spades;&nbsp;Q&hearts;&nbsp;Q&spades;&nbsp;&gt;&nbsp;8&clubs;&nbsp;8&diams;&nbsp;8&spades;&nbsp;K&hearts;&nbsp;K&spades;&nbsp;（两者牌型均为满堂红，比较牌型中<br />
三张同一点数的牌&nbsp;9&nbsp;比&nbsp;8&nbsp;大）；&nbsp;</p>

<p>3、A&clubs;&nbsp;A&diams;&nbsp;8&hearts;&nbsp;8&spades;&nbsp;Q&spades;&nbsp;&gt;&nbsp;A&spades;&nbsp;A&hearts;&nbsp;7&hearts;&nbsp;7&spades;&nbsp;K&spades;&nbsp;（两者牌型均为两对，且最大的对子相同，此时比较次大的对子，8&nbsp;比&nbsp;7&nbsp;大）；&nbsp;</p>

<p>4、A&spades;&nbsp;Q&spades;&nbsp;J&hearts;&nbsp;9&hearts;&nbsp;8&hearts;&nbsp;&gt;&nbsp;A&diams;&nbsp;Q&diams;&nbsp;J&spades;&nbsp;9&clubs;&nbsp;8&clubs;&nbsp;（两者牌型均为无对，所有数码均相同，此时比较最大牌的花色，A&spades;&nbsp;&gt;&nbsp;A&diams;）。&nbsp;</p>

<p>5、4&spades;&nbsp;4&hearts;&nbsp;A&diams;&nbsp;Q&diams;&nbsp;5&diams;&nbsp;&gt;&nbsp;4&clubs;&nbsp;4&diams;&nbsp;A&spades;&nbsp;Q&spades;&nbsp;5&spades;&nbsp;（两者牌型均为一对,<span style="line-height: 20.8px;">所有数码均相同，</span>此时对&nbsp;4&nbsp;为牌型里最大的部分，因此比较&nbsp;4&spades;&nbsp;&gt;&nbsp;4&clubs;）&nbsp;</p>

<p>在小&nbsp;Y&nbsp;和小&nbsp;Z&nbsp;玩梭哈的过程中，小&nbsp;Y&nbsp;总希望能够实时了解目前的形势，即根据自己手上的牌算出自己的胜率。但是他的编程能力有限，你能帮他完成这个任务么？&nbsp;</p> 

 
 # 输入格式 
<p>第一行包含&nbsp;1&nbsp;个正整数&nbsp;N，表示小&nbsp;Y&nbsp;自己手上牌的数量。&nbsp;</p>

<p>接下来&nbsp;N&nbsp;行每行用两个整数描述一张小&nbsp;Y&nbsp;手上的牌：第一个数表示牌的数码（1&nbsp;表示&nbsp;A，13&nbsp;表示&nbsp;K，12&nbsp;表示&nbsp;Q，11&nbsp;表示&nbsp;J），第二个数表示牌的花色（1表示黑桃，2&nbsp;表示红心，3&nbsp;表示梅花，4&nbsp;表示方块）。&nbsp;</p>

<p>接下来&nbsp;N&nbsp;&ndash;&nbsp;1&nbsp;行每行用两个整数描述一张小&nbsp;Z&nbsp;手上的明牌：第一个数表示牌的数码（1&nbsp;表示&nbsp;A，13&nbsp;表示&nbsp;K，12&nbsp;表示&nbsp;Q，11&nbsp;表示&nbsp;J），第二个数表示牌的花色（1&nbsp;表示黑桃，2&nbsp;表示红心，3&nbsp;表示梅花，4&nbsp;表示方块）。&nbsp;</p> 

 
 # 输出格式 
<p>输出文件&nbsp;showhand.out&nbsp;仅包含一行，格式为&nbsp;A/B&nbsp;形式。A,B&nbsp;为两个互质的自然数，A/B&nbsp;表示了小&nbsp;Y&nbsp;当前局面下的获胜可能性。特别的，若&nbsp;A&nbsp;为&nbsp;0，则应输出&nbsp;0/1。&nbsp;</p> 

 
 # 提示 
<h3>样例说明</h3>

<p>小&nbsp;Y&nbsp;手上牌的牌型是&nbsp;4&nbsp;条，小&nbsp;Z&nbsp;若底牌是方块&nbsp;A&nbsp;则也能构成&nbsp;4&nbsp;条，并通过数码大获胜。其他情况下都是小&nbsp;Y&nbsp;获胜。&nbsp;</p>

<h3>数据范围</h3>

<p>对于&nbsp;10%的数据，N&nbsp;=&nbsp;5;&nbsp;</p>

<p>对于&nbsp;30%的数据，3&nbsp;&le;&nbsp;N&nbsp;&le;&nbsp;5;&nbsp;&nbsp;</p>

<p>对于&nbsp;100%的数据，1&nbsp;&le;&nbsp;N&nbsp;&le;&nbsp;5.&nbsp;</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>5
2 1
2 2
2 3
2 4
3 1
1 1
1 2
1 3
3 2
</td><td>42/43</td></tr></table>
