# 

 
 # 题目描述 
<p>
给出一个字符矩阵,你要从中找出一个出现次数最多的子矩阵.<br><br></p> 

 
 # 输入格式 
<p>
第一行给出N,M.代表矩阵的大小.<br>下面N行M列用来描述矩阵的形态.<br>再给出X,Y代表子矩阵的大小.</p> 

 
 # 输出格式 
<p>
先输出X,Y<br>再输出你所找到的字符矩阵.<br>再输出它出现的次数.<br>再输出它每次出现的位置的左上角坐标.</p> 
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
<tr><td>8 10
qw.aba..f.
wq.bab.ff.
zx.cdc.K.R
c.ababa.es
x.babab.Ed
j.cdcdcaba
yo.k.k.bab
opu..l.cdc
3 3
</td><td>
3 3
aba
bab
cdc
4
1 4
4 3
4 5
6 8
</td></tr></table>
