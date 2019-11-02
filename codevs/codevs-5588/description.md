<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">魔兽世界的西面是红魔军的司令部，东面是蓝魔军的司令部。两个司令部之间是依次排列的若干城市。 </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">红司令部，City 1，City 2，……，City n，蓝司令部</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">两军的司令部都会制造武士。武士一共有 dragon 、ninja、iceman、lion、wolf 五种。每种武士都有编号、生命值、攻击力这三种属性。 </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">双方的武士编号都是从1开始计算。红方制造出来的第n个武士，编号就是n。同样，蓝方制造出来的第n个武士，编号也是n。 </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">武士在刚降生的时候有一个生命值。 </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">在每个整点，双方的司令部中各有一个武士降生。 </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">红方司令部按照iceman、lion、wolf、ninja、dragon的顺序循环制造武士。 </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">蓝方司令部按照lion、dragon、ninja、iceman、wolf的顺序循环制造武士。 </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">制造武士需要生命元。 </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">制造一个初始生命值为m的武士，司令部中的生命元就要减少m个。 </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">如果司令部中的生命元不足以制造某个按顺序应该制造的武士，那么司令部就试图制造下一个。如果所有武士都不能制造了，则司令部停止制造武士。</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">给定一个时间，和双方司令部的初始生命元数目，要求你将从0点0分开始到双方司令部停止制造武士为止的所有事件按顺序输出。</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">一共有两种事件，其对应的输出样例如下： </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">1) 武士降生 </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">输出样例： 004 blue lion 5 born with strength 5,2 lion in red headquarter</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">表示在4点整，编号为5的蓝魔lion武士降生，它降生时生命值为5，降生后蓝魔司令部里共有2个lion武士。（为简单起见，不考虑单词的复数形式）注意，每制造出一个新的武士，都要输出此时司令部里共有多少个该种武士。</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">2) 司令部停止制造武士</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">输出样例： 010 red headquarter stops making warriors</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">表示在10点整，红方司令部停止制造武士</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">输出事件时： </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">首先按时间顺序输出； </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">同一时间发生的事件，先输出红司令部的，再输出蓝司令部的。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">第一行是一个整数，代表测试数据组数。</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">每组测试数据共两行。 </span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">第一行：一个整数M。其含义为， 每个司令部一开始都有M个生命元( 1 &lt;= M &lt;= 10000)。</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">第二行：五个整数，依次是 dragon 、ninja、iceman、lion、wolf 的初始生命值。它们都大于0小于等于10000。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">对每组测试数据，要求输出从0时0分开始，到双方司令部都停止制造武士为止的所有事件。</span><br style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px; white-space: normal; "/><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">对每组测试数据，首先输出&quot;Case:n&quot; n是测试数据的编号，从1开始 。</span><br style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px; white-space: normal; "/><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">接下来按恰当的顺序和格式输出所有事件。每个事件都以事件发生的时间开头，时间以小时为单位，有三位。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: 'Courier New';">1
20
3 4 5 6 7</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: 'Courier New';">Case:1
000 red iceman 1 born with strength 5,1 iceman in red headquarter
000 blue lion 1 born with strength 6,1 lion in blue headquarter
001 red lion 2 born with strength 6,1 lion in red headquarter
001 blue dragon 2 born with strength 3,1 dragon in blue headquarter
002 red wolf 3 born with strength 7,1 wolf in red headquarter
002 blue ninja 3 born with strength 4,1 ninja in blue headquarter
003 red headquarter stops making warriors
003 blue iceman 4 born with strength 5,1 iceman in blue headquarter
004 blue headquarter stops making warriors</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">来源：北京大学程序设计实习</span></p>
</div>
</div>