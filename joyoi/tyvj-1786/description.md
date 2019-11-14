# 

 
 # 题目背景 
SCOI2011&nbsp;Day1&nbsp;第二题 

 
 # 题目描述 
lxhgww的小名叫“小L”，这是因为他总是很喜欢L型的东西。小L家的客厅是一个&nbsp;的矩形，现在他想用L型的地板来铺满整个客厅，客厅里有些位置有柱子，不能铺地板。现在小L想知道，用L型的地板铺满整个客厅有多少种不同的方案？<BR>需要注意的是，如下图所示，L型地板的两端长度可以任意变化，但不能长度为0。铺设完成后，客厅里面所有没有柱子的地方都必须铺上地板，但同一个地方不能被铺多次。<BR>【图片1】<BR> 

 
 # 输入格式 
输入的第一行包含两个整数，R和C，表示客厅的大小。<BR>接着是R行，每行C个字符。’_’表示对应的位置是空的，必须铺地板；’*’表示对应的位置有柱子，不能铺地板。<BR><BR> 

 
 # 输出格式 
输出一行，包含一个整数，表示铺满整个客厅的方案数。由于这个数可能很大，只需输出它除以20110520的余数。 

 
 # 提示 
对于1,2的数据，保证&nbsp;R*C&lt;=25<BR>对于3,4,5的数据，保证&nbsp;R*C&lt;=100并且(R&nbsp;=&nbsp;2或者C&nbsp;=&nbsp;2)<BR>对于6,7,8,9,10的数据，保证&nbsp;R*C&nbsp;&lt;=&nbsp;100<BR> 
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
<tr><td>【样例输入1】
2 2
*_
__
【样例输入2】
3 3
___
_*_
___ 



</td><td>【样例输出1】
1
【样例输出2】
8
</td></tr></table>
