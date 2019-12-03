# 

 
 # 题目描述 
<p>
贱买贵卖（buylow.pas\c\cpp） <br><br>【题目描述】<br>　　中国最近的房价极其不稳定，时高时低，symbol灵机一动，价格低时买，高时卖岂不是可以赚一笔，但毕竟有风险，他想先研究下最近一段N天的价格，由于资金短缺，一次只能买一套房，要等这套房卖掉才能买下一套。<br>　　由于symbol还有其他的业务，他最多一共有K天去房地产市场，每次去要么是买房要么是卖房。<br>　　你的任务是帮symbol计算出最多可以获得的利润。<br></p> 

 
 # 输入格式 
<p>
　　输入文件buylow.in第一行包含两个整数N,K,N表示给定最近价格的天数，K表示去市场的最多次数。接下来N行，第i+1行每行一个正整数，表示第i天的价格。</p> 

 
 # 输出格式 
<p>
　　输出文件buylow.out输出一个非负整数表示最多可以获得的利润。</p> 

 
 # 提示 
<p>
【数据说明】<br>　　100%的数据 N<=400 and K<=400<br></p> 
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
<tr><td>【样例输入1】
10 5
10
12
8
11
11
10
12
15
13
10

【样例输入2】
10 6
10
12
8
11 
11
10
12
15
13
10
</td><td>【样例输出1】
9

【样例输出1】
10</td></tr></table>
