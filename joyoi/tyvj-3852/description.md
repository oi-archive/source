# 

 
 # 题目描述 
<p style="line-height: 20.7999992370605px;">一个1~N的排列：a1,a2,&hellip;,an如果被称为是奇特的，当且仅当它满足下列奇特的性质：</p>

<p style="line-height: 20.7999992370605px;">在该排列中，不存在一对三元组(ak,&nbsp;ai,&nbsp;aj)满足k&lt;i&lt;j且ak&nbsp;&gt;&nbsp;aj&nbsp;&gt;&nbsp;ai。</p>

<p style="line-height: 20.7999992370605px;">例如1&nbsp;3&nbsp;2&nbsp;4&nbsp;就是一个奇特的排列，而&nbsp;1&nbsp;4&nbsp;2&nbsp;3就不是一个奇特的排列（4&gt;3&gt;2）。</p>

<p style="line-height: 20.7999992370605px;">下面给定N，想询问这种奇特排列的方案数，你只需要对方案数mod&nbsp;(10^9+7)输出即可。</p> 

 
 # 输入格式 
<p>输入包含一行整数N。</p> 

 
 # 输出格式 
<p>输出为奇特排列的方案数mod&nbsp;(10^9+7)后的结果。</p> 

 
 # 提示 
<p>对于30%的数据，n&lt;=10</p>

<p>对于50%的数据，n&lt;=100</p>

<p>对于70%的数据，n&lt;=1000</p>

<p>对于100%的数据，n&lt;=1000000</p> 
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
<tr><td>7</td><td>429</td></tr><tr><td>740616</td><td>726935399
</td></tr></table>
