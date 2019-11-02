# 

 
 # 题目背景 
wzc小盆友玩游戏。。 

 
 # 题目描述 
wzc小盆友正在玩一个很有趣的游戏：<BR>给一个n*n的格子染色，每个格子可以染m种颜色。<BR>他想知道有几种染色方法，这个问题对他来说实在是太简单了，他只用了-1秒就解决了这个问题。后来他发现整个格子是可以转的，有一些染色方法经过旋转可以得到另外一个染色方法，他喜欢称之为本质相同的染色方法。<BR>现在他有一个问题要问问你，有多少种本质不同的染色方案？<BR>由于这个数可能很大，wzc小盆友很讨厌看到一大长串数，而他又是一个质数控，<BR>所以他希望知道这个方案数模一个质数p的结果<BR> 

 
 # 输入格式 
每个测试点有多组数据&nbsp;每行三个整数n&nbsp;m&nbsp;p<BR>数据末尾以0&nbsp;0&nbsp;0结束 

 
 # 输出格式 
每行一个整数L对应每组数据本质不同的方案数模p的结果<BR> 

 
 # 提示 
0&lt;n,m&lt;=1000000&nbsp;p是一个maxlongint范围内的质数<BR>每个点中数据的组数不会超过10000 
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
<tr><td>2 2 7
119 920 10007
0 0 0</td><td>6
3140
</td></tr></table>
