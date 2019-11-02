# 

 
 # 题目描述 
<p>
邮递员送信（post.pas/c/cpp）<br><br>【问题描述】<br><br>　　有一个邮递员要送东西，邮局在结点1。他总共要送N-1样东西，其目的地分别是2至N。由于这个城市的交通比较繁忙，因此所有的道路都是单行的，共有M条道路，通过每条道路需要一定的时间。这个邮递员每次只能带一样东西。求送完这N-1样东西并且最终回到邮局最少需要多少时间。<br></p> 

 
 # 输入格式 
<p>
输入文件post.in第一行包含一个正整数N和M；<br>接下来M行，每行三个正整数U、V、W，表示该条道路为从U至V的，且通过这条道路需要W的时间。满足 1=<U, V<=N,1=<W<=10000，输入保证任意两点都能互相到达。<br></p> 

 
 # 输出格式 
<p>
输出文件post.out仅一行，包含一个整数，为最少需要的时间。</p> 

 
 # 提示 
<p>
数据规模：<br>对于30%的数据，满足1=< N <=200 ;<br>对于100%的数据，满足1=< N <=1000, 1=< M <=100000 .<br></p> 
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
<tr><td>5 10
2 3 5
1 5 5
3 5 6
1 2 8
1 3 8
5 3 4
4 1 8
4 5 3
3 5 6
5 4 2
</td><td>83</td></tr></table>
