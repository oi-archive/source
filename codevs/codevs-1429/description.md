<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小<span style="font-family: 'Times New Roman';">Q</span><span style="">的妈妈是一个出纳，经常需要做一些统计报表的工作。今天是妈妈的生日，小</span><span style="font-family: 'Times New Roman';">Q</span><span style="">希望可以帮妈妈分担一些工作，作为她的生日礼物之一。</span></p>
<p>经过仔细观察，小<span style="font-family: 'Times New Roman';">Q</span><span style="">发现统计一张报表实际上是维护一个非负整数数列，并且进行一些查询操作。</span></p>
<p>在最开始的时候，有一个长度为N的整数序列，并且有以下三种操作：</p>
<p> </p>
<table>
<tbody>
<tr>
<td valign="top" width="133">
<p>INSERT i k</p>
</td>
<td valign="top" width="310">
<p>在原数列的第i个元素后面添加一个新元素k；如果原数列的第i个元素已经添加了若干元素，则添加在这些元素的最后（见下面的例子）</p>
</td>
</tr>
<tr>
<td valign="top" width="133">
<p>MIN_GAP</p>
</td>
<td valign="top" width="310">
<p>查询相邻两个元素的之间差值（绝对值）的最小值</p>
</td>
</tr>
<tr>
<td valign="top" width="133">
<p>MIN_SORT_GAP</p>
</td>
<td valign="top" width="310">
<p>查询所有元素中最接近的两个元素的差值（绝对值）</p>
</td>
</tr>
</tbody>
</table>
<p> </p>
<p>例如一开始的序列为</p>
<table>
<tbody>
<tr>
<td valign="top" width="56">
<p>5</p>
</td>
<td valign="top" width="56">
<p>3</p>
</td>
<td valign="top" width="56">
<p>1</p>
</td>
</tr>
</tbody>
</table>
<p> </p>
<p>执行操作<span style="font-family: 'Times New Roman';">INSERT 2  9</span><span style="">将得到：</span></p>
<table>
<tbody>
<tr>
<td valign="top" width="56">
<p>5</p>
</td>
<td valign="top" width="56">
<p>3</p>
</td>
<td valign="top" width="56">
<p>9</p>
</td>
<td valign="top" width="56">
<p>1</p>
</td>
</tr>
</tbody>
</table>
<p>此时<span style="font-family: 'Times New Roman';">MIN_GAP</span><span style="">为</span><span style="font-family: 'Times New Roman';">2</span><span style="">，</span><span style="font-family: 'Times New Roman';">MIN_SORT_GAP</span><span style="">为</span><span style="font-family: 'Times New Roman';">2</span><span style="">。</span></p>
<p> </p>
<p>再执行操作<span style="font-family: 'Times New Roman';">INSERT 2  6</span><span style="">将得到：</span></p>
<table>
<tbody>
<tr>
<td valign="top" width="56">
<p>5</p>
</td>
<td valign="top" width="56">
<p>3</p>
</td>
<td valign="top" width="56">
<p>9</p>
</td>
<td valign="top" width="56">
<p>6</p>
</td>
<td valign="top" width="56">
<p>1</p>
</td>
</tr>
</tbody>
</table>
<p> </p>
<p>注意这个时候原序列的第<span style="font-family: 'Times New Roman';">2</span><span style="">个元素后面已经添加了一个</span><span style="font-family: 'Times New Roman';">9</span><span style="">，此时添加的</span><span style="font-family: 'Times New Roman';">6</span><span style="">应加在</span><span style="font-family: 'Times New Roman';">9</span><span style="">的后面。这个时候</span><span style="font-family: 'Times New Roman';">MIN_GAP</span><span style="">为</span><span style="font-family: 'Times New Roman';">2</span><span style="">，</span><span style="font-family: 'Times New Roman';">MIN_SORT_GAP</span><span style="">为</span><span style="font-family: 'Times New Roman';">1</span><span style="">。</span></p>
<p>于是小<span style="font-family: 'Times New Roman';">Q</span><span style="">写了一个程序，使得程序可以自动完成这些操作，但是他发现对于一些大的报表他的程序运行得很慢，你能帮助他改进程序么？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个整数N，M，分别表示原数列的长度以及操作的次数。</p>
<p>第二行为N个整数，为初始序列。</p>
<p>接下来的M行每行一个操作，即“<span style="font-family: 'Times New Roman';">INSERT </span>i k”，“<span style="font-family: 'Times New Roman';">MIN_GAP</span><span style="">”，“</span><span style="font-family: 'Times New Roman';">MIN_SORT_GAP</span><span style="">”中的一种（无多余空格或者空行）。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对于每一个&ldquo;<span style="font-family: 'Times New Roman';">MIN_GAP</span><span style="font-family: 宋体;">&rdquo;和&ldquo;</span><span style="font-family: 'Times New Roman';">MIN_SORT_GAP</span><span style="font-family: 宋体;">&rdquo;命令，输出一行答案即可。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 5</p>
<p>5 3 1</p>
<p>INSERT 2 9</p>
<p>MIN_SORT_GAP</p>
<p>INSERT 2 6</p>
<p>MIN_GAP</p>
<p>MIN_SORT_GAP</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>2</p>
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据，</span>N ≤ 1000 , M ≤ 5000</p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，</span>N , M ≤500000</p>
<p>对于所有的数据，序列内的整数不超过<span style="font-family: 'Times New Roman';">5*10</span><sup><span>8</span></sup>。</p>
<p> </p>
</div>
</div>