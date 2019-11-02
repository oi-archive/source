# 

 
 # 题目描述 
<p>N个人围成一圈，从1到N进行编号。现在从第1个人开始循环报数，每次报到一个特殊的数字的人将会退出序列，他的下一个人从1开始重新报数。</p>

<p>现在这个特殊的数字序列为{2,3,5,7...}，序列中第i个数为第i个素数，即：</p>

<div>
<p style="line-height: 20.7999992370605px;">1.&nbsp;当第一轮报数中，报2的人退出</p>

<p style="line-height: 20.7999992370605px;">2.&nbsp;在第二轮报数中，报3的人退出</p>

<p style="line-height: 20.7999992370605px;">3.&nbsp;在第i轮报数中，报pi的人退出</p>
</div>

<p>请问最后剩下的唯一一个人的编号？</p>

<p>【具体参见样例解释】</p> 

 
 # 输入格式 
<p>输入包含一个整数N</p> 

 
 # 输出格式 
<p>输出包含一个整数P，表示最后剩下的人的编号</p> 

 
 # 提示 
<p><strong>[</strong><strong>样例</strong><strong>1</strong><strong>解释</strong><strong>]</strong></p>

<p>（1）：1号报1,2号报2（2为素数，2号退出）</p>

<p>（2）：3号报1，4号报2，5号报3（5号退出）</p>

<p>（3）：6号报1,1号报2，3号报3，4号报4，6号报5（6号退出）</p>

<p>（4）：1号报1，3号报2,4号报3,1号报4,3号报5,4号报6,1号报7（1号退出）</p>

<p>（5）：3号报1，4号报2，...，3号报11（3号退出）</p>

<p>所以最后只剩下4号。</p>

<p><strong>数据范围：</strong></p>

<p>对于30%的数据，N&lt;=1000</p>

<p>对于100%的数据，N&lt;=1000000</p> 
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
<tr><td>6</td><td>4</td></tr><tr><td>1234</td><td>945</td></tr></table>
