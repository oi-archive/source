# 

 
 # 题目描述 
<p>
Mirko和Slavko在玩动物玩具。首先，他们选择下图中三个棋盘中的一个。<br><br><center><img src="/source/joyoi/tyvj-2814/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjgxNC9wcm9ibGVtc19pbWFnZXMvMzM0Mi9wZy5qcGc=.jpg"></img></center><br>图中每个圆圈代表一个格子，棋盘是由一维、二维、三维网格构成的。<br>Mirko将N个可爱的小动物玩具放在了格子里。<br>两个格子间的距离指的是从一个格子移动到另外一个的最小步数；每一步，小动物可以从一个格子移动到相邻的格子（在图中用短线连接）。<br>如果两个小动物之间的距离不超过D，他们就能彼此听见。Slavko的任务就是计算有多少对动物可以互相听到。<br>任务<br>写一个程序，输入棋盘类型，动物位置，D值，找出题目所述的动物对数。</p> 

 
 # 输入格式 
<p>
第一行包括4个整数<br>· 棋盘类型B (1 ≤ B ≤ 3);<br>· 动物数目 N (1 ≤ N ≤ 100 000);<br>· 动物可以互相听见的最大距离D (1 ≤ D ≤ 100 000 000);<br>· 棋盘的尺寸M (可能出现的最大的坐标)，M≤75*10003-B<br>接下来N行，每行有3个1到M的整数，代表小动物的坐标<br>同一个格子里面可能有好多个小动物。</p> 

 
 # 输出格式 
<p>
仅包含一个整数，即可以互相听见的动物的对数，请使用64位整数计算 (long long in C/C++, int64 in Pascal)。</p> 

 
 # 提示 
<p>
限制<br>在20分的测试数据内，N<=1000<br>此外，对于任意一种棋盘，能正确解决这种棋盘上的问题的程序可以得到不低于30分。</p> 
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
<tr><td><br><center><img src="/source/joyoi/tyvj-2814/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjgxNC9wcm9ibGVtc19pbWFnZXMvMzM0Mi9wZzIuanBn.jpg"></img></center>
</td><td>（见上）</td></tr></table>
