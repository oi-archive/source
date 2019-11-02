# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;HNSDFZ的同学们为了庆祝春节，准备排练一场舞<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;n个人选出3*m人，排成m组，每组3人。<BR>&nbsp;&nbsp;&nbsp;&nbsp;站的队形——较矮的2个人站两侧，最高的站中间。<BR>&nbsp;&nbsp;&nbsp;&nbsp;从对称学角度来欣赏，左右两个人的身高越接近，则这一组的“残疾程度”越低。<BR>&nbsp;&nbsp;&nbsp;&nbsp;计算公式为&nbsp;&nbsp;h=(a-b)^2&nbsp;&nbsp;(a、b为较矮的2人的身高)<BR>&nbsp;&nbsp;&nbsp;&nbsp;那么问题来了。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在候选人有n个人，要从他们当中选出3*m个人排舞蹈，要求总体的“残疾程度”最低。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一排为m，n。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第二排n个数字，保证升序排列。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出最小“残疾程度”。<BR> 

 
 # 提示 
m&lt;=1000,n&lt;=5000<BR>数据保证3*m&lt;=n<BR> 
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
<tr><td>9 40
1 8 10 16 19 22 27 33 36 40 47 52 56 61 63 71 72 75 81 81 84 88 96 98 103 110 113 118 124 128 129 134 134 139 148 157 157 160 162 164
</td><td>23
</td></tr></table>
