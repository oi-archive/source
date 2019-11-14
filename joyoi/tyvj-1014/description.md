# 

 
 # 题目背景 
太原成成中学第2次模拟赛&nbsp;第四道 

 
 # 题目描述 
乘法游戏是在一行牌上进行的。每一张牌包括了一个正整数。在每一个移动中，玩家拿出一张牌，得分是用它的数字乘以它左边和右边的数，所以不允许拿第1张和最后1张牌。最后一次移动后，这里只剩下两张牌。<BR>&nbsp;&nbsp;&nbsp;&nbsp;你的目标是使得分的和最小。<BR>&nbsp;&nbsp;&nbsp;&nbsp;例如，如果数是10&nbsp;1&nbsp;50&nbsp;20&nbsp;5，依次拿1、20、50，总分是&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;10*1*50+50*20*5+10*50*5=8000<BR>&nbsp;&nbsp;&nbsp;&nbsp;而拿50、20、1，总分是1*50*20+1*20*5+10*1*5=1150。&nbsp;<BR> 

 
 # 输入格式 
输入文件的第一行包括牌数(3&lt;=n&lt;=100)，第二行包括N个1-100的整数，用空格分开。 

 
 # 输出格式 
输出文件只有一个数字：最小得分 
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
<tr><td>6
10 1 50 50 20 5
</td><td>3650
</td></tr></table>
