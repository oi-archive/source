# 

 
 # 题目描述 
<p>
 有n根木棍, 第i根木棍的长度为Li,n根木棍依次连结了一起, 总共有n-1个连接处. 现在允许你最多砍断m个连接处, 砍完后n根木棍被分成了很多段,要求满足总长度最大的一段长度最小, 并且输出有多少种砍的方法使得总长度最大的一段长度最小.<br></p> 

 
 # 输入格式 
<p>
输入文件第一行有2个数n,m.<br>接下来n行每行一个正整数Li,表示第i根木棍的长度.<br></p> 

 
 # 输出格式 
<p>
输出有2个数, 第一个数是总长度最大的一段的长度最小值, 第二个数是有多少种砍的方法使得满足条件.<br></p> 
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
<tr><td>3 2                           
1 
1
10
</td><td>10 2

两种砍的方法: (1)(1)(10)和(1 1)(10)
数据范围  
   n<=50000, 0<=m<=min(n-1,1000).
   1<=Li<=1000.</td></tr></table>
