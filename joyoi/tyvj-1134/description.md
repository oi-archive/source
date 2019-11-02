# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;CCR在2011年的中考复习时给自己定了个计划，计划包括了N天的复习科目（这一天复习的科目可以为语文、英语和随机安排三种，用c,e和w表示）注意3&lt;=N&lt;=350。<BR>&nbsp;&nbsp;&nbsp;&nbsp;但是CCR在定完计划后又改变了主意，决定把科目专项复习，于是他（应该说是“我”）把这个计划的尾和头连接了起来，接着再从其中的某一天起，把这个计划断开，从一端开始计算同一科目的最大数目（随机可以被当成其中任何一个科目，只要想这么做），另一端也这么做。计算规则如下：<BR>&nbsp;&nbsp;&nbsp;&nbsp;你需要计算的科目总和取决于端口的科目名称（如果是随机就随机了），接着向后累计，直到找到一个其他科目（随机不算啊！）为止。CCR写了一个程序以确定他最多可以复习多少天的同一科目，现在他（就是“我”了）来考考大家。 

 
 # 输入格式 
第&nbsp;1&nbsp;行:&nbsp;N,&nbsp;就是天数&nbsp;<BR>第&nbsp;2&nbsp;行:&nbsp;长度为N的字符串,&nbsp;每个字符是&nbsp;c&nbsp;，e&nbsp;或&nbsp;w。 

 
 # 输出格式 
单独的一行包含CCR可以复习的同一科目的天数最大值。 

 
 # 提示 
陈超锐的中考系列 
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
<tr><td>1
c</td><td>1</td></tr></table>
