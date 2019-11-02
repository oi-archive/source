# 

 
 # 题目描述 
<p>
N头牛（2<=n<=1000）别人被标记为1到n，在同样被标记1到n的n块土地上吃草，第i头牛在第i块牧场吃草。<br><br>这n块土地被n-1条边连接。<br><br>奶牛可以在边上行走，第i条边连接第Ai，Bi块牧场，第i条边的长度是Li（1<=Li<=10000）。<br><br>这些边被安排成任意两头奶牛都可以通过这些边到达的情况，所以说这是一棵树。<br><br>这些奶牛是非常喜欢交际的，经常会去互相访问,他们想让你去帮助他们计算Q(1<=q<=1000)对奶牛之间的距离。<br></p> 

 
 # 输入格式 
<p>
*第一行：两个被空格隔开的整数：N和Q<br><br>*第二行到第n行：第i+1行有两个被空格隔开的整数：AI，BI，LI<br><br>*第n+1行到n+Q行：每一行有两个空格隔开的整数：P1，P2，表示两头奶牛的编号。<br><br><br></p> 

 
 # 输出格式 
<p>
*第1行到第Q行：每行输出一个数，表示那两头奶牛之间的距离。<br><br></p> 
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
<tr><td>4 2
2 1 2
4 3 2
1 4 3
1 2
3 2
</td><td>2
7</td></tr></table>
