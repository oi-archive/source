# 

 
 # 题目描述 
<p>
定义一个新的比较大小的规则：<br>1、关键字为各位数字之和；<br>1、关键字为字符序。<br>例如120<4因为1+2+0<4；<br>555<78因为5+5+5=15=7+8，而555的字符序小于78；<br>20<200应为2+0=2+0+0,而20的字符序小于200；<br>现在要你求1到n中k是第几大的，第k大的是几。<br></p> 

 
 # 输入格式 
<p>
有多组数据，<br>每组数据有n和k（1<=k<=n<=10^18），当n=k=0时结束读入。<br></p> 

 
 # 输出格式 
<p>
对于每组输入，输出一组1到n中k是第几大的和第k大的是几。<br></p> 
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
<tr><td>20 10
0 0	</td><td>2 14
数据范围：数据组数最多只有20组。
         30%的数据，n<=10^5;
         100%的数据，n<=10^18;</td></tr></table>
