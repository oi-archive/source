<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><strong>公路图纸</strong></p>
<p>上一次，你帮小Z完成了高速公路的规划，小Z十分高兴，又送了你一车子的鸡蛋（编者：一定又是你奶奶的养鸡场的蛋吧……小Z：不是，不只是一家，她开连锁店了。编者：-□-｜｜）。现在，他想看一看高速公路的样子，又请到了你。</p>
<p>给你两个点，把两个点连起来。</p>
<p>只能横着、竖着、斜着连（周围八格）</p>
<p>例：</p>
<p>****         ****</p>
<p>#***         ##**</p>
<p>****         **#*</p>
<p>***#——&gt;***#</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共10行</p>
<p>每行十个字母，有两个’#’，代表两个要连的点。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共12行</p>
<p>第一行：最短路径的条数以及最点路径的距离（算两个点）</p>
<p>第二~十一行：10*10的方块（完成图（方法见提示））</p>
<p>最后一行：花费的钱（经过的点（两端不算）的ASCLL码之和）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>**********<br>*#********<br>****#*****<br>**********<br>**********<br>**********<br>**********<br>**********<br>**********<br>********** </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 4</p>
<p>**********<br>*###******<br>****#*****<br>**********<br>**********<br>**********<br>**********<br>**********<br>**********<br>**********</p>
<p>84</p>
<p>样例解释：</p>
<p>共有三种最短路径：</p>
<p>###*  ##**  #***</p>
<p>***#   **##  *###</p>
<p>距离是四</p>
<p>耗费八十四元（'*'的ASCLL码是42，经过两个'*'）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据保证：只有'*'和'#'；</p>
<p>100%的数据保证：只有两个'#'（小Z：废话！）。（待续…………）</p>
<p>提示：对于两点之间有6种情况</p>
<p>***#   **#*  *#**  ***#  #***  #***<br>****   ****   ****  ****   ****   ****<br>****   ****   ****  #***  ***#   ****<br>#***  #***   ***#  ****  ****   ***#<br>分别对应以下完成图：<br>***#  **#*  *#**  **##  ##**  #***<br>**#*  **#*  *#**  *#**   **#*  *#**<br>*#**  *#**  **#*  #***   ***#  **#*<br>#***  #***  ***#  ****   ****   ***#</p>
</div>
</div>