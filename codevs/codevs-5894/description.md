<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">下面是一个乘法竖式，如果用我们给定的那n个数字来替代*，可以使式子成立的话，我们就叫这个式子牛式。</p><pre style="">          ***
x      **
----------
***
***
----------
****</pre><p style="">数字只能取代*，当然第一位不能为0,况且给定的数字里不包括0。</p><p style="">注意一下在美国的学校中教的“部分乘积”，第一部分乘积是第二个数的个位和第一个数的积，第二部分乘积是第二个数的十位和第一个数的乘积.</p><p style="">写一个程序求出所有牛式的总数。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">Line 1:数字的个数n。</p><p style="">Line 2:N个用空格分开的数字（每个数字都属于{1,2,3,4,5,6,7,8,9}）。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 12.7px; line-height: 19.05px; background-color: rgb(255, 255, 255);">共一行，一个数字。表示牛式的总数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="">5
2 3 4 6 8</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="">1</pre><h2 style="font-weight: normal;"><span>样例分析</span></h2><pre style="">          222
x      22
----------
444
444
----------
4884</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">每个数字都属于{1,2,3,4,5,6,7,8,9}</span></p><p><span style="">注意：结果只能为4位</span></p>
</div>
</div>