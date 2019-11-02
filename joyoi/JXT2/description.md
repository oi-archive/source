# 
**Description
小明家有一个非常旧的钟表，表盘上的数字已经看不清了，但是时针依然运转完好，于是小明想根据时针的角度来判断现在的时间，请你编程来帮助他。
当时针指向正右方，也就是3点钟的时候，我们规定此时为0度。因此，当时针转过80度的时候，此时的时间在0点钟与1点钟之间。
注意我们规定没有12点钟，要用0点钟来表示。
Input
输入包含多组测试数据。
每组输入一个整数a（0<=a<=360），表示时针转过的角度。当a=-1时，输入结束。
Output
对于每组输入，输出现在的时间，格式有两种，如下：
（1）Exactly x o'clock
（2）Between x o'clock and y o'clock
注意，当输出为第二种格式时，x点钟应该是y点钟之前一个小时的那个整点，所以你不能输出例如“Between 3 o'clock and 2 o'clock”这种结果。**# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>90
245
-1</td><td>Exactly 0 o'clock
Between 6 o'clock and 7 o'clock</td></tr></table>
