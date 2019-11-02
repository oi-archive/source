# 

 
 # 题目描述 
<p>
精灵王如此机智，得益于年轻时候的好奇心和热爱思考的习惯。<br>话说当年精灵王只有16岁，就思考这样的问题：<br>给定n个不同的整数，我们可以通过不断交换相邻的两个元素将它们升序排列呢。精灵王称之为“极端快排”。比如对于序列<br>    9 1 0 5 4<br>极端快排后是<br>    0 1 4 5 9<br>精灵王思考的问题是，对于给定的序列至少需要多少次两两相邻交换操作，才能完成排序。<br></p> 

 
 # 输入格式 
<p>
输入包含多组数据。对于每组数据：<br>第1行：整数n表示序列长度。（n < 500,000）<br>第2…n+1行：每一行包含一个整数a[i]，表示数列中的一个元素。（0 ≤ a[i] ≤ 999,999,999）<br>输入以n = 0结束，这组数据不用处理。<br></p> 

 
 # 输出格式 
<p>
第1行：最少的两两相邻交换次数。</p> 
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
<tr><td>5
9
1
0
5
4
3
1
2
3
0
</td><td>6
0</td></tr></table>
