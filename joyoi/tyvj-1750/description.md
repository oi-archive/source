# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;著名的格雷码是指2n个不同n位二进制数（即0~2n-1，不足n位在前补零）的一个排<BR>列，这个排列满足相邻的两个二进制数的n位数字中最多只有一个数字不同（例如<BR>003和001就有一个数位不同，而003和030有两个数位不同，不符合条件）。例如n=2<BR>时，(00,01,11,10)就是一个满足条件的格雷码。<BR>&nbsp;&nbsp;&nbsp;&nbsp;所谓超级格雷码就是指Bn个不同的n位B进制数的排列满足上面的条件。<BR>任务：给出n和B（2≤B≤36,&nbsp;1≤Bn≤65535），求一个满足条件的格雷码。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;对于大于9的数位用A~Z表示（10~35）。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;只有一行，为两个整数n和B。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;一共B^n个行，每行一个B进制数，表示你所求得的符合条件的排列。 

 
 # 提示 
SCOI2004&nbsp;day2&nbsp;T1 
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
<tr><td>2 2
</td><td>00
01
11
10
</td></tr></table>
