# 

 
 # 题目描述 
<p>在一个N&nbsp;*&nbsp;M的棋盘上，摆放着K个士兵，一个士兵占据一个格子（可能有多个士兵占据同一个格子）。第i个士兵控制棋盘上所有与它相距不超过R<sub>i</sub>的格子。&nbsp;两个格子(X<sub>1</sub>,&nbsp;Y<sub>1</sub>)、(X<sub>2</sub>,&nbsp;Y<sub>2</sub>)间的距离定义为|X<sub>1</sub>&nbsp;-&nbsp;X<sub>2</sub>|&nbsp;+&nbsp;|Y<sub>1</sub>&nbsp;-&nbsp;Y<sub>2</sub>|。现在给出K个士兵的坐标，请你写一个程序返回被控制的格子的总数。</p> 

 
 # 输入格式 
<p>输入第一行包含三个整数N、M和K，以下K行每行包含三个整数X<sub>i</sub>、Y<sub>i</sub>和R<sub>i</sub>，分别表示相应的士兵的坐标（第X<sub>i</sub>行和第Y<sub>i</sub>列）以及其控制范围，我们规定棋盘的左下角为(1,&nbsp;1)，右上角为(N,&nbsp;M)。</p> 

 
 # 输出格式 
<p>输出仅包含一个整数表示被控制的格子总数。</p> 

 
 # 提示 
<p><span style="line-height: 1.6em;">对于10%的数据，有1&nbsp;&le;&nbsp;N,&nbsp;M&nbsp;&le;&nbsp;1000，1&nbsp;&le;&nbsp;K&nbsp;&le;&nbsp;100；</span></p>

<p>对于20%的数据，有1&nbsp;&le;&nbsp;N,&nbsp;M&nbsp;&le;&nbsp;100000，1&nbsp;&le;&nbsp;K&nbsp;&le;&nbsp;100；</p>

<p>对于50%的数据，有1&nbsp;&le;&nbsp;N,&nbsp;M&nbsp;&le;&nbsp;1000000000，1&nbsp;&le;&nbsp;K&nbsp;&le;&nbsp;1000；</p>

<p>对于100%的数据，有1&nbsp;&le;&nbsp;N,&nbsp;M&nbsp;&le;&nbsp;1000000000，1&nbsp;&le;&nbsp;K&nbsp;&le;&nbsp;100000。</p> 
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
<tr><td>4 4 31 1 13 1 13 3 1</td><td>10</td></tr></table>
