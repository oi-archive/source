# 

 
 # 题目描述 
<p>
铁塔尼号遇险了！他发出了求救信号。距离最近的哥伦比亚号收到了讯息，时间就是生命，必须尽快赶到那里。<br>通过侦测，哥伦比亚号获取了一张海洋图。这张图将海洋部分化成n*n个比较小的单位，其中用1标明的是陆地，用0标明是海洋。船只能从一个格子，移到相邻的四个格子。<br>为了尽快赶到出事地点，哥伦比亚号最少需要走多远的距离。<br></p> 

 
 # 输入格式 
<p>
第一行为n,下面是一个n*n的0，1矩阵，表示海洋地图。<br>最后一行为四个小于n的整数，分别表示哥伦比亚号和铁塔尼号的位置。<br></p> 

 
 # 输出格式 
<p>
哥伦比亚号到铁塔尼号的最短距离，答案精确到整数。</p> 

 
 # 提示 
<p>
数据范围：N<=1000。时间限制为1s。</p> 
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
<tr><td>3
001
101
100
1 1 3 3
</td><td>4</td></tr></table>
