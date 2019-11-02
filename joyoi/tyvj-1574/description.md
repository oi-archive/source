# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;在一个舞会上，有&nbsp;N&nbsp;对男女依次到达。<BR>&nbsp;&nbsp;&nbsp;&nbsp;当第一对到达后，他们便开始跳起了舞。然后第二对到了，这&nbsp;4&nbsp;个人便重新<BR>分配了一下舞伴，继续开始跳舞。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来每来一对男女，所有在场的人都从新分配下舞伴。<BR>&nbsp;&nbsp;&nbsp;&nbsp;分配舞伴的时候要依照某种方式，&nbsp;&nbsp;&nbsp;我们假设男性的身高为&nbsp;Ai&nbsp;而女性的身高为<BR>Bi，分配后&nbsp;Ai’与&nbsp;Bi’&nbsp;配对，则我们要最小化：Max(Ai'+Bi')<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在舞会的主办者，希望你给出每对男女来之后&nbsp;&nbsp;Max(Ai'+Bi')&nbsp;&nbsp;的值。<BR> 

 
 # 输入格式 
第一行一个数字&nbsp;N。<BR>接下来&nbsp;N&nbsp;行，每行两个数表示一对男女的身高。<BR> 

 
 # 输出格式 
输出&nbsp;N&nbsp;行，每行一个数，表示最小的Max(Ai'+Bi')&nbsp;的值。 

 
 # 提示 
样例解释<BR>&nbsp;&nbsp;&nbsp;&nbsp;第一队男女来后：(2,8)<BR>&nbsp;&nbsp;&nbsp;&nbsp;第二队男女来后：(2,8)&nbsp;(3,1)<BR>&nbsp;&nbsp;&nbsp;&nbsp;第三队男女来后：(2,4)&nbsp;(3,1)&nbsp;(1,8)<BR>数据规模<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于&nbsp;50%&nbsp;的数据&nbsp;N&lt;=200；<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于&nbsp;100%&nbsp;的数据&nbsp;N&lt;=100000，1&lt;=Ai,Bi&lt;=100。<BR>清北学堂模拟赛，第二场，第三题。 
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
2 8
3 1
1 4
</td><td>10
10
9
</td></tr></table>
