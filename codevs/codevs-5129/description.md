<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""><span style="">扫雷游戏是一款十分经典的单机小游戏。 在 n 行 m 列的雷区中有一些格子含有地雷（称之为地雷格） ，其他格子不含地雷（称之为非地雷格） 。玩家翻开一个非地雷格时，该格将会出现一个数字——提示周围格子中有多少个是地雷格。 游戏的目标是在不翻出任何地雷格的条件下，找出所有的非地雷格。</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">现在给出n行m列的雷区中的地雷分布， 要求计算出每个非地雷格周围的地雷格数。</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">注：一个格子的周围格子包括其上、下、左、右、左上、右上、左下、右下八个方向上与之直接相邻的格子。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入文件第一行 是用一个空格隔开的 两个整数n和m， 分别表示雷区的行数和列数。</span></p><p><span style="">接下来 n 行，每行 m 个字符，描述了雷区中的地雷分布情况。字符 '*' 表示相应格子是地雷格，字符 '?' 表示相应格子是非地雷格。相邻字符之间无分隔符。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;; "><span style="color: rgb(51, 51, 51); font-size: 14px; line-height: 25px; background-color: rgb(255, 255, 255); ">输出文件包含&nbsp;n&nbsp;行，每行&nbsp;m&nbsp;个字符，描述整个雷区。用 &#39;*&#39; 表示地雷格，用周围</span><span style="background-color: rgb(255, 255, 255); color: rgb(51, 51, 51); font-size: 14px; line-height: 25px; ">的地雷个数表示非地雷格。相邻字符之间无分隔符。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">输入样例 1</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">3 3</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">*??</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">???</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">?*?</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style=""><br></span></span></p><p><span style=""><span style="">输入样例 2</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">2 3</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">?*?</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">*??</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">输出样例 1</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">*10</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">221</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">1*1<span style=""></span></span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style=""><br></span></span></p><p><span style=""><span style="">输出样例 2</span><br style="font-family: Verdana, Arial, Helvetica, sans-serif;"><span style="">2*1</span><br></span></p><p><span style="">*21</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于 100%的数据，1≤n≤100，1≤m≤100</span></p>
</div>
</div>