<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>排版是很有讲究的。假设稿纸的宽度是W个字符，长度不限，当你对一篇文章排版时，必须满足以下条件：</p>
<p>1.必须保持单词的次序。下图显示了对4个单词“This is a pen”在一张宽11字符的稿纸上排版的结果：</p>
<p>2.同一行的两个相邻单词之间至少要有一个空格分隔。</p>
<p>3.单词必须保持其完整性，不能从中间断成两行，也不能在单词中间插入空格。</p>
<p>4.排版必须两头对齐，每行第一个单词必须顶着最左列；除了最后一行，每行最后一个单词必须顶着最右列。</p>
<p>  最美观的排版要求版面中不出现非必要的长空格。例如图6最多只出现了两个连续空格，而图1中出现了三个连续空格，因此图6的排版比图1的排版美观。你的任务是对给定的文章和稿纸宽度，计算最美观的排版。</p>
<p> </p>

<img src="/source/codevs/codevs-2576/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzI1NzYucG5n.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行是用空格分隔的两个正整数W和N（3&lt;=W&lt;=80000，2&lt;=N&lt;=50000），分别代表稿纸的宽度和单词数。接下来有N个正整数，第i个正整数x<sub>i</sub>代表第i个单词的长度（1&lt;=x<sub>i</sub>&lt;=(W-1)/2）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数，代表最美观的排版中，最多出现多少个连续空格。</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="253">
<p>spacing.in</p>
</td>
</tr>
<tr>
<td valign="top" width="253">
<p>11 4</p>
<p>4 2 1 3</p>
</td>
</tr>
<tr>
<td valign="top" width="253">
<p>5 7</p>
<p>1 1 1 2 2 1 2</p>
</td>
</tr>
<tr>
<td valign="top" width="253">
<p>11 7</p>
<p>3 1 3 1 3 3 4</p>
</td>
</tr>
<tr>
<td valign="top" width="253">
<p>100 3</p>
<p>30 30 39</p>
</td>
</tr>
<tr>
<td valign="top" width="253">
<p>30 3</p>
<p>2 5 3</p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="275">
<p>spacing.out</p>
</td>
</tr>
<tr>
<td valign="top" width="275">
<p>2</p>
</td>
</tr>
<tr>
<td valign="top" width="275">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="275">
<p>2</p>
</td>
</tr>
<tr>
<td valign="top" width="275">
<p>40</p>
</td>
</tr>
<tr>
<td valign="top" width="275">
<p>1</p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>3&lt;=W&lt;=80000，2&lt;=N&lt;=50000 </p>
<p> </p>
<p>2013广州市队选拔赛</p>
</div>
</div>