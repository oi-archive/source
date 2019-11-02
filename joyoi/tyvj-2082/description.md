# 

 
 # 题目背景 
<p>noip2013day1</p>

<p>&nbsp;</p> 

 
 # 题目描述 
<p>&nbsp;</p>

<p>A&nbsp;国有&nbsp;n&nbsp;座城市，编号从&nbsp;1&nbsp;到&nbsp;n，城市之间有&nbsp;m&nbsp;条双向道路。每一条道路对车辆都有重<br />
量限制，简称限重。现在有&nbsp;q&nbsp;辆货车在运输货物，&nbsp;司机们想知道每辆车在不超过车辆限重的<br />
情况下，最多能运多重的货物。<br />
&nbsp;</p> 

 
 # 输入格式 
<p>输入文件第一行有两个用一个空格隔开的整数&nbsp;n，&nbsp;m，&nbsp;表示&nbsp;A&nbsp;国有&nbsp;n&nbsp;座城市和&nbsp;m&nbsp;条道<br />
路。<br />
接下来&nbsp;m&nbsp;行每行&nbsp;3&nbsp;个整数&nbsp;x、&nbsp;y、&nbsp;z，每两个整数之间用一个空格隔开，表示从&nbsp;x&nbsp;号城市<br />
到&nbsp;y&nbsp;号城市有一条限重为&nbsp;z&nbsp;的道路。注意：&nbsp;x&nbsp;不等于&nbsp;y，两座城市之间可能有多条道路。<br />
接下来一行有一个整数&nbsp;q，表示有&nbsp;q&nbsp;辆货车需要运货。<br />
接下来&nbsp;q&nbsp;行，每行两个整数&nbsp;x、&nbsp;y，之间用一个空格隔开，表示一辆货车需要从&nbsp;x&nbsp;城市<br />
运输货物到&nbsp;y&nbsp;城市，注意：&nbsp;x&nbsp;不等于&nbsp;y。</p> 

 
 # 输出格式 
<p>输出共有&nbsp;q&nbsp;行，每行一个整数，表示对于每一辆货车，它的最大载重是多少。如果货<br />
车不能到达目的地，输出-1。</p> 

 
 # 提示 
<p>对于&nbsp;30%的数据，&nbsp;0&nbsp;&lt;&nbsp;n&lt;&nbsp;1,000，&nbsp;0&nbsp;&lt;&nbsp;m&lt;&nbsp;10,000，&nbsp;0&nbsp;&lt;&nbsp;q&lt;&nbsp;1,000；<br />
对于&nbsp;60%的数据，&nbsp;0&nbsp;&lt;&nbsp;n&lt;&nbsp;1,000，&nbsp;0&nbsp;&lt;&nbsp;m&lt;&nbsp;50,000，&nbsp;0&nbsp;&lt;&nbsp;q&lt;&nbsp;1,000；</p>

<p>对于&nbsp;100%的数据，&nbsp;0&nbsp;&lt;n&nbsp;&lt;&nbsp;10,000，&nbsp;0&nbsp;&lt;m&nbsp;&lt;&nbsp;50,000，&nbsp;0&nbsp;&lt;q&nbsp;&lt;&nbsp;30,000，</p>

<p>0&nbsp;&le;&nbsp;z&nbsp;&le;&nbsp;100,000。</p>

<p>by&nbsp;460289052</p> 
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
<tr><td>4 3
1 2 4
2 3 3
3 1 1
3
1 3
1 4
1 3
</td><td>3
-1
3
</td></tr></table>
