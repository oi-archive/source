<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="FONT-FAMILY: arial, helvetica, sans-serif;">     Tgopknight是著名的计算机天才，他十分喜欢研究二进制。所以他对0和1特别感兴趣。由于他很喜欢读宋词，在文学的熏陶下，他发现只有0,1,组成的十进制数是十分有特点的。他定义为特别的数：</span></p><p><span style="FONT-FAMILY: arial, helvetica, sans-serif;">1. “1”是一个的特别的数。</span></p><p><span style="FONT-FAMILY: arial, helvetica, sans-serif;">2. 一个以“1”结尾的特别的数在末尾加上“1”或“0”都是特别的数</span></p><p><span style="FONT-FAMILY: arial, helvetica, sans-serif;">3. 一个以“0”结尾的特别的数在末尾加上“0”是特别的数。</span></p><p><span style="FONT-FAMILY: arial, helvetica, sans-serif;">     很快他发现了这些数字之间隐藏的奥秘！现在他想知道这些特别的数中是否有一个能被M整除？如果存在，请输出特别的数中最小一个满足条件的数，如果不存在这样的数，请输出“Impossible”！</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入一个数M<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出符合题意得0 1 串</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：1</p><p>样例2：6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">样例1：110</p><p style="">样例2：1110</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="FONT-FAMILY: arial, helvetica, sans-serif;">样例解释1：实际上任何一个特别的数都会是答案。</span></p><p><span style="FONT-FAMILY: arial, helvetica, sans-serif;"><span style=""></span>样例解释2：</span>我们枚举比1110小的特别的数 1,10,11,100,110,111,1000,1100发现他们都不能被6整除。</p><p><br><span style="FONT-FAMILY: arial, helvetica, sans-serif;"></span></p><p><span style="FONT-FAMILY: arial, helvetica, sans-serif;"><br></span></p><p><span style="FONT-FAMILY: arial, helvetica, sans-serif;">对于前30%的数据，保证存在一个答案使得答案小于32767或者不存在这样的数。</span></p><p><span style="FONT-FAMILY: arial, helvetica, sans-serif;">对于前60%的数据，保证答案的长度不超过20位，或者不存在这样的数。</span></p><p><span style="FONT-FAMILY: arial, helvetica, sans-serif;">对于100%的数据，保证M(1&lt;=M&lt;=1e7),答案可能十分的大，如果觉得有必要可以考虑输出优化。</span></p><p><br></p>
</div>
</div>