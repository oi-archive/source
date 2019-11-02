# 

 
 # 题目描述 
<p>
城市规划（city.pas/c/cpp)<br><br>【问题描述】<br><br>　　N城准备开发一个荒地，目前已经规划好了一些居民点，还要建些道路。由于经费问题，他们想在任两点间的距离最短的前提下, 用尽可能少的投资把各个点连接起来。需要注意的是并不是任两个居民点间都能直接相连。给出两两居民点间建路的花费(与长度成正比)，你可以帮他们选择一个最佳方案吗？<br></p> 

 
 # 输入格式 
<p>
输入文件 city.in<br>　　第一行是一个数N(N＜100)，表示有N个居民点。<br>　　以下的N行每行有N个数，第i行第j个数表示居民点i到居民点j间建路的花费wij ( 0＜wij＜ 10000, wij=wji), 非正数表示两地不可直连。输入数据保证有解。<br></p> 

 
 # 输出格式 
<p>
　　输出文件city.out<br>　　第一行输出总花费<br>　　然后输出N行，每行N个数，第i行第j个数表示居民点i到居民点j的路，用1表示选取这条路，0则不选。<br></p> 
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
0 2 1
2 0 3
1 3 0
</td><td>3
0 1 1
1 0 0
1 0 0</td></tr></table>
