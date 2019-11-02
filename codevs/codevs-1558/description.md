<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>约翰农场的牛群希望能够在 <span style="font-family: Times New Roman;">N </span><span style="">个</span><span style="font-family: Times New Roman;">(1&lt;=N&lt;=200) </span><span style="">草地之间任意移动。草地的编号由 </span><span style="font-family: Times New Roman;">1</span><span style="">到 </span><span style="font-family: Times New Roman;">N</span><span style="">。草地之间有树林隔开。牛群希望能够选择草地间的路径，使牛群能够从任一 片草地移动到任一片其它草地。 牛群可在路径上双向通行。</span></p>
<p>牛群并不能创造路径，但是他们会保有及利用已经发现的野兽所走出来的路径<span style="font-family: Times New Roman;">(</span><span style="">以 下简称兽径</span><span style="font-family: Times New Roman;">)</span><span style="">。每星期他们会选择并管理一些或全部已知的兽径当作通路。</span></p>
<p>牛群每星期初会发现一条新的兽径。他们接着必须决定管理哪些兽径来组成该周牛 群移动的通路，使得牛群得以从任一草地移动到任一草地。牛群只能使用当周有被 管理的兽径做为通路。</p>
<p>牛群希望他们管理的兽径长度和为最小。牛群可以从所有他们知道的所有兽径中挑 选出一些来管理。牛群可以挑选的兽径与它之前是否曾被管理无关。</p>
<p>兽径决不会是直线，因此连接两片草地之间的不同兽径长度可以不同。 此外虽然 两条兽径或许会相交，但牛群非常的专注，除非交点是在草地内，否则不会在交点 换到另外一条兽径上。</p>
<p>在每周开始的时候，牛群会描述他们新发现的兽径。如果可能的话，请找出可从任 何一草地通达另一草地的一组需管理的兽径，使其兽径长度和最小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含两个用空白分开的整数 <span style="font-family: Times New Roman;">N </span><span style="">和 </span><span style="font-family: Times New Roman;">W</span><span style="">。</span><span style="font-family: Times New Roman;">W </span><span style="">代表你的程序需要处理 的周数</span><span style="font-family: Times New Roman;">. (1 &lt;= W &lt;= 6000)</span><span style="">。</span></p>
<p>以下每处理一周，读入一行数据，代表该周新发现的兽径，由三个以空白分开 的整数分别代表该兽径的两个端点 <span style="font-family: Times New Roman;">(</span><span style="">两片草地的编号</span><span style="font-family: Times New Roman;">) </span><span style="">与该兽径的长度</span><span style="font-family: Times New Roman;">(1</span><span style="font-family: Calibri;">…</span><span style="font-family: Times New Roman;">10000)</span><span style="">。一条兽径的两个端点一定不同。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">每次读入新发现的兽径后，你的程序必须立刻输出一组兽径的长度和，此组兽径可从任何一草地通达另一草地，并使兽径长度和最小。如果不能找到一组可从任一草地通达另一草地的兽径，则输出&nbsp;&ldquo;<span style="font-family: Times New Roman;">-1</span><span style="font-family: 宋体;">&rdquo;。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> 由于题目特殊，输入输出详见下图表格。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p> 由于题目特殊，输入输出详见下图表格。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> </p>
<table>
<tbody>
<tr>
<td valign="top" width="70">
<p>輸入</p>
</td>
<td valign="top" width="91">
<p>輸出</p>
</td>
<td valign="top" width="266">
<p>說明</p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p>4 6</p>
</td>
<td valign="top" width="91">
<p> </p>
</td>
<td valign="top" width="266">
<p> </p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p>1 2 10</p>
</td>
<td valign="top" width="91">
<p> </p>
</td>
<td valign="top" width="266">
<p> </p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p> </p>
</td>
<td valign="top" width="91">
<p>-1</p>
</td>
<td valign="top" width="266">
<p>No trail connects 4 to the rest of the fields.</p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p>1 3 8</p>
</td>
<td valign="top" width="91">
<p> </p>
</td>
<td valign="top" width="266">
<p> </p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p> </p>
</td>
<td valign="top" width="91">
<p>-1</p>
</td>
<td valign="top" width="266">
<p>No trail connects 4 to the rest of the fields.</p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p>3 2 3</p>
</td>
<td valign="top" width="91">
<p> </p>
</td>
<td valign="top" width="266">
<p> </p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p> </p>
</td>
<td valign="top" width="91">
<p>-1</p>
</td>
<td valign="top" width="266">
<p>No trail connects 4 to the rest of the fields.</p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p>1 4 3</p>
</td>
<td valign="top" width="91">
<p> </p>
</td>
<td valign="top" width="266">
<p> </p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p> </p>
</td>
<td valign="top" width="91">
<p>14</p>
</td>
<td valign="top" width="266">
<p>Maintain 1 4 3, 1 3 8, and 3 2 3.</p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p>1 3 6</p>
</td>
<td valign="top" width="91">
<p> </p>
</td>
<td valign="top" width="266">
<p> </p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p> </p>
</td>
<td valign="top" width="91">
<p>12</p>
</td>
<td valign="top" width="266">
<p>Maintain 1 4 3, 1 3 6, and 3 2 3.</p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p>2 1 2</p>
</td>
<td valign="top" width="91">
<p> </p>
</td>
<td valign="top" width="266">
<p> </p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p> </p>
</td>
<td valign="top" width="91">
<p>8         </p>
</td>
<td valign="top" width="266">
<p>Maintain 1 4 3, 2 1 2, and 3 2 3.</p>
</td>
</tr>
<tr>
<td valign="top" width="70">
<p> </p>
</td>
<td valign="top" width="91">
<p>program exit</p>
</td>
<td valign="top" width="266">
<p> </p>
</td>
</tr>
</tbody>
</table>
</div>
</div>