# 

 
 # 题目背景 
水叮当得到了一块五颜六色的格子形地毯作为生日礼物，更加特别的是，地毯上格子的颜色还能随着踩踏而改变。<BR>为了讨好她的偶像虹猫，水叮当决定在地毯上跳一支轻盈的舞来卖萌~~~ 

 
 # 题目描述 
地毯上的格子有N行N列，每个格子用一个0~5之间的数字代表它的颜色。<BR>水叮当可以随意选择一个0~5之间的颜色，然后轻轻地跳动一步，左上角的格子所在的联通块里的所有格子就会变成她选择的那种颜色。这里连通定义为：两个格子有公共边，并且颜色相同。<BR>由于水叮当是施展轻功来跳舞的，为了不消耗过多的真气，她想知道最少要多少步才能把所有格子的颜色变成一样的。<BR> 

 
 # 输入格式 
每个测试点包含多组数据。<BR>每组数据的第一行是一个整数N，表示地摊上的格子有N行N列。<BR>接下来一个N*N的矩阵，矩阵中的每个数都在0~5之间，描述了每个格子的颜色。<BR>N=0代表输入的结束。 

 
 # 输出格式 
对于每组数据，输出一个整数，表示最少步数。 

 
 # 提示 
对于30%的数据，N&lt;=5<BR>对于50%的数据，N&lt;=6<BR>对于70%的数据，N&lt;=7<BR>对于100%的数据，N&lt;=8，每个测试点不多于20组数据。<BR><BR>第二组样例解释：<BR>0&nbsp;1&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;1&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;2&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;1&nbsp;1<BR>1&nbsp;1&nbsp;2&nbsp;&nbsp;--&gt;&nbsp;1&nbsp;1&nbsp;2&nbsp;&nbsp;--&gt;&nbsp;2&nbsp;2&nbsp;2&nbsp;&nbsp;--&gt;&nbsp;1&nbsp;1&nbsp;1<BR>2&nbsp;2&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;2&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;2&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;1&nbsp;1 
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
<tr><td>2
0 0 
0 0
3
0 1 2
1 1 2
2 2 1
0
</td><td>0
3
</td></tr></table>
