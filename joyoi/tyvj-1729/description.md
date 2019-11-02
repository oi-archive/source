# 

 
 # 题目背景 
此为平衡树系列第二道：文艺平衡树 

 
 # 题目描述 
您需要写一种数据结构（可参考题目标题），来维护一个有序数列，其中需要提供以下操作：<BR>翻转一个区间，例如原有序序列是5&nbsp;4&nbsp;3&nbsp;2&nbsp;1，翻转区间是[2,4]的话，结果是5&nbsp;2&nbsp;3&nbsp;4&nbsp;1 

 
 # 输入格式 
第一行为n,m&nbsp;n表示初始序列有n个数，这个序列依次是(1,2……n-1,n)&nbsp;&nbsp;m表示翻转操作次数<BR>接下来m行每行两个数[l,r]&nbsp;数据保证&nbsp;1&lt;=l&lt;=r&lt;=n 

 
 # 输出格式 
输出一行n个数字，表示原始序列经过m次变换后的结果 

 
 # 提示 
n,m&lt;=100000&nbsp;<BR> 
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
<tr><td>5 3
1 3
1 3
1 4
</td><td>4 3 2 1 5 </td></tr></table>
