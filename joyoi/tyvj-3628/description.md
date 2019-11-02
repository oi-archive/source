# 

 
 # 题目描述 
<p>
　　对于自然数1..n的一个排列A[1..N] 可以划分为若干个单调递增序列。每个单调递增序列由连续元素A[st..ed]组成，且满足以下条件：<br>　　1 <= st , ed <= n；  <br>　　A[i] < A[i+1] ( st <= i < ed-1 )；<br>　　ed = n 或者 A[ed] > A[ed+1]；<br>　<br>　　例如：排列1 2 4 5 6 3 9 10 7 8 可划分为3个单调递增序列 1 2 3 4 5；3 9 10 ；7 8 ； 所以我们称这是一个 3上升段序列 。<br>现在给定n和k , 求出n的全排列中的，k上升段序列 的个数。<br><br><br></p> 

 
 # 输入格式 
<p>
　　1行，包含两个数n , k（1 < n <= 20, 1 < k < n），两个数之间有一个空格间隔。</p> 

 
 # 输出格式 
<p>
　　输出n的所有k上升段的个数。</p> 

 
 # 提示 
<p>
( 说明，符合条件的排列是１３２，３１２，２１３，２３１)</p> 
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
<tr><td>3 2</td><td>4</td></tr></table>
