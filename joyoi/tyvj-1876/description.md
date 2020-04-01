# 

 
 # 题目描述 
若一个数（首位不为零）从左向右读与从右向左读都一样，我们就将其称之为回文数。<BR>例如：给定一个10进制数56，将56加65（即把56从右向左读），得到121是一个回文数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;又如：对于10进制数87：<BR>&nbsp;&nbsp;&nbsp;&nbsp;STEP1：87+78&nbsp;&nbsp;=&nbsp;165&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;STEP2：165+561&nbsp;=&nbsp;726<BR>&nbsp;&nbsp;&nbsp;&nbsp;STEP3：726+627&nbsp;=&nbsp;1353&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;STEP4：1353+3531&nbsp;=&nbsp;4884<BR>&nbsp;&nbsp;&nbsp;&nbsp;在这里的一步是指进行了一次N进制的加法，上例最少用了4步得到回文数4884。 

 
 # 输入格式 
给定一个N（2&lt;=N&lt;=10，N=16）进制数M 

 
 # 输出格式 
求最少经过几步可以得到回文数。如果在30步以内（包含30步）不可能得到回文数，则输出“Impossible!”。如果能得到回文数，则输出&nbsp;STEP=最少的步数 
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
<tr><td>9  
87  </td><td>STEP=6
</td></tr></table>
