# 

 
 # 题目背景 
NOIP2004&nbsp;提高组&nbsp;第三道 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;N位同学站成一排，音乐老师要请其中的(N-K)位同学出列，使得剩下的K位同学排成合唱队形。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;合唱队形是指这样的一种队形：设K位同学从左到右依次编号为1，2…，K，他们的身高分别为T1，T2，…，TK，&nbsp;&nbsp;则他们的身高满足T1&lt;...&lt;Ti&gt;Ti+1&gt;…&gt;TK(1&lt;=i&lt;=K)。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;你的任务是，已知所有N位同学的身高，计算最少需要几位同学出列，可以使得剩下的同学排成合唱队形。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;输入文件chorus.in的第一行是一个整数N(2&lt;=N&lt;=100)，表示同学的总数。第一行有n个整数，用空格分隔，第i个整数Ti(130&lt;=Ti&lt;=230)是第i位同学的身高(厘米)。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出文件chorus.out包括一行，这一行只包含一个整数，就是最少需要几位同学出列。 

 
 # 提示 
对于50％的数据，保证有n&lt;=20；<BR>对于全部的数据，保证有n&lt;=100。<BR> 
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
<tr><td>8
186 186 150 200 160 130 197 220
</td><td>4</td></tr></table>
