# 

 
 # 题目描述 
<p>
    奶牛们又在玩一种无聊的数字游戏。输得很郁闷的贝茜想请你写个程序来帮她在开局时预测结果。在游戏的开始，每头牛都会得到一个数N(1<=N<=1,000,000)。此时奶牛们的分数均为0。如果N是奇数，那么奶牛就会把它乘以3后再加1。如果N是偶数，那么这个数就会被除以2。数字每变动一次，这头奶牛就得到1分。当N的值等于1时，游戏结束，此时的分数就是这头奶牛在这局游戏中的最终得分。<br><br>    以下是N的初始值为5时，一局游戏的完整过程：<br> <br>        N    操作后所得数     注释     总分<br>        5        16          3*5+1       1<br>       16         8           16/2       2<br>        8         4            8/2       3<br>        4         2            4/2       4<br>        2         1            2/2       5<br><br>    这头奶牛的最终得分是5。<br></p> 

 
 # 输入格式 
<p>
* 第1行: 一个正整数，N<br><br></p> 

 
 # 输出格式 
<p>
* 第1行: 输出一个正整数N，即奶牛在这局游戏中的最终得分<br><br></p> 
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
<tr><td>112
</td><td>20</td></tr></table>
