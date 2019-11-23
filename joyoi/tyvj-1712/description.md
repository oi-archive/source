# 

 
 # 题目描述 
二维世界里，一个人要从山的一端Castle到山的另一端Village，而且他能水平地挖隧道。他爬山的速度是Vw，挖隧道的速度是Vc。这座山有N个折点。问他从Castle到Village最少所需要的时间是多少。保留六位小数。 

 
 # 输入格式 
第一行1个整数N表示有N个点。<BR>第二行2个实数表示Vw和Vc。<BR>以下N行，每行2个实数Xi和Yi表示折点的坐标。数据保证Xi是递增的。 

 
 # 输出格式 
一行1个整数，表示最少需要的时间。保留6位小数。 

 
 # 提示 
30%的数据&nbsp;2&lt;=N&lt;=6。<BR>100%的数据&nbsp;2&lt;=N&lt;=1,000，|Xi|,|Yi|&lt;=10,000。 
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
<tr><td>Sample Input 1:
3
2 1
0 0
50 50
100 0

Sample Input 2:
3
1 1
0 0
50 50
100 0

Sample Input 3:
3
1 2
0 0
50 50
100 0</td><td>Sample Output 1:
70.710678

Sample Output 2:
100.000000

Sample Output 3:
50.000000</td></tr></table>
