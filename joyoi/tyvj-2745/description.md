# 

 
 # 题目描述 
<p>
岛国Flatopia非常平整。不幸的是，Flatopia没有公共高速公路。所以Flatopia的交通非常困难。Flatopia政府意识到这个问题。他们计划建造一些公路，使任意一对城镇之间都可以开车到达。<br>Flatopia城镇都用1到n编号。每一条公路连接恰好两个城镇。所有高速公路沿着直线。所有高速公路可以双向行驶。高速公路可以自由相互交叉,但司机只能在城镇处切换高速公路。<br>Flatopia政府想要减少公路的总长度。然而,他们想要保证每一个城镇都是可达的。<br><br></p> 

 
 # 输入格式 
<p>
输入的第一行为整数N (3 <= N <= 500),表示城镇的数目。随后是N行，每一行N列，第i+1行第j列的数字表示城镇i到城镇j之间的距离（距离范围为[1, 65536])。</p> 

 
 # 输出格式 
<p>
找到一个能够使所有城镇都可达的高速公路建造方案，输出该方案中最长的公路的长度。</p> 
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
<tr><td>3
0 990 692
990 0 179
692 179 0
</td><td>692</td></tr></table>
