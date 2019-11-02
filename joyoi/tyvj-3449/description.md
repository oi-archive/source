# 

 
 # 题目描述 
<p>
割，割点<br>　　天凯是苏联的总书记。苏联有n个城市，某些城市之间修筑了公路。任意两个城市都可以通过公路直接或者间接到达。天凯发现有些公路被毁坏之后会造成某两个城市之间无法互相通过公路到达。这样的公路就被称为dangerous pavement。为了防止美帝国对dangerous pavement进行轰炸，造成某些城市的地面运输中断，天凯决定在所有的dangerous pavement驻扎重兵。可是到底哪些是dangerous pavement呢？你的任务就是找出所有这样的公路。<br><br></p> 

 
 # 输入格式 
<p>
　　第一行n，m(1 <= n <= 150, 1 <= m <= 5000)，分别表示有n个城市，总共m条公路。<br>　　以下m行每行两个整数a, b，表示城市a和城市b之间修筑了直接的公路。<br></p> 

 
 # 输出格式 
<p>
　　输出有若干行。每行包含两个数字a,b( a < b ) ，表示<a,b>是dangerous pavement。请注意：输出时，所有的数对 < a , b > 必须按照a从小到大排序输出；如果a相同，则根据b从小到大排序。<br><br></p> 
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
<tr><td>Danger.in
6 6
1 2
2 3
2 4
3 5
4 5
5 6
</td><td>Dager.out
1 2
5 6
</td></tr></table>
