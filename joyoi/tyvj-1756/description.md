# 

 
 # 题目描述 
<p>相信大家都玩过扫雷的游戏。那是在一个n*m的矩阵里面有一些雷，要你根据一些信息找出雷来。万圣节到了，&ldquo;余&rdquo;人国流行起了一种简单的扫雷游戏，这个游戏规则和扫雷一样，如果某个格子没有雷，那么它里面的数字表示和它8连通的格子里面雷的数目。现在棋盘是n&times;2的，第一列里面某些格子是雷，而第二列没有雷，如图：<br />
<img alt="" src="data:image/png;base64,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" style="opacity: 0.9; line-height: 20.8px; width: 249px; height: 145px;" /><br />
<br />
由于第一列的雷可能有多种方案满足第二列的数的限制，你的任务即根据第二列的信息确定第一列雷有多少种摆放方案。</p> 

 
 # 输入格式 
<p>第一行为N，第二行有N个数，依次为第二列的格子中的数。（1&lt;=&nbsp;N&nbsp;&lt;=&nbsp;10000）</p> 

 
 # 输出格式 
<p>一个数，即第一列中雷的摆放方案数。</p> 

 
 # 提示 
<p>数据范围见题干<br />
SCOI2005&nbsp;第四题</p> 
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
<tr><td>2
1 1
</td><td>2
</td></tr></table>