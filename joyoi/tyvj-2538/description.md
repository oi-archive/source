# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>


 
 # 输出格式 
<p>

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
<tr><td>6
A
C
D
B
C
B

输入说明:

    FJ有6头顺次排好队的奶牛：ACDBCB

</td><td>
ABCBCD

输出说明:

 操作数   原队列     新队列
   #1     ACDBCB
   #2      CDBCB     A
   #3      CDBC      AB
   #4      CDB       ABC
   #5      CD        ABCB
   #6       D        ABCBC
   #7                ABCBCD