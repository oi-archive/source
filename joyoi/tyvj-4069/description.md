# 

 
 # 题目描述 
<p><span style="line-height: 20.7999992370605px;">桌子上有N个方块排成一行，每个方块上都有一个小写字母。你的任务是将这些方块重新排列成某个给定的目标状态。在重新排列的时候你只能够交换相邻两个方块，并且这两个方块上的字母属于一个可交换对。在此我们会给出M个可交换对。可能有人不禁要发问：为什么要这么规定？说实在我也搞不清楚。总之现在你需要用最少的交换次数达到目的，或者直截了当地说不存在这种可能性。</span></p> 

 
 # 输入格式 
<p>输入第一行包含一个仅由小写字母组成的字符串，表示方块的初始状态，第二行用同样的方式表示目标状态。第三行为一个整数M，以下M行每行包含两个小写字母表示可交换对，中间没有任何多余字符。</p> 

 
 # 输出格式 
<p>如果无法达到目的，则输出-1；否则输出最少的交换次数，鉴于答案可能很大，你只需要输出答案模2<sup>32</sup>的余数即可。</p> 

 
 # 提示 
<p>对于20%的数据，有1&nbsp;&le;&nbsp;N&nbsp;&le;&nbsp;1000；</p>

<p>对于100%的数据，有1&nbsp;&le;&nbsp;N&nbsp;&le;&nbsp;100000。</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>abccba3abcbca</td><td>3</td></tr></table>
