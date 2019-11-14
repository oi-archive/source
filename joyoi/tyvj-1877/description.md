# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;一个旅行家想驾驶汽车以最少的费用从一个城市到另一个城市（假设出发时油箱是空的）。给定两个城市之间的距离D1、汽车油箱的容量C（以升为单位）、每升汽油能行驶的距离D2、出发点每升汽油价格P和沿途油站数N（N可以为零），油站i离出发点的距离Di、每升汽油价格Pi（i=1，2，…，N）。计算结果四舍五入至小数点后两位。如果无法到达目的地，则输出“No&nbsp;Solution”。<BR>样例：&nbsp;INPUT<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;D1=275.6&nbsp;&nbsp;C=11.9&nbsp;&nbsp;D2=27.4&nbsp;&nbsp;&nbsp;P=2.8&nbsp;&nbsp;&nbsp;N=2<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;油站号I&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;离出发点的距离Di&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;每升汽油价格Pi<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;102.0	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.9<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;220.0	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OUTPUT　　26.95（该数据表示最小费用）<BR> 

 
 # 输入格式 
共n+1行<BR>第1行为：&nbsp;D1&nbsp;C&nbsp;D2&nbsp;P&nbsp;N（以下N行）<BR>每行分别：油站号I，该油站距出发点的距离Di，该油站每升汽汽油的价格Pi<BR> 

 
 # 输出格式 
仅一行，表示最少费用 

 
 # 提示 
n&lt;=10 
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
<tr><td>275.6 11.9 27.4 2.8 2
102.0 2.9
220.0 2.2
</td><td>26.95    （该数据表示最小费用）</td></tr></table>
