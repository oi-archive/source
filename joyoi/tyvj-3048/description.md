# 

 
 # 题目描述 
<p>
精灵王变得非常懒，他不想再继续维护小精灵之间通行的道路。道路被用来连接N（5≤N≤10000）块魔法石，编号为1到N。每块魔法石都是一名小精灵的家。精灵王计划除去P（N-1≤P≤100000）条道路中尽可能多的道路，但是还要保持魔法石的连通性。你首先要决定哪些道路是要保留的N-1条道路。<br>第j条双向道路连接了魔法石Sj和Ej（1≤Sj, Ej≤N；Sj≠Ej），而且走完它需要Lj（0≤Lj≤1000）的时间。没有两块魔法石是被一条以上的道路所连接。<br>小精灵们非常担心，因为她们的交通系统被削减了。你需要到每一名小精灵的住处去安慰她们。每次你到达第i块魔法石的时候（即使你已经经过），你必须花去Ci（1≤Ci≤1000）的时间和小精灵交谈。<br>你每个晚上都会在同一块魔法石（这是供你选择的）过夜，直到小精灵们都从悲伤中缓过神来。在早上起来和晚上回去睡觉的时候，你都需要和你住同一块魔法石的小精灵交谈一次。这样你才能完成你的交谈任务。<br>假设精灵王采纳了你的建议，请计算出使所有小精灵都被安慰的最少时间。<br></p> 

 
 # 输入格式 
<p>
第1行：用空格分隔的两个整数N和P。<br>第2到N+1行：第i+1行包含了一个整数Ci。<br>第N+2到N+P+1行：第N+j+1行包含用空格分隔的三个整数Sj、Ej和Lj。<br></p> 

 
 # 输出格式 
<p>
第1行：一个整数，表示使所有小精灵都被安慰的最少时间。</p> 

 
 # 提示 
<p>
<br><img src="/source/joyoi/tyvj-3048/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA0OC9wcm9ibGVtc19pbWFnZXMvMzY2OC8xLmpwZw==.jpg"></img></p> 
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
<tr><td>5 7
10
10
20
6
30
1 2 5
2 3 5
2 4 12
3 4 17
2 5 15
3 5 6
4 5 12
</td><td>176</td></tr></table>
