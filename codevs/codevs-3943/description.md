<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">作为上白泽慧音老师的出色弟子，数学奇才琪露诺在算术方面有很深的造诣。今天，codevs</span><span style=""></span><span style="">有幸请到了这位数学界的奇葩作为本场考试的第一题主考官。</span></p><p style=""><span style="">琪露诺喜欢0-9</span><span style=""></span><span style="">之间的数字，她喜欢将十进制非负数字的每一位一一识别出来，再将它们用计算器加起来，也即数字的数位之和，例如，对于1234</span><span style=""></span><span style="">，琪露诺会用计算器算出1+2+3+4=10</span><span style=""></span><span style="">。</span></p><p style=""><span style="">琪露诺不仅会使用计算器的加法，还会使用计算器的减法、乘法和求幂操作，她觉得一个数x</span><span style=""></span><span style="">对她来说是有趣的，当且仅当<strong><em><span style="TEXT-DECORATION: underline;">她将x</span></em></strong></span><span style=""></span><strong><em><span style="TEXT-DECORATION: underline;"><span style="">的数位之和算出来后，进行求k</span></span></em></strong><span style=""></span><strong><em><span style="TEXT-DECORATION: underline;"><span style="">次幂的操作，再乘p</span></span></em></strong><span style=""></span><strong><em><span style="TEXT-DECORATION: underline;"><span style="">，再加上或减去</span></span></em><span style="TEXT-DECORATION: underline;"><span style="">|q|</span></span></strong><span style=""></span><strong><span style="TEXT-DECORATION: underline;"><span style="">，</span></span><em><span style="TEXT-DECORATION: underline;"><span style="">得到的数恰好还是x</span></span></em></strong><span style=""></span><span style="">。</span></p><p style=""><span style="">琪露诺是非常好奇，在一段区间[l,r]</span><span style="">以内的所有整数x</span><span style=""></span><span style="">里，有多少个x</span><span style=""></span><span style="">对她来说是有趣的，她希望你能帮她解决这个问题。</span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">    第一行三个整数k,p和q，</span></span><span style="">表示求k</span><span style=""></span><span style="">次幂，乘以p</span><span style="">，如果q</span><span style=""></span><span style="">为正则加上|q|</span><span style=""></span><span style="">，如果</span><span style=""></span><span style="">非正则减去|q|</span><span style=""></span><span style="">。</span></p><p style=""><span style="">第二行两个非负整数l</span><span style=""></span><span style="">和r</span><span style=""></span><span style="">，表示所求的区间，保证l≤r</span><span style=""></span><span style="">。</span></p><p><span style=""><br></span></p><p><span style=""><span style=""><br></span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="TEXT-INDENT: 28px"><span style="FONT-FAMILY: 宋体"></span></p><p style="TEXT-INDENT: 28px"><span style="FONT-FAMILY: 宋体">第一行一个非负整数n</span><span style="FONT-FAMILY: ; TOP: 3px"></span><span style="FONT-FAMILY: 宋体">，表示有多少个有趣的x</span><span style="FONT-FAMILY: ; TOP: 3px"></span><span style="FONT-FAMILY: 宋体">。</span></p><p style="TEXT-INDENT: 28px"><span style="FONT-FAMILY: 宋体">如果</span><span style="FONT-FAMILY: ; TOP: 3px"></span><span style="FONT-FAMILY: 宋体">为n正，则第二行升序输出n</span><span style="FONT-FAMILY: ; TOP: 3px"></span><span style="FONT-FAMILY: 宋体">个非负整数，表示这n</span><span style="FONT-FAMILY: ; TOP: 3px"></span><span style="FONT-FAMILY: 宋体">个有趣的数字，数字之间用一个空格隔开，行末可以有多余空格。</span></p><p style="TEXT-INDENT: 28px">&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">2 2 -1</span></p><p style=""><span style="">1 999</span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">4</span></p><p style=""><span style="">1 31 337 967</span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于100%</span><span style=""></span><span style="">的数据，有1≤k<span style="">≤</span>5,0<span style="">≤</span>p,|q|<span style="">≤</span>10000,0<span style="">≤</span>l<span style="">≤</span>r<span style="">≤</span>10<sup>9</sup></span><span style="">。</span></p>
</div>
</div>