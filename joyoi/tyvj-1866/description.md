# 

 
 # 题目描述 
Freda喜欢研究各种各样奇奇怪怪的东西~<BR>一天，Freda研究了一个关于哈密顿路的问题。<BR>如果一条路径满足：不经过重复顶点、不经过重复边、首尾相连，&nbsp;那么称这条路径为简单环。<BR>给出一张无向图，求这个无向图当中长度不小于3（即经过不少于3个点）的简单环的个数。 

 
 # 输入格式 
第一行两个整数N、M，表示图有N个点、M条边。<BR>接下来M行，每行两个整数a、b，表示顶点a和顶点b之间有一条无向边。<BR>数据保证没有自环和重边的出现。 

 
 # 输出格式 
一行一个整数，表示无向图当中长度不小于3的简单环的个数。 

 
 # 提示 
七个环分别为：<BR>1-&gt;2-&gt;3-&gt;1<BR>1-&gt;2-&gt;4-&gt;1<BR>1-&gt;3-&gt;4-&gt;1<BR>2-&gt;3-&gt;4-&gt;2<BR>1-&gt;2-&gt;3-&gt;4-&gt;1<BR>1-&gt;2-&gt;4-&gt;3-&gt;1<BR>1-&gt;3-&gt;2-&gt;4-&gt;1<BR>对于50%的数据,保证答案不大于10^6.<BR>对于100%的数据,N&lt;=20,&nbsp;保证答案可以用64位整形存储,From&nbsp;---&nbsp;This_poet<BR>Contact&nbsp;me&nbsp;---&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<BR>My&nbsp;Blog&nbsp;---&nbsp;http://thispoet.blogcn.com 
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
<tr><td>4 6
1 2
1 3
1 4
2 3
2 4
3 4
</td><td>7
</td></tr></table>
