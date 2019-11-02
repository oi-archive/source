# 

 
 # 题目描述 
<p>
最小花费<br><br>问题描述：<br>　　在n个人中，某些人的银行账号之间可以互相转账。这些人之间转账的手续费各不相同。给定这些人之间转账时需要从转账金额里扣除百分之几的手续费，请问A最少需要多少钱使得转账后B收到100元。<br></p> 

 
 # 输入格式 
<p>
　　第一行输入两个正整数n,m，分别表示总人数和可以互相转账的人的对数。<br>　　以下m行每行输入三个正整数x,y,z，表示标号为x的人和标号为y的人之间互相转账需要扣除z%的手续费 (z < 100)。<br>　　最后一行输入两个正整数A,B。数据保证A与B之间可以直接或间接地转账。<br><br></p> 

 
 # 输出格式 
<p>
    输出A使得B到账100元最少需要的总费用。精确到小数点后8位。<br><br></p> 

 
 # 提示 
<p>
时间限制：<br>　　各测试点1秒。<br><br>内存限制：<br>　　你的程序将被分配40MB的运行空间。<br><br>数据规模：<br>　　1 <= n <= 2000<br></p> 
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
<tr><td>3 3
1 2 1
2 3 2
1 3 3
1 3

</td><td>103.07153164
</td></tr></table>
