<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>   X学校被抽中进行一次数学测验，该学校共有N人，每个人有一个学号，一号学生的学号是1...N号学生的学号是N.<br>   为了减轻统计的负担，该学校只会随机抽取学号连续的k人(1≤k≤n)，且将该k人的平均分统计出来。小明已经知道了所有人的成绩，小明想知道，平均分在[L,R]上的概率为多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入共2行。<br>    第一行为三个正整数，N,L,R.<br><span style="">    第二行第i个数为学号为i的学生的成绩。 </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 输出学生的分数,表示成既约分数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【task1】<br><span style="">5 2 4<br></span><span style="">1 5 4 2 3<br>【task2】<br>5 1 5<br>1 5 4 2 3 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【task1】<br>4/5<br>【task2】<br>1 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释<span style="font-family: 'Courier New';">1</span><span style="">】</span></p>
<table>
<tbody>
<tr>
<td valign="top" width="189">
<p>选取的人的分数</p>
</td>
<td valign="top" width="189">
<p>平均数<span style="font-family: 'Courier New';">(</span><span style="">保留两位小数</span><span style="font-family: 'Courier New';">)</span></p>
</td>
<td valign="top" width="189">
<p>是否位于区间[L,R]上</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>1</p>
</td>
<td valign="top" width="189">
<p>1.00</p>
</td>
<td valign="top" width="189">
<p>否</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>5</p>
</td>
<td valign="top" width="189">
<p>5.00</p>
</td>
<td valign="top" width="189">
<p>否</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>4</p>
</td>
<td valign="top" width="189">
<p>4.00</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>2</p>
</td>
<td valign="top" width="189">
<p>2.00</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>3</p>
</td>
<td valign="top" width="189">
<p>3.00</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>1,5</p>
</td>
<td valign="top" width="189">
<p>3.00</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>5,4</p>
</td>
<td valign="top" width="189">
<p>4.50</p>
</td>
<td valign="top" width="189">
<p>否</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>4,2</p>
</td>
<td valign="top" width="189">
<p>3.00</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>2,3</p>
</td>
<td valign="top" width="189">
<p>2.50</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>1,5,4</p>
</td>
<td valign="top" width="189">
<p>3.33</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>5,4,2</p>
</td>
<td valign="top" width="189">
<p>3.67</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>4,2,3</p>
</td>
<td valign="top" width="189">
<p>3.00</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>1,5,4,2</p>
</td>
<td valign="top" width="189">
<p>3.00</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>5,4,2,3</p>
</td>
<td valign="top" width="189">
<p>3.50</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>1,5,4,2,3</p>
</td>
<td valign="top" width="189">
<p>3.00</p>
</td>
<td valign="top" width="189">
<p>是</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>总方法数：<span style="font-family: 'Courier New';">15</span></p>
</td>
<td valign="top" width="189"> </td>
<td valign="top" width="189">
<p>胜利数：<span style="font-family: 'Courier New';">12</span></p>
</td>
</tr>
</tbody>
</table>
<p>胜利的概率即为：<span style="font-family: 'Courier New';">12/15=4/5</span><br><span style="">如果概率为</span><span style="font-family: 'Courier New';">0%</span><span style="">或</span><span style="font-family: 'Courier New';">100%</span><span style="">，输出</span><span style="font-family: 'Courier New';">0</span><span style="">或</span><span style="font-family: 'Courier New';">1</span><span style="">。<br></span></p>
<p> </p>
<p>【数据范围】</p>
<p>对于3<span style="font-family: 'Courier New';">0%</span><span style="">的数据，</span><span style="font-family: 'Courier New';">N≤10,000</span></p>
<p> </p>
<p>对于<span style="font-family: 'Courier New';">100%</span><span style="">的数据，</span><span style="font-family: 'Courier New';">N≤1,000,000</span><span style="">。</span></p>
<p><span style=""> </span></p>
</div>
</div>