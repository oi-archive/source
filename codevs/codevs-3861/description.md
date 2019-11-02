<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">“唔～哈哈哈哈哈哈哈哈哈，这样一来我就是新世界的神了！”“冈伦你闭嘴”</span></p><p style=""><span style="">从前有一个叫冈伦的阿宅，他和他的朋友们把手机和微波炉连接到一起想要做一个可以远程控制启动的微波炉。但好像是一个不小心，微波炉和旁边的电视机恰好构成了一个粒子加速器（这要花掉多少RP）从而能够生成可以用于往过去发送数据的克尔黑洞……</span></p><p style=""><span style="">经过冈伦和他的朋友们彻夜不眠的研究（其实冈伦基本没动手），他们终于弄清了这只机器的工作规律（其实原理还是没有弄懂）：以发送手机短信为例，当微波炉的加热时间设定为</span><span style="">m</span><span style="">秒时，短信就会被发送往</span><span style="">m*k</span><span style="">小时前。</span></p><p style=""><span style="">而又经过冈伦和他的朋友们彻夜不眠的改造，他们将微波炉改造成了不但可以发送短信，更可以将人的意识传送到过去的时间跳跃机（又名Heavenly Express，顺带一提冈伦基本没动手只有这个别名是冈伦取的）。而跳跃机在计算大脑的记忆储存量的时候需要进行一系列的加法操作。</span></p><p style=""><span style="">但是问题来了，因为时间机器自身的原因，以及冈伦和他的伙伴们的雄心壮志非常远大，上述整数最大都可能达到10</span><span style="">100</span><span style="">，而Windows自带的计算器明显不够用。所以冈伦决定亲自上阵，动手用草稿纸笔算。但这实在蠢到让人看不下去了，所以你决定亲自写一个计算器帮他们实现这几个简单得不行的计算功能。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行是一个字符串，如果该字符串是“D-Mail”，则微波炉处于发送短信的状态，如果是“Time Leap”，则微波炉处于时间跳跃的状态。（均无双引号，且要注意区分大小写）</span></p><p style=""><span style="">第二行是一个整数，表示共要处理</span><span style="">n</span><span style="">次运算。</span></p><p style=""><span style="">接下来2*</span><span style="">n</span><span style="">行，每行有一个整数，两行为一组，当微波炉处于发送短信的状态时分别代表</span><span style="">m</span><span style="">和</span><span style="">k</span><span style="">，当处于时间跳跃状态时，则分别代表两个需要相加的整数</span><span style="">a</span><span style="">和</span><span style="">b</span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 28px;"><span style=";font-family:华文细黑;font-size:14px">共</span><span style=";font-family:华文细黑;font-style:italic;font-size:14px">n</span><span style=";font-family:华文细黑;font-size:14px">行，每行一个整数，表示运算的结果。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<table style="" width="595"><tbody><tr style=""><td style="" valign="top" width="298"><p><span style="">样例一</span></p><p><span style="">D-Mail</span></p><p><span style="">3</span></p><p><span style="">30</span></p><p><span style="">2</span></p><p><span style="">66</span></p><p><span style="">99</span></p><p><span style="">987654321987654321</span></p><p><span style="">1000000000000000</span></p></td><td style="" valign="top" width="298"><p><span style="">样例二</span></p><p><span style="">Time Leap</span></p><p><span style="">3</span></p><p><span style="">123</span></p><p><span style="">210</span></p><p><span style="">555</span></p><p><span style="">913</span></p><p><span style="">74747412380000</span></p><p><span style="">999999999999999</span></p></td></tr></tbody></table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<table style="" width="606"><tbody><tr style=""><td style="" valign="top" width="303"><p><span style="">样例一</span></p><p><span style="">60</span></p><p><span style="">6534</span></p><p><span style="">987654321987654321000000000000000</span></p></td><td style="" valign="top" width="303"><p><span style="">样例二</span></p><p><span style="">333</span></p><p><span style="">1468</span></p><p><span style="">1074747412379999</span></p></td></tr></tbody></table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">时间限制</span></p><p style=""><span style="">因为时间机器打开克尔黑洞的能力实在是有限，所以不在1s内计算出来的话，不但数据传输会失败，而且你还会被冈伦加以惨无人道的嘲讽。</span></p><p><span style="">数据范围</span></p><p style=""><span style="">0≤所有整数≤10</span><span style="">100</span></p><p><span style="">Hint</span></p><p style=""><span style="">“你的一秒，便是我的永恒。”</span> <span style="">——林 直孝</span></p><p style=""><span style="">“等着我，红莉栖。”</span> <span style="">——冈部 伦太郎</span></p><p style=""><span style="">小提示：冈伦其实不笨，想想草稿纸笔算时的竖式计算能对本题有什么启发？</span></p><p style=""><span style="">Problem by nGya。</span></p><p style=""><span style="">p.s.:这份题里就我的题目背景最正常有木有</span></p>
</div>
</div>