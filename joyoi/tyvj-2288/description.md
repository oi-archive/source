# 

 
 # 题目描述 
<p>
邮递员每天给N个村子的人送信,每个村子可能在某个十字路口上,或一条路的中央.<br>村子里的人都希望早点收到信,因此与邮递员达成一个协议:每个村子都有一个期望值Wi,如果这个村子是邮递员经过的第K个不同的村子,那么如果K<=Wi,则村子给他Wi-K元,反之他给村子K-Wi元.别外每经过一条不同的路,邮局会给他1元钱,而邮局的规定是每条路(共M条路)都至少经过一次,邮递员要怎么走才能拿到最多的钱.</p> 

 
 # 输入格式 
<p>
第一行给出N,M代表有多少个点,多少条边.<br>下面N个数,代表Wi,Wi在[1,1000]<br>下面M行,代表图的结构.</p> 

 
 # 输出格式 
<p>
最多可以赚到多少钱....</p> 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-2288/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjI4OC9wcm9ibGVtc19pbWFnZXMvMjY1OC8xMzc5LmpwZw==.jpg"><br><br></p> 
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
<tr><td>6 7
1
7
4
10
20
5
2 4
1 5
2 1
4 5
3 6
1 6
1 3</td><td>7</td></tr></table>
