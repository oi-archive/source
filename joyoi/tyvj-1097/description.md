# 

 
 # 题目背景 
Bless&nbsp;all&nbsp;rp++..<BR> 

 
 # 题目描述 
在一个数轴上,有n个MM(绝非恐龙!)在哭泣(5555~一直哭).<BR><BR>tcboy也在这个数轴上,并恰好看到了这一幕,由于每个MM哭都会让tcboy损失一定的rp,于是tcboy有必要去安慰她们.(真命苦啊&nbsp;T.T)<BR><BR>开始时，tcboy站在k号MM的旁边.<BR><BR>现在知道第i个MM哭泣每秒钟会使tcboy降低&nbsp;w[i]的rp&nbsp;(单位rp/s).<BR><BR>而tcboy的行走速度很慢只有1m/s&nbsp;.&nbsp;<BR><BR>tcboy安慰MM的方式很特别(怎么安慰随便大家YY了..#@$%^%$#@),不需要花费时间.<BR><BR>请计算tcboy安慰完所有MM,会消耗掉的rp的最小值.<BR><BR> 

 
 # 输入格式 
输入文件的第一行包含一个整数N，2&lt;=N&lt;=1000，表示MM的数量。<BR>第二行包含一个整数V，1&lt;=V&lt;=N，表示开始时tcboy站在几号MM的旁边.<BR>接下来的N行中，每行包含两个用空格隔开的整数D和W，用来描述每个MM，其中0&lt;=D&lt;=1000，0&lt;=W&lt;=1000。D表示MM在数轴上的位置(单位:&nbsp;m)，W表示每秒钟会使tcboy降低W的rp。<BR> 

 
 # 输出格式 
输出只有一行：一个整数，即消耗rp之和的最小值。结果不超过1,000,000,000。 

 
 # 提示 
注意结果的大小。 
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
<tr><td>4
3
2 2
5 8
6 1
8 7
</td><td>56
</td></tr></table>
