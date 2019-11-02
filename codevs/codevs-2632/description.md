<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">Bessie<span style="">和其他的所有奶牛的耳朵上都戴有一个射频识别（</span><span style="font-family: Times New Roman;">RFID</span><span style="">）序列号码牌。因此农夫</span><span style="font-family: Times New Roman;">John</span><span style="">可以机械化地计算他们的数量。很多奶牛都有一个“牛友”。如果奶牛</span><span style="font-family: Times New Roman;">A</span><span style="">的序列号的约数之和刚好等于奶牛</span><span style="font-family: Times New Roman;">B</span><span style="">的序列号，那么</span><span style="font-family: Times New Roman;">A</span><span style="">的牛友就是</span><span style="font-family: Times New Roman;">B</span><span style="">。在这里，一个数的“约数”不包括这个数本身。</span></span></p>
<p style=""><span style="">因为一些奶牛的号码约数和大于其他任何奶牛的号码，所以这些奶牛没有牛友。而一些奶牛有一个“非常好友”，当两个奶牛互为“牛友”时，他们就是一对“非常好友”。注意在这道题中，忽略那些自己是自己的“非常好友”的情况。</span></p>
<p style=""><span style="">给定一个序列号<span style="font-family: Times New Roman;">S (6</span><span style="">≤</span><span style="font-family: Times New Roman;">S</span><span style="">≤</span><span style="font-family: Times New Roman;">18,000)</span><span style="">，找到序列号不小于</span><span style="font-family: Times New Roman;">S</span><span style="">的第一个有“非常好友”的奶牛。</span></span></p>
<p style=""><span style="">比如说，考虑序列号<span style="font-family: Times New Roman;">220</span><span style="">，它的约数是</span><span style="font-family: Times New Roman;">1, 2, 4, 5, 10, 11, 20, 22, 44, 55, </span><span style="">和</span><span style="font-family: Times New Roman;">110</span><span style="">，和是</span><span style="font-family: Times New Roman;">284</span><span style="">。类似的，</span><span style="font-family: Times New Roman;">284</span><span style="">的约数是</span><span style="font-family: Times New Roman;">1, 2, 4, 71, </span><span style="">和</span><span style="font-family: Times New Roman;">142</span><span style="">，他们的和是</span><span style="font-family: Times New Roman;">220</span><span style="">。因此</span><span style="font-family: Times New Roman;">220</span><span style="">和</span><span style="font-family: Times New Roman;">284</span><span style="">是一对非常好友。</span></span></p>
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
<p style=""><span style="">第<span style="font-family: Times New Roman;">1</span><span style="">行</span><span style="font-family: Times New Roman;">: </span><span style="">一个单独的整数</span><span style="font-family: Times New Roman;">S</span><span style="">，即给定的序列号。</span></span></p>
<!--EndFragment-->

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0" style="line-height: 150%; text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: '宋体'; font-size: 14pt; mso-spacerun: 'yes';">第<span style="font-family: Times New Roman;">1</span><span style="font-family: 宋体;">行：</span><span style="font-family: Times New Roman;">2</span><span style="font-family: 宋体;">个整数</span><span style="font-family: Times New Roman;">A</span><span style="font-family: 宋体;">和</span><span style="font-family: Times New Roman;">B</span><span style="font-family: 宋体;">，用一个空格隔开。</span><span style="font-family: Times New Roman;">A</span><span style="font-family: 宋体;">表示第一个序列号不小于</span><span style="font-family: Times New Roman;">S</span><span style="font-family: 宋体;">的有非常好友的奶牛的序列号，</span><span style="font-family: Times New Roman;">B</span><span style="font-family: 宋体;">是他的&ldquo;非常好友&rdquo;的序列号。</span></span></p>
<!--EndFragment-->

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Times New Roman';">206</span></p>
<!--EndFragment-->

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Times New Roman';">220 284</span></p>
<!--EndFragment-->

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>NO</p>
</div>
</div>