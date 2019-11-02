# 

 
 # 题目描述 
Farmer&nbsp;John最近为奶牛们的图书馆添置了一个巨大的书架，尽管它是如此<BR>的大，但它还是几乎瞬间就被各种各样的书塞满了。现在，只有书架的顶上还留<BR>有一点空间。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;所有N(1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;20)头奶牛都有一个确定的身高H_i<BR>(1&nbsp;&lt;=&nbsp;H_i&nbsp;&lt;=&nbsp;1,000,000&nbsp;-&nbsp;好高的奶牛&gt;_&lt;)。设所有奶牛身高的和为S。书架的<BR>高度为B，并且保证1&nbsp;&lt;=&nbsp;B&nbsp;&lt;=&nbsp;S。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;为了够到比最高的那头奶牛还要高的书架顶，奶牛们不得不象演杂技一般，<BR>一头站在另一头的背上，叠成一座“奶牛塔”。当然，这个塔的高度，就是塔中<BR>所有奶牛的身高之和。为了往书架顶上放东西，所有奶牛的身高和必须不小于书<BR>架的高度。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;塔叠得越高便越不稳定，于是奶牛们希望找到一种方案，使得叠出的塔在高<BR>度不小于书架高度的情况下，高度尽可能小。你也可以猜到你的任务了：写一个<BR>程序，计算奶牛们叠成的塔在满足要求的情况下，最少要比书架高多少。<BR> 

 
 # 输入格式 
*&nbsp;第1行:&nbsp;2个用空格隔开的整数：N&nbsp;和&nbsp;B<BR><BR>*&nbsp;第2..N+1行:&nbsp;第i+1行是1个整数：H_i<BR> 

 
 # 输出格式 
*&nbsp;第1行:&nbsp;输出1个非负整数，即奶牛们叠成的塔最少比书架高的高度<BR> 

 
 # 提示 
我们选用奶牛1、3、4、5叠成塔，她们的总高度为3&nbsp;+&nbsp;3&nbsp;+&nbsp;5&nbsp;+&nbsp;6&nbsp;=&nbsp;17。任<BR>何方案都无法叠出高度为16的塔，于是答案为1。<BR> 
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
<tr><td>5 16
3
1
3
5
6
</td><td>1
</td></tr></table>
