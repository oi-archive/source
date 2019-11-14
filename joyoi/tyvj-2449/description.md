# 

 
 # 题目描述 
<p>
每天,农夫John需要经过一些道路去检查牛棚N里面的牛. 农场上有M(1<=M<=50,000)条双向<br>泥土道路,编号为1..M. 道路i连接牛棚P1_i和P2_i (1 <= P1_i <= N; 1 <= P2_i<= N).<br>John需要T_i (1 <= T_i <= 1,000,000)时间单位用道路i从P1_i走到P2_i或者从P2_i<br>走到P１_i<br><br>他想更新一些路经来减少每天花在路上的时间.具体地说,他想更新K (1 <= K <= 20)条路经，<br>将它们所须时间减为０．帮助FJ选择哪些路经需要更新使得从１到N的时间尽量少.<br><br></p> 

 
 # 输入格式 
<p>
* 第一行: 三个空格分开的数: N, M, 和 K<br><br>* 第2..M+1行: 第i+1行有三个空格分开的数：P1_i, P2_i, 和 T_i<br><br></p> 

 
 # 输出格式 
<p>
* 第一行: 更新最多Ｋ条路经后的最短路经长度．</p> 

 
 # 提示 
<p>
K是1; 更新道路3->4使得从３到４的时间由１００减少到０. 最新最短路经是1->3->4,总用时<br>为１单位.<br>N<=10000</p> 
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
<tr><td>4 4 1
1 2 10
2 4 10
1 3 1
3 4 100
</td><td>1
</td></tr></table>
