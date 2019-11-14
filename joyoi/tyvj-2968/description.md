# 

 
 # 题目描述 
<p>
有一天，Merlin同学突然发现一件有趣的事情。1到100之间的整数，有一些写成带分数的形式后，刚好使用了1到9这9个数字各一次，例如对于6，可以写成：<br><br><center><img src="/source/joyoi/tyvj-2968/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk2OC9wcm9ibGVtc19pbWFnZXMvMzU1Ny90MS5ibXA=.bmp"></img></center> <br>现在给定一个1到100之间的整数，请你找出所有满足这种形式的方案，即<br><br><center><img src="/source/joyoi/tyvj-2968/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk2OC9wcm9ibGVtc19pbWFnZXMvMzU1Ny90Mi5ibXA=.bmp"></img></center><br>其中，A是给定的整数，B、C和D是正整数，并且在B、C、D三个数中，1到9这9个数字恰好都出现过一次且仅一次。</p> 

 
 # 输入格式 
<p>
输入仅一个正整数A（A <= 100）。</p> 

 
 # 输出格式 
<p>
输出满足要求的所有方案。其中，先输出B最小的方案，B相同的情况下先输出C最小的方案。题目保证对于输入的A起码存在一个方案。<br>注意，在输出样例中的字母x只是用于占位，让选手可以清楚输出的格式，实际输出中请用空格代替x！<br></p> 
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
<tr><td>45</td><td>xxxxx3564
45=27----
xxxxxx198
xxxxx4172
45=38----
xxxxxx596</td></tr></table>
