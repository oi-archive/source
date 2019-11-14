# 

 
 # 题目描述 
<p>
从前有一个迷宫，迷宫的外形就像一棵带根树，每个结点（除了叶子结点外）恰好有K个儿子。<br>一开始你在根结点，根结点的K个儿子分别标记为‘A’, ‘B’, ‘C’….,而结点‘A’的K个儿子结点分别标记为‘AA’,‘AB’,‘AC’……，依此类推。这棵树一共有L层。<br>现在你事先知道M个结点中有金子，并且你可以派出N个机器人去收集金子。首先你可以分别指定每一个机器人的目标结点，于是这些机器人就会收集从根结点到其目标结点这条路径上（包括目标结点）所有的金子，但是每个位置的金子只能被收集一次。<br>现在你需要制定一个目标的分配方案，使得收集到的金子最多。<br></p> 

 
 # 输入格式 
<p>
输入的第一行有4个整数：M,K,L,N。对应题目描述中的参数。<br>接下来M行，每行是一个字符串，表示所对应的结点上有金子。<br></p> 

 
 # 输出格式 
<p>
输出利用N个机器人所能捡到时最多几个结点上的金子。</p> 

 
 # 提示 
<p>
<br><left><img src="/source/joyoi/tyvj-2990/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk5MC9wcm9ibGVtc19pbWFnZXMvMzU5OS90LmJtcA==.bmp"></img></left></p> 
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
<tr><td>样例输入1：
5 3 3 1
ACC
ACB
AB
AC
A

样例输入 2：
5 3 3 2
ACC
ACB
AB
AC
A
</td><td>样例输出1：
3
样例输出2：
4</td></tr></table>
