# 题目描述


<p>
<strong>题目描述</strong>：<strong> </strong><br/>
你在一个组合式家具厂工作，这种组合式家具由各种形状不同的组件组成，例如：<br/>
<img alt="1" src="http://www.smartoj.com/ajax/Image.ashx?id=34" height="111" width="323"/><br/>
图1 三种不同形状的组件<br/>
这些组件生产出来后将被自动装箱，组件按生产的次序落下，第一个组件落在箱子底部，其后的组件依次落下，直至组件接触到之前装入的组件或箱子底部。例如，假设组件按图1从左至右的次序生产出来，装箱结果将如图2左所示。假如按图1从右至左的次序生产出来，装箱结果将如图2右所示。<br/>
<img alt="2" src="http://www.smartoj.com/ajax/Image.ashx?id=35" height="137" width="143"/><br/>
图2 不同的生产次序导致两种不同的装箱结果<br/>
由于箱子高度有限，如图2左，三个组件已经超过了箱子的高度，这种情况第三个组件及之后的组件需要用新的箱子来装。<br/>
你的工作是为自动装箱系统编写程序，根据组件生产的次序，输出装完这些组件后，每个箱子的组件堆叠的高度。<br/>
<strong>输入格式</strong>（Pack.in）：<br/>
第一行是用空格分隔的三个整数n,w,b。n是一套家具的组件数，1&lt;=n&lt;=100，w和b是箱子的宽和高，1&lt;=w&lt;=10，1&lt;=b&lt;=100。接下来是n个组件的形状描述，按生产的次序排列，每个组件描述第一行是一个整数h，1&lt;=h&lt;=10且h&lt;=b，接下来h行每行w个字符，描述组件的形状，“X”代表组件的部分，“.”代表空间。<br/>
<strong>输出格式</strong>（Pack.out）：<br/>
m个整数（m代表装箱所需的箱子数），按装箱的次序输出m个箱子里组件的高度。<br/>
<strong>样例 </strong> 
</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="284">
<br/>
Pack.in
</td>
<td valign="top" width="284">
<p>
Pack.out
</p>
</td>
</tr>
<tr>
<td valign="top" width="284">
<p>
3 5 12<br/>
5<br/>
XXXXX<br/>
.XXXX<br/>
..XXX<br/>
...XX<br/>
....X<br/>
4<br/>
XXX..<br/>
..X..<br/>
..XXX<br/>
..X..<br/>
6<br/>
X....<br/>
X....<br/>
X....<br/>
X....<br/>
X....<br/>
XXXXX
</p>
</td>
<td valign="top" width="284">
<p>
9 6
</p>
</td>
</tr>
</tbody>
</table>
