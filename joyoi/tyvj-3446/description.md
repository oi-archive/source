# 

 
 # 题目描述 
<p>
Computia（cchkk.pas\c\cpp）<br><br>【题目描述】<br>　　在著名的Computia城里，所有的道路都是单向行驶的。<br>　　Computia城的市长先生认为在这样的设置下，在任意两个路口间都有存在合法的路径使得他们相通。但是反对派的人却不同意这点。所以必须要有一个电脑程序来判断市长先生对不对。<br></p> 

 
 # 输入格式 
<p>
　　输入文件Computia.in第一行，两个整数，N(<=10000），M(<=200000)。(每个路口从0开始编号到n-1)<br>　　接下来有M行，每行有两个整数x,y,分别代表两个路口，代表着从x可以到y。<br></p> 

 
 # 输出格式 
<p>
　　输出文件Computia.out:<br>　　如果市长对了，你就输出"Succeed".<br>　　如果市长错了，你就输出"Beiju".并输出这城市被划分成了多少块（一块当中的所有路口都可以相互到达，不同块间的点不能相互到达）。<br></p> 
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
<tr><td>【输入样例1】
5 10
2 4
4 1
3 1
1 4
4 2
3 4
0 3
4 3
0 4
0 1

【输入样例2】
5 10
1 0
4 2
0 2
1 4
4 3
3 4
3 1
0 3
2 3
1 3
</td><td>
【输出样例1】
Beiju 2

【输出样例2】
Succeed
</td></tr></table>
