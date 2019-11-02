# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;有一只青蛙…… 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;有一只青蛙，它要进行n级跳，它的跳跃能力很大程度上有关，具体来说，第i次跳远的距离Fi&nbsp;=&nbsp;F(i-1)&nbsp;*&nbsp;a&nbsp;+&nbsp;b&nbsp;(&nbsp;1&nbsp;&lt;=&nbsp;i&nbsp;&lt;=&nbsp;n&nbsp;)&nbsp;（&nbsp;单位：m）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;当然，刚开始跳了0m&nbsp;(&nbsp;F0&nbsp;=&nbsp;0&nbsp;）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;你只要输出第n步跳了几米，由于答案很大，所以输出答案除以m的余数。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行两个整数a，b，表示跳跃的两个参数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第二行两个整数n，m，表示跳了n步，答案要除以m。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出n次跳跃的米数除以m的余数。<BR> 

 
 # 提示 
99%的分数：0&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;10^6<BR>100%的分数：0&nbsp;&lt;=&nbsp;a&nbsp;&lt;=&nbsp;2000&nbsp;,&nbsp;0&nbsp;&lt;=&nbsp;b&nbsp;&lt;=&nbsp;10^9&nbsp;,&nbsp;0&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;10^9&nbsp;,&nbsp;1&nbsp;&lt;=&nbsp;m&nbsp;&lt;=&nbsp;10^9<BR> 
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
<tr><td>2 55
5 200 </td><td>105
</td></tr></table>
