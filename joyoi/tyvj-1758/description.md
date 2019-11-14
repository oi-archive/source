# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;设A(N,K)是全体N位K进制整数a的集合（a的高位可以为0，例如，0023可看作一个4位8进制数，或一个4位5进制数，由题中指定的条件可以唯一确定），其中2≤K≤6000，N=2，3，4，即：<BR>&nbsp;&nbsp;&nbsp;&nbsp;A(N,K)={a|a=a1a2a3…aN，0≤ai≤K-1,&nbsp;i=1,…,N}<BR>设D(N-1,K)是A(N-1,K)的一个子集，它是由A(N,K)生成的一个N-1<BR>位K进制整数d的集合，生成规则如下<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;注1：我们称这个规则为A(N,K)&nbsp;到A(N-1,K)内的一个映射d=Image(a)，可以证明这个映射是多对一的，即：如果<BR>&nbsp;<BR>注2：对某些K,N,&nbsp;D(N-1,K)是A(N-1,K)的一个真子集，例如K=4,N=4，则不存在&nbsp;&nbsp;<BR>任务：从文本文件输入两个用空格隔开的整数&nbsp;N,K，然后在指定的文本文件中输出下列表达式的值：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;例：设N=2,K=3，则A(N,K)={00,01,02,11,10,12,20,21,22}，正确的输出结果应为14。<BR>提示：应先建立相应的计算方法，直接利用f(N,K)的表达式计算会使多数测试超时。<BR>关于测试的说明：数字完全正确，给满分。当输出结果的位数超过15位时，如果仅最后两位不准确时给一半分。（每个需测试的计算结果不超过1019）。<BR> 

 
 # 输入格式 
输入文件只有一行：用空格隔开的两个整数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;N&nbsp;&nbsp;k<BR> 

 
 # 输出格式 
输出文件只有一个大整数，为计算结果。 

 
 # 提示 
SCOI2006&nbsp;T2 
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
<tr><td> 2  3
</td><td>14
（每行以数字开始，不要有多余的空格）
</td></tr></table>
