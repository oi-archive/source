# 

 
 # 题目描述 
<p>
在 Byteotia境内有两棵非常高的树, 树上有一些洞. 一天n 只鸟飞来这里要住进这些树洞里. 他们中的有一些是好朋友想互相能访问到对方的树洞,所以他们必须遵守: 

 
 # 输入格式 
<p>
第一行三个整数n, m 和 k, 分别表示: 鸟的个数, 互相访问的鸟的对数以及输出时用到的数, 2 <= n <= 1 000 000, 1 <= m <= 10 000 000, 2 <= k <= 2 000 000. 鸟儿从1 到 n编号. 接下来m 行每行两个数ai 和 bi, 表示相连的两只鸟(1 <= ai, bi <= n,  ai <> bi). 特定的一对鸟在文件中最多出现一次. 

 
 # 输出格式 
<p>
输出总方案mod p后的数字. 
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
<tr><td>3 2 10
1 2
1 3
</td><td>4