# 

 
 # 题目描述 
<p>sideman&nbsp;做好了回到&nbsp;Gliese&nbsp;星球的硬件准备，但是&nbsp;sideman&nbsp;的导航系统还没有完全设计好。为了方便起见，&nbsp;我们可以认为宇宙是一张有&nbsp;N&nbsp;个顶点和&nbsp;M&nbsp;条边的带权无&nbsp;向图，顶点表示各个星系，两个星系之间有边就表示两个&nbsp;星系之间可以直航，而边权则是航行的危险程度。&nbsp;sideman&nbsp;现在想把危险程度降到最小，具体地来说，&nbsp;就是对于若干个询问(A,&nbsp;B)，sideman&nbsp;想知道从顶点&nbsp;A&nbsp;航行&nbsp;到顶点B所经过的最危险的边的危险程度值最小可能是多&nbsp;少。作为&nbsp;sideman&nbsp;的同学，你们要帮助&nbsp;sideman&nbsp;返回家园，&nbsp;兼享受安全美妙的宇宙航行。所以这个任务就交给你了。</p> 

 
 # 输入格式 
<p>第一行包含两个正整数&nbsp;N&nbsp;和&nbsp;M，表示点数和边数。&nbsp;之后&nbsp;M&nbsp;行，每行三个整数&nbsp;A，B&nbsp;和&nbsp;L，表示顶点&nbsp;A&nbsp;和&nbsp;B&nbsp;之间有一条边长为&nbsp;L&nbsp;的边。顶&nbsp;点从&nbsp;1&nbsp;开始标号。&nbsp;下面一行包含一个正整数&nbsp;Q，表示询问的数目。&nbsp;之后&nbsp;Q&nbsp;行，每行两个整数&nbsp;A&nbsp;和&nbsp;B，表示询问&nbsp;A&nbsp;和&nbsp;B&nbsp;之间最危险的边危险程度的可能最&nbsp;小值。</p> 

 
 # 输出格式 
<p>对于每个询问，在单独的一行内输出结果。如果两个顶点之间不可达，输出&nbsp;impossible。</p> 

 
 # 提示 
<p>对于&nbsp;40%&nbsp;的数据，满足&nbsp;N&le;1000，M&le;3000，Q&le;1000。&nbsp;</p>

<p>对于&nbsp;80%&nbsp;的数据，满足&nbsp;N&le;10000，M&le;10^5，Q&le;1000。&nbsp;</p>

<p>对于&nbsp;100%&nbsp;的数据，满足&nbsp;N&le;10^5，M&le;3&times;10^5，Q&le;10^5，L&le;10^9。数据不保证没有重&nbsp;边和自环。</p>

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
<tr><td>4 5
1 2 5
1 3 2 
2 3 11 
2 4 6 
3 4 4
3 
2 3 
1 4 
1 2 </td><td>5
4
5</td></tr></table>
