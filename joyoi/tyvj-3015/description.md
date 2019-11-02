# 

 
 # 题目描述 
<p>
　　给你一个长度为N的数组，一个长为K的滑动的窗体从最左移至最右端，你只能见到窗口的K个数，每次窗体向右移动一位，如下表：<br>　　<br><center><img src="/source/joyoi/tyvj-3015/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzAxNS9wcm9ibGVtc19pbWFnZXMvMzYyOC8xLnBuZw==.png"></img></center><br>　　你的任务是找出窗口在各位置时的max value，min value。</p> 

 
 # 输入格式 
<p>
　　第1行：n，k。<br>　　第2行：长度为n的数组。</p> 

 
 # 输出格式 
<p>
　　2行，第1行每个位置的min value,第2行每个位置的max value。</p> 

 
 # 提示 
<p>
　　数据范围：<br>　　20%： n<=500；<br>　　50%: n<=100000；<br>　　100%: n<=1000000。</p> 
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
<tr><td>8 3
1 3 -1 -3 5 3 6 7</td><td>-1 -3 -3 -3 3 3
3 3 5 5 6 7</td></tr></table>
