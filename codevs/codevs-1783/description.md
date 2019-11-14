<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这就是智慧珠游戏</p>

<img src="/source/codevs/codevs-1783/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzgzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NTc2OTkyOS4wNDAuMzUzOTY4NzU2OTI5LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件中包含初始的盘件描述，一共有 10 行，第 i 行有 i 个字符。如果第 i 行 的第 j 个字符是字母”A”至”L”中的一个，则表示第 i 行第 j 列的格子上已经放了 零件，零件的编号为对应的字母。如果第 i 行的第 j 个字符是”.”，则表示第 i 行 第 j 列的格子上没有放零件。 <br>输入保证预放的零件已摆放在盘件中。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果能找到解，向输出文件打印 10 行，为放完全部 12 个零件后的布局。其 中，第 i 行应包含 i 个字符，第 i 行的第 j 个字符表示第 i 行第 j 列的格子上放的 是哪个零件。 如果无解，输出单独的一个字符串&lsquo;No solution&rsquo;(不要引号，请注意大小写)。 所有的数据保证最多只有一组解。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>.</p>
<p>..</p>
<p><span style="">...</span></p>
<p><span style=""> ....</span></p>
<p><span style=""> .....</span></p>
<p><span style=""> .....C</span></p>
<p><span style=""> ...CCC.</span></p>
<p><span style=""> EEEHH...</span></p>
<p><span style=""> E.HHH....</span></p>
<p><span style=""> E......... </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>B</p>
<p>BK</p>
<p>BKK</p>
<p>BJKK</p>
<p>JJJDD</p>
<p>GJGDDC</p>
<p>GGGCCCI</p>
<p>EEEHHIIA</p>
<p>ELHHHIAAF</p>
<p>ELLLLIFFFF </p>

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