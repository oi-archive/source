# 

 
 # 题目描述 
<p>
三个袋子（bags.pas\c\cpp）<br><br>【题目背景】<br>　　平平在公园里游玩时捡到了很多小球，而且每个球都不一样。平平找遍了全身只发现了3个一模一样的袋子。他打算把这些小球都装进袋子里（袋子可以为空）。他想知道他总共有多少种放法。<br><br>【题目描述】<br>　　将N个不同的球放到3个相同的袋子里，求放球的方案总数M。<br>　　结果可能很大，我们仅要求输出M mod K的结果。<br>　　现在，平平已经统计出了N<=10的所有情况。见下表：<br><br><center><img src="/source/joyoi/tyvj-3429/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzQyOS9wcm9ibGVtc19pbWFnZXMvMjIyNi8xLmpwZw==.jpg"></img></center><br></p> 

 
 # 输入格式 
<p>
　　输入文件bags.in包含两个整数N,K，N表示球的个数。</p> 

 
 # 输出格式 
<p>
　　输出文件bags.out输出仅包括一行，一个整数M mod K 。</p> 

 
 # 提示 
<p>
【数据规模】<br>　　对于 40%数据,10<=N<=10,000<br>　　对于100%数据,10<=N<=1,000,000,000<br>　　对于 100%数据，K<=100,000<br></p> 
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
<tr><td>11 10000</td><td>9525</td></tr></table>
