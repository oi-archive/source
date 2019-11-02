# 

 
 # 题目描述 
<p>
一天，mlj在平面上画了N个黑点和N个白点，按以下方式来连边，构成一个有向完全图。<br>1.I J同色，随机选择I→J或J→I<br>2.I J异色，若Dij>D，则白点→黑点，否则黑点→白点<br>这里的Dij指的是曼哈顿（|xi-xj|+|yi-yj|)，D为给定值<br>然后，mlj发现有很多三角形很漂亮，漂亮三角形的定义如下：<br>1.三个顶点I J K颜色不完全相同<br>2.它们之间的连的边是 I→J J→K K→I<br>（至于为什么mlj觉得这样漂亮，大概是火星人审美观与众不同吧）<br>mlj想知道这里面漂亮三角形的个数，但他视力很差，于是求助于你。<br>求出漂亮三角形最少有多少个，最多有多少个。</p> 

 
 # 输入格式 
<p>
第一行两个正整数 N D 。<br>接下来N行Xi Yi描述第i个白点的坐标。<br>再接下来N行Xj Yj描述第j个黑点的坐标。<br></p> 

 
 # 输出格式 
<p>
两个数依次为漂亮三角形最少的个数，最多的个数，中间用一个空格隔开。</p> 

 
 # 提示 
<p>
<br><img src="/source/joyoi/tyvj-2904/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjkwNC9wcm9ibGVtc19pbWFnZXMvMzQ2OS9wZy5qcGc=.jpg"></img></p> 
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
<tr><td>2 1
1 2
1 1
3 1
2 2	
</td><td>0 2</td></tr></table>
