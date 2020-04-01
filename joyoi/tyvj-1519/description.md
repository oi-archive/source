# 

 
 # 题目背景 
Bob最近迷上了一个博彩游戏……<BR> 

 
 # 题目描述 
这个游戏的规则是这样的：<BR>每花一块钱可以得到一个随机数R，花上N块钱就可以得到一个随机序列；<BR>有M个序列，如果某个序列是产生的随机序列的子串，那么就中奖了，否则不中。<BR>Bob会告诉你这M个序列，和身上有的钱的总数N，当然还有R的范围。<BR>请你告诉Bob中奖的概率有多少？ 

 
 # 输入格式 
第一行三个用空格隔开的数N、M和R的范围R。<BR>其中1&lt;=R&lt;=9，0&lt;N&lt;=60，0&lt;M&lt;=20000。<BR>下面M行每行一个字符串（长度小于等于20），字符串的每一位范围在1-r之间<BR>保证必要运算都在64位整型范围内。<BR> 

 
 # 输出格式 
一行一个实数，表示中奖的概率（保留小数点后5位小数）。<BR> 

 
 # 提示 
数据分布：<BR>第1个点~第10个点，每个点5分；<BR>第11个点~第15个点，每个点10分。<BR><BR>对于样例的解释：<BR>随机序列一共有3^5=243个，其中包含"1"的个数为211个，则概率为211/243=0.86831Bob&nbsp;HAN<BR> 
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
<tr><td>5 1 3
1
</td><td>0.86831</td></tr></table>
