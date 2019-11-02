<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">求一元二次方程ax</span><sup style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">2</sup><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">+ bx + c =0的根，其中a不等于0。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">输入一行，包含三个浮点数a, b, c（它们之间以一个空格分开），分别表示方程ax</span><sup style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">2</sup><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"> + bx + c =0的系数。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">输出一行，表示方程的解。</span><br style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px; white-space: normal;"/><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">若b</span><sup style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; line-height: 21px; white-space: normal;">2</sup><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">&nbsp;= 4 * a * c,则两个实根相等，则输出形式为：x1=x2=...。</span><br style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px; white-space: normal;"/><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">若b</span><sup style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; line-height: 21px; white-space: normal;">2</sup><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">&nbsp;&gt; 4 * a * c,则两个实根不等，则输出形式为：x1=...;x2 = ...，其中x1&gt;x2。</span><br style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px; white-space: normal;"/><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">若b</span><sup style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; line-height: 21px; white-space: normal;">2</sup><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">&nbsp;&lt; 4 * a * c，则有两个虚根，则输出：x1=实部+虚部i; x2=实部-虚部i，即x1的虚部系数大于等于x2的虚部系数，实部为0时不可省略。实部 = -b / (2*a), 虚部 = sqrt(4*a*c-b*b) / (2*a)</span><br style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px; white-space: normal;"/><br style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px; white-space: normal;"/><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">所有实数部分要求精确到小数点后5位，数字、符号之间没有空格。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre style="font-family: 'Courier New';">样例输入1
1.0 2.0 8.0

样例输入2
1 0 1</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre style="font-family: 'Courier New';">样例输出1
x1=-1.00000+2.64575i;x2=-1.00000-2.64575i

样例输出2
x1=0.00000+1.00000i;x2=0.00000-1.00000i</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>a,b,c&lt;100<br></p>
</div>
</div>