<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">大佬TYZ最近迷上了一种游戏——24点，游戏规则是给你4张扑克牌，你需要通过加减乘除四则运算及括号将这四个数连接成一个表达式，是表达式的结果等于24。</p><p style="">一天，TYZ准备和他的中华小学犬ZZH开始一局24点挑战赛，在比赛之前的一个晚上，TYZ偷偷潜入客厅，将比赛的扑克牌中的J，Q，K和10全部藏了起来，以增加自己的胜率。不巧的是，ZZH在吃狗粮时看到了TYZ的卑鄙行为，于是他决定要把TYZ赢得心服口服，可是由于ZZH智商爆表，|ZZH.iQ()|==∞（且ZZH.iQ()&lt;=0），所以它决定求助于聪明绝顶的您。</p><p style=""><strong><span style="">形式化的讲，给出4个小于10个正整数，您需要使用加减乘除4种运算以及括号把这4个数连接起来得到一个表达式。判断这四个数能否算出24。</span></strong></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><strong><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">输入数据包括多行，每行给出一组测试数据，包括4个小于10个正整数。最后一组测试数据中包括4个0，表示输入的结束，这组数据不用处理。</span></strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><strong><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; line-height: 21px; font-size: 18px;">对于每一组测试数据，输出一行，如果可以得到24，输出“YES”；否则，输出“NO”。</span></strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: 'Courier New';">5 5 5 1
1 1 4 2
0 0 0 0</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: 'Courier New';">YES
NO</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释：对于5，5，5，1，我们知道5 * (5 – 1 / 5) = 24，因此可以得到24。又比如，对于1，1，4，2，我们怎么都不能得到24。</p><p><span style=""><strong><span style="">（注意：YES和NO均为大写）</span></strong></span></p>
</div>
</div>