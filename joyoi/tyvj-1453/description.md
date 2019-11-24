# 

 
 # 题目描述 
&nbsp;一个n的全排列A[i]是单峰的，当且仅当存在某个x使得A[1]&lt;A[2]&lt;...&lt;A[x]&gt;A[x+1]&gt;...&gt;&nbsp;A[n]。<BR>　　例如，对于9的全排列，125798643是一个单峰排列，123456789也是一个单峰排列，但356298741就不是。<BR>　　试求n的单峰全排列的个数。<BR>&nbsp;<BR>&nbsp;<BR> 

 
 # 输入格式 
输入一个数n。n小于int64<BR> 

 
 # 输出格式 
输出n的全排列中单峰排列的个数。<BR>　　由于这个数可能很大，因此你只需要输出它mod&nbsp;1234567的值。<BR>&nbsp;<BR>&nbsp;&nbsp;&nbsp;<BR> 

 
 # 提示 
样例说明<BR>　　共有以下4种方案：<BR>　　123<BR>　　132<BR>　　231<BR>　　321 
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
<tr><td>3
</td><td>4

</td></tr></table>
