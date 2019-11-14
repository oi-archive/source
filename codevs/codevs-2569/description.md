<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""> </p>
<p style=""><span style="">天平的两边有时不一定只能挂物品，还可以继续挂着另一个天平，现在给你一些天平的情况和它们之间的连接关系，要求使得所有的天平都能平衡时所需物品的总重量最轻，一个天平平衡当且仅当“左端点的重量×左端点到支点的距离<span style="font-family: Times New Roman;">=</span><span style="">右端点的重量×右端点到支点的距离”。</span></span></p>
<p style=""> </p>
<p style=""><span style="">注意：题目中的输入保证这些天平构成一个整体。</span></p>
<p style=""> </p>
<!--EndFragment-->

<img src="/source/codevs/codevs-2569/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yNTY5L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2ODM2NDA2MS45MzAuMDAzNjA5NzI5NDYyMjUuUE5H.PNG" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行包含一个<span style="font-family: Times New Roman;">N</span><span style="">（</span><span style="font-family: Times New Roman;">N</span><span style="">≤</span><span style="font-family: Times New Roman;">100</span><span style="">），表示天平的数量，天平编号为</span><span style="font-family: Times New Roman;">1</span><span style="">到</span><span style="font-family: Times New Roman;">N</span><span style="">，接下来包含</span><span style="font-family: Times New Roman;">N</span><span style="">行描述天平的情况，每行</span><span style="font-family: Times New Roman;">4</span><span style="">个整数</span><span style="font-family: Times New Roman;">P,Q,R,B</span><span style="">，</span><span style="font-family: Times New Roman;">P</span><span style="">和</span><span style="font-family: Times New Roman;">Q</span><span style="">表示横杆上支点到左端点的距离与到右端点的距离的比例为</span><span style="font-family: Times New Roman;">P:Q</span><span style="">，</span><span style="font-family: Times New Roman;">R</span><span style="">表示左边悬挂的情况，如果</span><span style="font-family: Times New Roman;">R=0</span><span style="">说明悬挂物品，否则表示左边悬挂的是天平</span><span style="font-family: Times New Roman;">R</span><span style="">；</span><span style="font-family: Times New Roman;">B</span><span style="">表示右边悬挂的情况，如果</span><span style="font-family: Times New Roman;">B=0</span><span style="">表示右边悬挂的是物品，否则右边悬挂的是天平</span><span style="font-family: Times New Roman;">B</span><span style="">。</span></span></p>
<p style=""><span style="">对于所有的输入，保证<span style="font-family: Times New Roman;">W*L&lt;2^31</span><span style="">，其中</span><span style="font-family: Times New Roman;">W</span><span style="">为最轻的天平重量，而</span><span style="font-family: Times New Roman;">L</span><span style="">为输入中描述左右比例时出现的最大值。</span></span></p>
<p style=""> </p>
<!--EndFragment-->

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: '宋体'; font-size: 14pt; mso-spacerun: 'yes';">输出一个整数表示使得所有天平都平衡所需最轻的物品总重量。</span></p>
<!--EndFragment-->

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""> </p>
<table>
<tbody>
<tr>
<td valign="top" width="267">
<p>4</p>
<p>3 2 0 4</p>
<p>1 3 0 0</p>
<p>4 4 2 1</p>
<p>2 2 0 0</p>
</td>
</tr>
</tbody>
</table>
<p style=""> </p>
<!--EndFragment-->

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<table>
<tbody>
<tr>
<td valign="top" width="264">
<p>40</p>
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
<p>NO</p>
</div>
</div>