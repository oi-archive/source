<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">作为一个生活散漫的人，小Z每天早上都要耗费很久从一堆五颜六色的袜子中找出一双来穿。终于有一天，小Z再也无法忍受这恼人的找袜子过程，于是他决定听天由命……</span></p><p><span style="">具体来说，小Z把这N只袜子从1到N编号，然后从编号L到R(L 尽管小Z并不在意两只袜子是不是完整的一双，甚至不在意两只袜子是否一左一右，他却很在意袜子的颜色，毕竟穿两只不同色的袜子会很尴尬。</span></p><p><span style="">你的任务便是告诉小Z，他有多大的概率抽到两只颜色相同的袜子。当然，小Z希望这个概率尽量高，所以他可能会询问多个(L,R)以方便自己选择。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入文件第一行包含两个正整数N和M。N为袜子的数量，M为小Z所提的询问的数量。接下来一行包含N个正整数Ci (<span style="">Ci ≤ N) </span>，其中Ci表示第i只袜子的颜色，相同的颜色用相同的数字表示。再接下来M行，每行两个正整数L，R (<span style="">1 ≤ L &lt; R ≤ N) </span>表示一个询问。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含M行，对于每个询问在一行中输出分数A/B表示从该询问的区间[L,R]中随机抽出两只袜子颜色相同的概率。若该概率为0则输出0/1，否则输出的A/B必须为最简分数。（详见样例）<span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;"></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">6 4</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">1 2 3 3 3 2<span style=""></span></span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">2 6</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">1 3</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">3 5</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">1 6</span></span><span style="font-family: arial, helvetica, sans-serif;"></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">2/5</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">0/1</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">1/1</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">4/15</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">【样例解释】</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">询问1：共C(5,2)=10种可能，其中抽出两个2有1种可能，抽出两个3有3种可能，概率为(1+3)/10=4/10=2/5。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">询问2：共C(3,2)=3种可能，无法抽到颜色相同的袜子，概率为0/3=0/1。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">询问3：共C(3,2)=3种可能，均为抽出两个3，概率为3/3=1/1。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">注：上述C(a, b)表<span style=""></span>示组合数，组合数C(a, b)等价于在a个不同的物品中选取b个的选取方案数。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">【数据规模和约定】<br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="">提示<span style="">：</span>数据有梯度<span style="">，且本题数据是随机生成的（非官方数据），不过暴力还是过不了。</span></span></span></span></p><p><br></p><table width="-351"><tbody><tr><td style="" valign="top"><span style="">数据点</span></td><td style="" valign="top"><span style="">数据范围</span></td></tr><tr><td style="" valign="top"><span style="">1</span></td><td style="" valign="top"><span style="">N=6,M=4</span></td></tr><tr><td style="" valign="top" width="96"><span style="">2,3</span></td><td style="" valign="top" width="96"><span style="">N,M ≤ 5000</span></td></tr><tr><td style="" valign="top" width="96"><span style="">4,5,6</span></td><td style="" valign="top" width="96"><span style="">N,M ≤ 25000</span></td></tr><tr><td style="" valign="top" width="96"><span style="">7,8,9,10</span></td><td style="" valign="top" width="96"><span style="">N,M ≤ 50000</span></td></tr></tbody></table>
</div>
</div>