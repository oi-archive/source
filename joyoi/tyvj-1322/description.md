# 

 
 # 题目描述 
天凯是苏联的总书记。苏联有n个城市，某些城市之间修筑了公路。任意两个城市都可以通过公路直接或者间接到达。<BR>天凯发现有些公路被毁坏之后会造成某两个城市之间无法互相通过公路到达。这样的公路就被称为dangerous&nbsp;pavement。<BR>为了防止美帝国对dangerous&nbsp;pavement进行轰炸，造成某些城市的地面运输中断，天凯决定在所有的dangerous&nbsp;pavement驻扎重兵。可是到底哪些是dangerous&nbsp;pavement呢？你的任务就是找出所有这样的公路。 

 
 # 输入格式 
输入n和m，表示n个城市，m条道路<BR>下面m行每行两个数，表示两个城市间有道路 

 
 # 输出格式 
对dangerous&nbsp;pavement按照第一关键字为起点，第二关键字为终点，进行字典序排序后输出全部dangerous&nbsp;pavement路径。请注意：输出时，所有的数对&lt;a,b&gt;必须按照a从小到大排序输出；如果a相同，则根据b从小到大排序。 

 
 # 提示 
n&lt;=200<BR>m&lt;=500 
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
<tr><td>6 6
1 2
2 3
2 4
3 5
4 5
5 6
</td><td>1 2
5 6
</td></tr></table>
