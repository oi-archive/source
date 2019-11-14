# 

 
 # 题目描述 
给定一个长度为N的序列，起始时所有数都为0.以后有2种操作：<BR>1:对于操作1，读入两个数x,y，表示从x到y把对应的序列上的数都做取反操作。即，该位置是0，操作以后为1；该位置是1，操作以后是0。<BR>2:对于操作2，读入一个数x，输出当前序列中x位置上的数字。<BR>对于两种操作，共有p次。<BR> 

 
 # 输入格式 
第一行，一个数N；<BR>第二行，一个数p；<BR>以后p行，每行第一个数表示操作k，k=1或2；对于k=1，读入两个数x，y；对于k=2，读入一个数x。 

 
 # 输出格式 
对于每一个操作2，输出一行，一个数为所求。 

 
 # 提示 
对于10%的数据，N&lt;=10；<BR>对于20%的数据，N&lt;=100；<BR>对于30%的数据，N&lt;=1000；<BR>对于50%的数据，N&lt;=10000；<BR>对于100%的数据，N&lt;=100000。<BR> 
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
3
1 1 2
2 2
2 3</td><td>1
0</td></tr></table>
