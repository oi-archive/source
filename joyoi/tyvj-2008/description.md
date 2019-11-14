# 

 
 # 题目描述 
Rainbow和Freda要在Poetic&nbsp;Island市的一座山脚下盖房子定居了……盖房子需要钢材，幸运的是，这里有排成一行的n座废弃的铁塔，从左到右编号为1~n，其中第i座的高度为h[i]。<br>Rainbow和Freda想盖一座上面小下面大的城堡，并且城堡的层数尽可能多。因此，他们要把这些铁塔分成尽量多组，每组内的铁塔编号必须是连续的，并且从左到右各组内铁塔的高度之和单调不减。<br>但是Rainbow和Freda简直弱爆了有木有，于是请你帮忙计算一下最多能分成多少组呢？<br> 

 
 # 输入格式 
第一行一个整数n。<br>第二行n个整数，第i个整数表示h[i]。<br> 

 
 # 输出格式 
输出一个整数，表示(n&nbsp;-&nbsp;最多能分成的组数)。<br> 

 
 # 提示 
对于30%的数据，0&lt;&nbsp;n&nbsp;&lt;=100。<br>对于70%的数据，0&lt;&nbsp;n&nbsp;&lt;=5000。<br>对于100%的数据，0&lt;&nbsp;n&nbsp;&lt;=200000，0&lt;&nbsp;h[i]&nbsp;&lt;=2147483647，h均为随机生成。<br><br>样例可分成1、9、9、4&nbsp;1&nbsp;2&nbsp;2、9，各组的和分别为1&nbsp;9&nbsp;9&nbsp;9&nbsp;9，单调不减。因此输出n-最大组数=3.<br> 
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
<tr><td>8
1 9 9 4 1 2 2 9
</td><td>3
</td></tr></table>
