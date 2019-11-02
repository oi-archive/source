<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>21世纪．人类宇航员第一次在火星表面登陆，发现了一些奇妙的图案，经科学家们的研究，猜想其中的某一部分可能为火星人计算两个数相乘的记录，且它们用的是18进制。</p>
<p>在这些图案和符号中，他们用类似ASCII来表示数字，具体如下：</p>
<p>I 代表 “1” N代表 “10” M代表 “100”</p>
<p>H代表 “1000”</p>
<p>R代表 “10000”</p>
<p>P代表 “100000”</p>
<p>K代表 “1000000”</p>
<p>T代表 “10000000”</p>
<p>上面用“”包含的数字是18进制的数字，如M十M代表“110”（为方便起见，将字符间的加号省略，写为NM），相当于我们所用的十进制数342（342=18x18＋18）。而我们的十进制数401，火星人写为：</p>
<p>(401）<sub>10</sub>=1x（18）<sub>10</sub>x（18）<sub>10</sub>+4x（18）<sub>10</sub>＋5x（1）<sub>10</sub>=(145）<sub>18</sub>＝1x（100）<sub>18</sub>＋4x（10）<sub>18</sub>＋5x（1）<sub>18</sub>=IIIIINNNNM</p>
<p>（先写低位后写高位）</p>
<p>现在使数字a与数字b相乘，火星人的方法是：先用I与b相乘，I在第一行的左边，右边为I与b的积，再用II与b相乘，第二行输出II及II与b的积，每次加倍，依次用IIII、 IIIIIIII等去乘b，直到当各行左边一列的数的和大于等于a为止。</p>
<p>例如：</p>
<p>a＝IIIIIIIIINN</p>
<p>b＝IIIIINNNNNN</p>
<p>过程如下：</p>
<p>I＊IIIIINNNNNN</p>
<p>II IIIIIIIIIINNNNNNNNNNNN</p>
<p>IIII＊IINNNNNNNH</p>
<p>IIIIIIII＊IIIINNNNNNNNNNNNNNMM</p>
<p>IIIIIIII＊IIIIIIIINNNNNNNNNNMMMM</p>
<p>IIIIIIIIIIIIIIII IIIIIIIINNNNNNNNNNMM</p>
<p>IIIIIIIIIIIIIIN＊IIIIIIIIIIIIIIIINNMMMMMMMMMMM</p>
<p>在左边的一列中取出I、IIII、IIIIIIII、IIIIIIIIIIIIIIN（这四个数之和为a，取出的数紧接输出一个“＊”，这四行对应的右边的四项之和即为a X b，结果为：</p>
<p>IIIIIIIIINNNNNNNNNNNNMMMMMMMMMMMMMMM</p>
<p>编程完成上述乘法。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件仅含两行，第一行为“a”，第二行为“b”。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出由若干行组成。每行的左列从上到下依次为：I、II、IIII&hellip;，取出的数紧接着输出一个&ldquo;＊&rdquo;，右列从上到下依次为：I、II、IIII等与b的乘积，左列与右列之间用一个空格隔开。最后的一行输出&ldquo;The solution is ：&rdquo;和最后的积axb。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>IIIIIIIIINN</span></p>
<p><span>IIIIINNNNNN</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>I</span>＊<span>IIIIINNNNNN</span></p>
<p><span>II IIIIIIIIIINNNNNNNNNNNN</span></p>
<p><span>IIII</span>＊<span>IINNNNNNNM</span></p>
<p><span>IIIIIIII</span>＊<span>IIIINNNNNNNNNNNNNNMM</span></p>
<p><span>IIIIIIIIIIIIIIII IIIIIIIINNNNNNNNNNMMMMM</span></p>
<p><span>IIIIIIIIIIIIIIN</span>＊<span>IIIIIIIIIIIIIIIINNMMMMMMMMMMM</span></p>
<p><span>The solution is</span>：<span>IIIIIIIIINNNNNNNNNNNNMMMMMMMMMMMMMMM</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入的a和 b为我们地球上使用的小于等于32767的正整数</p>
</div>
</div>