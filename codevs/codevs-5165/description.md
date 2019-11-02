<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">任何一个正整数都可以用2的幂次方表示。例如：</span></p><p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">    137=2<sup>7</sup>+2<sup>3</sup>+2<sup>0</sup></span></p><p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">同时约定方次用括号来表示，即a<sup>b</sup>可表示为a(b)。由此可知，137可表示为：</span></p><p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">    2(7)+2(3)+2(0)</span></p><p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">进一步：7=2<sup>2</sup>+2+2<sup>0</sup>（2<sup>1</sup>用2表示）</span></p><p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">        3=2+2<sup>0</sup></span></p><p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">所以最后137可表示为：</span></p><p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">    2(2(2)+2+2(0))+2(2+2(0))+2(0)</span></p><p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">又如：</span></p><p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">    1315=2<sup>10</sup>+2<sup>8</sup>+2<sup>5</sup>+2+1</span></p><p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">所以1315最后可表示为：</span></p><p style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'><span style="">    2(2(2+2(0))+2)+2(2(2+2(0)))+2(2(2)+2(0))+2+2(0)</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个正整数x(x≤2^16-1)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>x的符合题目要求的表示（不能有额外的空格）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>137<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style='font-family: "Lucida Grande", Verdana, "Bitstream Vera Sans", Arial, sans-serif;'>2(2(2)+2+2(0))+2(2+2(0))+2(0)</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>x≤2^16-1</p><p>输出不能有额外的空格</p>
</div>
</div>