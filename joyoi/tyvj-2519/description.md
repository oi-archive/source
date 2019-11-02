# 

 
 # 题目描述 
<p>
<br>正如你所知，奶牛们没有手指以至于不能玩“石头剪刀布”来任意地决定例如<br>谁先挤奶的顺序。她们甚至也不能通过仍硬币的方式。<br><br>所以她们通过"round number"竞赛的方式。第一头牛选取一个整数，小于20亿。<br>第二头牛也这样选取一个整数。如果这两个数都是 "round numbers"，那么第一<br>头牛获胜，否则第二头牛获胜。<br><br>如果一个正整数N的二进制表示中，0的个数大于或等于1的个数，那么N就被称为<br>"round number" 。例如，整数9，二进制表示是1001，1001 有两个'0'和两个'1';<br> 因此，9是一个round number。26 的二进制表示是 11010 ; 由于它有2个'0'和<br>3个'1'，所以它不是round number。<br><br>很明显，奶牛们会花费很大精力去转换进制，从而确定谁是胜者。 Bessie 想要<br>作弊，而且认为只要她能够知道在一个指定区间范围内的"round numbers"个数。<br><br>帮助她写一个程序，能够告诉她在一个闭区间中有多少Hround numbers。区间是<br>[start, finish]，包含这两个数。 (1 <= Start < Finish <= 2,000,000,000)<br></p> 

 
 # 输入格式 
<p>
* Line 1: 两个用空格分开的整数，分别表示Start 和 Finish。<br><br></p> 

 
 # 输出格式 
<p>
<br><br>* Line 1:  Start..Finish范围内round numbers的个数<br><br></p> 
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
<tr><td>2 12
</td><td>
6

输出解释:

 2    10  1x0 + 1x1  ROUND
 3    11  0x0 + 2x1  NOT round
 4   100  2x0 + 1x1  ROUND
 5   101  1x0 + 2x1  NOT round
 6   110  1x0 + 2x1  NOT round
 7   111  0x0 + 3x1  NOT round
 8  1000  3x0 + 1x1  ROUND
 9  1001  2x0 + 2x1  ROUND
10  1010  2x0 + 2x1  ROUND
11  1011  1x0 + 3x1  NOT round
12  1100  2x0 + 2x1  ROUND</td></tr></table>
