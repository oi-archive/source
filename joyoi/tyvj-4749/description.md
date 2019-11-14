# 

 
 # 题目背景 
<p>NOIP春季系列课程</p> 

 
 # 题目描述 
<p>这个故事是关于小F的，它有一个怎么样的故事呢。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;小F是一个田径爱好者，这天它们城市里正在举办马拉松比赛，这个城市可以被看作是n个点m条带权有向边组成的图。马拉松比赛的终点只有一个：点S。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;有k个人参加了这场马拉松，小F所在的城市的马拉松与正常的马拉松不一样，每个人的起点都是不相同的，具体地，第i个人从第{ai}个城市出发，并且第i个人的速度是{vi}。每个人当然是会沿着最短路跑到S点，如果一个人跑步的距离是s，速度是v，那么他所花费的时间为s/v。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;现在小F想知道，谁是最快到达终点的。若有多个同时到达终点的，就求跑的路最长的，如果有多个同时到达终点且跑的路最长的，就求编号最大的。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;小F想知道那个人的编号是多少。</p>

<p>&nbsp;</p> 

 
 # 输入格式 
<p>第一行3个数字，n,k,m，表示点的个数，跑步的人数，以及路径的条数。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来一行m行，每行3个数ai,bi,ci表示有一条从ai到bi长为ci的有向路径。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来一行一个数S。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来一行k个数，表示每个人的起点xi。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来一行k个数，表示每个人的速度vi。</p> 

 
 # 输出格式 
<p>输出一个数表示答案。</p>

<p>&nbsp;</p> 

 
 # 提示 
<p>输入样例</p>

<p>3&nbsp;2&nbsp;3</p>

<p>1&nbsp;2&nbsp;2</p>

<p>1&nbsp;3&nbsp;3</p>

<p>2&nbsp;3&nbsp;1</p>

<p>3</p>

<p>2&nbsp;1</p>

<p>1&nbsp;3</p>

<p>&nbsp;</p>

<p>输出样例</p>

<p>2</p>

<p>&nbsp;</p>

<p>数据范围</p>

<p>对于30%的数据n&lt;=5，m&lt;=10。</p>

<p>对于100%的数据n&lt;=300，m&lt;=5000。0&lt;=ci&lt;=100，1&lt;=xi,S&lt;=n，1&lt;=vi&lt;=100，1&lt;=k&lt;=n。</p>

<p>&nbsp;</p>

<p>&nbsp;</p> 
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
<tr><td>5 2 10
5 1 9
1 2 81
2 3 30
2 1 46
1 4 45
2 4 48
5 1 93
2 5 61
2 5 21
3 5 45
1
3 5 
18 29 </td><td>2
</td></tr></table>
