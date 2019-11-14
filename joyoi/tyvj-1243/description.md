# 

 
 # 题目描述 
六一儿童节到了，李老师准备发笔作为礼物送给大家，李老师想把礼物送给好同学，他的手头有一份EZOI成员名单和资料，共n人，每人的资料都有p项，现在请你按照这些资料的某一项从大到小排好序，由于老师只发给m个同学，所以请你输出前m个人的名字。<BR> 

 
 # 输入格式 
第一行有4个自然数，n和m（0&lt;=m&lt;=n&lt;=100000）以及p、q（0&lt;=q&lt;=p&lt;=15）.<BR>以下n行，第一个是名字（长度不会超过200位），后接他/她的p项资料，都是不超过1000000自然数。空格隔开。没有两个人的同一项资料的值相等。可能有人的名字相同，照输就可以了。<BR>请你按照第q项资料排序。<BR> 

 
 # 输出格式 
有m行，是按照第q项资料排序能得到礼物的名单。<BR> 

 
 # 提示 
From&nbsp;EZ_lzh.(物归原主了） 
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
<tr><td>2 1 2 1
Littlefat 0 500000
Turtle 500000 0
</td><td>Turtle
</td></tr></table>
