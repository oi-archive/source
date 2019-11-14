# 

 
 # 题目背景 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">发鸠之山，其上多柘木。有鸟焉，其状如乌，文首，白喙，赤足，名曰精卫，其名自詨。是炎帝之少女，名曰女娃。女娃游于东海，溺而不返，故为精卫。常衔西山之木石，以堙于东海。&mdash;&mdash;《山海经》</span></p> 

 
 # 题目描述 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">精卫终于快把东海填平了！只剩下了最后的一小片区域了。同时，西山上的木石也已经不多了。精卫能把东海填平吗？</span><br style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;" />
<span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">事实上，东海未填平的区域还需要体积为v的木石才可以填平，而西山上的木石还剩下n块，每块的体积和把它衔到东海需要的体力分别为k和m。精卫已经填海填了这么长时间了，她也很累了，她还剩下的体力为c。</span></p> 

 
 # 输入格式 
<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">输入文件的第一行是三个整数：v、n、c。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">从第二行到第n+1行分别为每块木石的体积和把它衔到东海需要的体力。</p> 

 
 # 输出格式 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">输出文件只有一行，如果精卫能把东海填平，则输出她把东海填平后剩下的最大的体力，否则输出&rsquo;Impossible&rsquo;（不带引号）。</span></p> 

 
 # 提示 
<h2>数据范围</h2>

<p>对于20%的数据，0&lt;n&lt;=50。<br />
对于50%的数据，0&lt;n&lt;=1000。<br />
对于100%的数据，0&lt;n&lt;=10000，所有读入的数均属于[0,10000]，最后结果&lt;=c。</p>

<p>&nbsp;</p>

<h2>版权</h2>

<p>本用户并不拥有该资料版权。如果无意侵犯了您的权益，请私信管理员或本用户。管理员接到通知后请删题，以避免不必要的纠纷，谢谢！</p> 
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
<tr><td>100 2 10
50 5
50 5</td><td>0</td></tr><tr><td>10 2 1
50 5
10 2</td><td>Impossible</td></tr></table>
