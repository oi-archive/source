# 题目描述


<p class="MsoNormal">
	<span style="font-family:宋体;"><b>【问题描述</b>】 </span> 
</p>
<p>
	<span class="MsoNormal"></span>在这个题目里，你将要模拟一个著名的疯狂西部主题纸牌游戏，它的名字叫“BANG”。这个游戏适合4到7个人围在一起玩，它之所以出名，部分原因是因为太复杂。不过别担心，你要模拟的只是它的简化版。<br/>
在我们这个版本的游戏里只有两个玩家，假定他们的名字是Iamcs和Peipei，开始时每人的生命值都是4。有一堆洗好的牌面朝下放在桌上，两个玩家从上往下摸牌，每人摸牌的张数跟自己的生命值相同（比如，Iamcs摸到最上面的4张牌，而Peipei摸走了接下来的4张牌），然后游戏开始，两个人轮流进行，Iamcs先来，轮到某个玩家时，他要进行如下三步：<br/>
（1）从牌堆最上面摸两张牌；<br/>
（2）打出去一些牌；<br/>
（3）丢弃一些牌，使得自己手里的牌数不超过自己的生命值。<br/>
在“BANG”纸牌游戏中，对于打出去或丢弃的任一张牌，不外乎下面几种类型，每一种都有它们自己的功能，详细如下：<br/>
Bang：你（出牌的人）向对手射击，如果对手未能成功防御（即刻打出Miss牌），则会被子弹击中，丢掉一分。每次轮到你时，最多只能出一张这种牌。<br/>
Grenade：你的对手必须立即出一张Miss牌，否则他将丢一分。<br/>
Ghost：你的对手必须立即丢弃一张Bang牌，否则他将丢一分。<br/>
Knife：你的对手立即丢掉一分。<br/>
Miss：当轮到你出牌时，不能出这种牌，它唯一的用途是来防御，避免中弹。<br/>
Parry：当轮到你出牌时，不能出这种牌，但是当你不得不出一张Miss牌时，你也可以同时出一张这种牌用做防御，每出一次这种牌，你必须立即从牌堆最上面摸一张牌来。<br/>
当某个玩家丢掉了所有的生命值就算输，整个游戏过程中，每一个玩家都必须遵守下面的策略：<br/>
a)轮到某个玩家时，他必须尽可能多地出牌；<br/>
b)当对手出了一张Bang或Ghost或Grenade牌时，只要他手里有，他必须出特定的那种牌；<br/>
c)Ghost牌要优先于其它牌出；<br/>
d)Parry牌要优先于Miss牌出；<br/>
e)如果必须要丢弃一些牌，则优先丢掉Bang牌，其次是Miss，最后是Parry牌。<br/>
<br/>
【输入格式】<br/>
<br/>
输入文件包含至少40组测试数据，每个数据有多行组成，表示这堆牌中的每一张，从上到下排列，每个测试数据以一行&#34;===&#34;（3个等号）表示结束，整个输入文件以一行单独的一个句点(.)表示结束。<br/>
输入数据保证有足够的牌使得游戏结束。
</p>
<p>
	【输出格式】
</p>
<p class="MsoNormal">
	  对于每个测试数据，如果第一个摸牌的人（比如Iamcs）赢了或者输了，则相应地在一行输出&#34;WIN&#34;或&#34;LOSE&#34;。
</p>
<p class="MsoNormal">
	【样例】
</p>
<p class="MsoNormal">
	bang.in<br/>
Bang<br/>
Bang<br/>
Bang<br/>
Bang<br/>
Parry<br/>
Bang<br/>
Ghost<br/>
Knife<br/>
Bang<br/>
Bang<br/>
Grenade<br/>
Miss<br/>
Grenade<br/>
===<br/>
.
</p>
<p>
	bang.out<br/>
LOSE
</p>
