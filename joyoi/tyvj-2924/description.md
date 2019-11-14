# 

 
 # 题目描述 
<p>
做过了乘积最大这道题，相信这道题也难不倒你。<br>已知一个数串，可以在适当的位置加入乘号（设加了k个，当然也可不加，即分成k+1个部分），设这k+1个部分的乘积（如果k=0,则乘积即为原数串的值）对m 的余数（即mod m）为x;<br>现求x能达到的最小值及该情况下k的最小值，以及x能达到的最大值及该情况下的k的最小值（可以存在x的最小值与最大值相同的情况）。<br></p> 

 
 # 输入格式 
<p>
第一行为数串，长度为n 满足2<=n<=1000，且数串中不存在0；<br>第二行为m，满足2<=m<=50。<br></p> 

 
 # 输出格式 
<p>
四个数，分别为x的最小值 和 该情况下的k，以及x的最大值和 该情况下的k，中间用空格隔开。</p> 
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
<tr><td>4421
22
</td><td>0 1 21 0</td></tr></table>
