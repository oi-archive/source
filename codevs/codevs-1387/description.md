<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一块<span style="font-family: 'Times New Roman';">N x N</span>（<span style="font-family: 'Times New Roman';">1&lt;=N&lt;=10</span>）正方形的黑白瓦片的图案要被转换成新的正方形图案。写一个程序来找出将原始<br>图案按照以下列转换方法转换成新图案的最小方式：<br><span style="font-family: 'Times New Roman';">#1</span>：转<span style="font-family: 'Times New Roman';">90</span>度：图案按顺时针转<span style="font-family: 'Times New Roman';">90</span>度。<br><span style="font-family: 'Times New Roman';">#2</span>：转<span style="font-family: 'Times New Roman';">180</span>度：图案按顺时针转<span style="font-family: 'Times New Roman';">180</span>度。<br><span style="font-family: 'Times New Roman';">#3</span>：转<span style="font-family: 'Times New Roman';">270</span>度：图案按顺时针转<span style="font-family: 'Times New Roman';">270</span>度。<br><span style="font-family: 'Times New Roman';">#4</span>：反射：图案在水平方向翻转（形成原图案的镜像）。<br><span style="font-family: 'Times New Roman';">#5</span>：组合：图案在水平方向翻转，然后按照<span style="font-family: 'Times New Roman';">#1-#3</span>之一转换。<br><span style="font-family: 'Times New Roman';">#6</span>：不改变：原图案不改变。<br><span style="font-family: 'Times New Roman';">#7</span>：无效转换：无法用以上方法得到新图案。<br>如果有多种可用的转换方法，请选择序号最小的那个。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<table border="1" style="">
<tbody>
<tr>
<td width="178"><span style="">第一行：<!--mstheme--></span></td>
<td width="563"><!--mstheme--><span style="">单独的一个整数<span style="font-family: 'Times New Roman';">N</span>。<!--mstheme--></span></td>
</tr>
<tr>
<td width="178"><!--mstheme--><span style="">第二行到第<span style="font-family: 'Times New Roman';">N+1</span>行：<!--mstheme--></span></td>
<td width="563"><!--mstheme--><span style=""><span style="font-family: 'Times New Roman';">N</span>行每行<span style="font-family: 'Times New Roman';">N</span>个字符（不是<span style="font-family: 'Times New Roman';">“@”</span>就是<span style="font-family: 'Times New Roman';">“-”</span>）；这是转换前的正方形。<!--mstheme--></span></td>
</tr>
<tr>
<td width="178"><!--mstheme--><span style="">第<span style="font-family: 'Times New Roman';">N+2</span>行到第<span style="font-family: 'Times New Roman';">2*N+1</span>行：<!--mstheme--></span></td>
<td width="563"><!--mstheme--><span style=""><span style="font-family: 'Times New Roman';">N</span>行每行<span style="font-family: 'Times New Roman';">N</span>个字符（不是<span style="font-family: 'Times New Roman';">“@”</span>就是<span style="font-family: 'Times New Roman';">“-”</span>）；这是转换后的正方形。</span></td>
</tr>
</tbody>
</table>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Times New Roman';">单独的一行包括1到7之间的一个数字（在上文已描述）表明需要将转换前的正方形变为转换后的正方形的<br />转换方法。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Times New Roman';">3<br></span><span style="">@-@<br>---<br>@@-<br>@-@<br>@--<br>--@</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Times New Roman';">1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>