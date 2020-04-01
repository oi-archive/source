# 

 
 # 题目描述 
<p>
在中山城新建的环城公路上一共有8个公交站，分别为A、B、C、D、E、F、G、H。公共汽车只能够在相邻的两个公交站之间运行，因此你从某一个公交站到另外一个公交站往往要换几次车，例如从公交站A到公交站D，你就至少需要换3次车。<br><br><center><img src="/source/joyoi/tyvj-2778/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc3OC9wcm9ibGVtc19pbWFnZXMvMzI5OC9wZy5naWY=.gif"></img></center><br>Tiger的方向感极其糟糕，我们知道从公交站A到公交E只需要换4次车就可以到达，可是tiger却总共换了n次车，注意tiger一旦到达公交站E，他不会愚蠢到再去换车。现在希望你计算一下tiger有多少种可能的乘车方案。</p> 

 
 # 输入格式 
<p>
输入文件由bus.in读入，输入文件当中仅有一个正整数n(4<=n<=10000000)，表示tiger从公交车站A到公交车站E共换了n次车。<br></p> 

 
 # 输出格式 
<p>
输出到文件bus.out。输出文件仅有一个正整数，由于方案数很大，请输出方案数除以 1000后的余数。<br></p> 

 
 # 提示 
<p>
8条路线分别是：<br>(A→B→C→D→C→D→E)，(A→B→C→B→C→D→E)，<br>(A→B→A→B→C→D→E)，(A→H→A→B→C→D→E)，<br>(A→H→G→F→G→F→E)，(A→H→G→H→G→F→E)，<br>(A→H→A→H→G→F→E)，(A→B→A→H→G→F→E)。<br></p> 
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
<tr><td>6</td><td>8</td></tr></table>
