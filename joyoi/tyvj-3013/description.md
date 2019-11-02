# 

 
 # 题目描述 
<p>
【问题描述】<br>    “话说有一天下流星雨，天上掉下来一个玉佩，它拥有无穷的力量。不过由于进入大气层的时候受到过于大的压力而导致被分成了4个部分散落在人间……”<br>     春哥对你说了这个传说，你抱着“信春鸽，得永生”的信念来到了这块散落着的玉佩的土地上。<br>这是一块正六边形的土地，到达的时候你发现了它已经变成了4个部分分散在各个角落。经过探索你发现了这个玉佩只有把4块全部连到 一起的时候才会发出无穷的力量，但是由于某种因素和技术原因，我们并不能移动任意一个玉佩的部分，只能通过购买一种连接用材料铺盖在土地上，把它们全部连在一起才行。<br>    现在需要找到最少要多少钱才可以得到这无穷的力量。<br><br>    比如说下图，玉佩被分成了4个部分ABCD，最少需要铺盖4块土地（用x标出）就可以把它们全部连接起来。<br><br><center><img src="/source/joyoi/tyvj-3013/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzAxMy9wcm9ibGVtc19pbWFnZXMvMzYyNi9wMS5qcGc=.jpg"></img></center></p> 

 
 # 输入格式 
<p>
    本题有多组测试数据。<br>    每组测试数据满足以下格式：<br>    第一行一个整数N，表示这块土地的大小；若N=0，表示输入结束。<br>    接着2*N-1行每行若干个数字描述了一个正六边形，若是一个字母（ABCD）就表示这块土地属于玉佩的某个部分，否则就表示这里是一块空地。<br></p> 

 
 # 输出格式 
<p>
    输出包括若干行，每行一句话“You have to buy x parcels.”表示第I组测试数据最少需要铺x个连通材料（不包含引号）。</p> 

 
 # 提示 
<p>
对于100%的数据，N≤20，测试数据数≤10</p> 
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
<tr><td>4 
    B . . C 
   . . . . C 
  . A . . C . 
 . A A . . . .
  . A . . . . 
   . . . D D 
    . . . . 
0
</td><td>You have to buy 4 parcels.</td></tr></table>
