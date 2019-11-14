# 

 
 # 题目描述 
<p>
Sramoc问题 <br>　　问题描述：Sramoc ( K , M ) 表示用数字0、1、２…、K-1组成的自然数中能被M整除的最小数。给定 K、M，求Sramoc ( K,M )。例如 K=2，M=7的时候，Sramoc( 2 , 7 ) = 1001。<br><br></p> 

 
 # 输入格式 
<p>
　　一行，为两个整数K、M，两数之间有一个空格，满足2<=K<=10、1<=M<=1000。</p> 

 
 # 输出格式 
<p>
　　一行，结果值。</p> 

 
 # 提示 
<p>
　　（提示：由于本题数据规模不大，可以从个位开始向高位逐位从0到K－1枚举，直到找到能M整除的数为止）。</p> 
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
<tr><td>2 7</td><td>1001</td></tr></table>
