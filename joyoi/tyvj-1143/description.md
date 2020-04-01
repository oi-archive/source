# 

 
 # 题目背景 
&nbsp;一阵狂风吹过&nbsp;<BR>&nbsp;只听“pong”的一声，飘飘乎居士降落了！！！ 

 
 # 题目描述 
又是美妙的一天，这天飘飘乎居士要和MM约会，因此他打扮的格外帅气。但是，因为打扮的时间花了太久，离约会的时间已经所剩无几。<BR>幸运的是，现在飘飘乎居士得到了一张n*m的地图，图中左上角是飘飘乎居士的位置，右下角是约会的地点。‘.’代表马路，‘*’代表房屋。飘飘乎居士只能沿着‘.’行走（也就是不能踏入‘*’），而且行走的方向只能为上下左右的相邻格子。为了不让MM等待太久，飘飘乎居士在整个过程中可能会使用一次飘飘神功（也可能不使用，但最多使用一次），使用飘飘神功后，飘飘乎居士可以走进房屋一次（也就是在全程的行走中最多可以走一个‘*’,注意，只有一个）；<BR>&nbsp;&nbsp;&nbsp;现在飘飘乎居士想要知道最少需要走多少步，飘飘乎居士才能到达约会的地点。<BR> 

 
 # 输入格式 
第一行，2个正整数&nbsp;n和m，表示一个n*m的矩阵<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来n行，每行m个字符，字符一定为&nbsp;’.’&nbsp;或者是‘*’&nbsp;，分别代表马路和房屋。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入数据保证左上角和右下角都为‘.’<BR> 

 
 # 输出格式 
一行，如果可以到达，则输入需要行走的最少步数（飘飘神功也记为一步）<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如果不可以到达，则输出‘no’<BR> 

 
 # 提示 
0&lt;N&nbsp;M&nbsp;&lt;=1000飘飘乎居士——violet&nbsp;hill 
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
<tr><td>样例输入1
3 3
.*.
...
...

样例输入2
3 3
.**
***
**.
</td><td>样例输入1
4

样例输入2
no</td></tr></table>
