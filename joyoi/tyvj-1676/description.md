# 

 
 # 题目背景 
Admin:314!你的题目呢？？？？<BR>西部314:额….前几天我生病了…电脑碰都没碰…….<BR>Admin:你自己说要出题的！<BR>西部314:…… 

 
 # 题目描述 
我们定义应急数字为，只有1,2,3,4,5组成，且相邻数字恰好相差1的整数。<BR>那么我们要关注到一个问题，对于给定的n，位数为n的应急数字的个数f(n)为多少？<BR><BR>由于是应急题目，这里只需要输出f(n)&nbsp;mod&nbsp;k,这里k也为输入的数。<BR> 

 
 # 输入格式 
第一行是一个正整数t，表示输入的组数<BR>之后T行每一行有两个正整数n,k,含义见题目<BR> 

 
 # 输出格式 
共T行，第i行输出对应输入第i+1行的f(n)&nbsp;mod&nbsp;k.<BR>这里mod是求余数的意思。<BR> 

 
 # 提示 
20%的数据有n&lt;=10,k&lt;=1000,t=1;<BR>50%的数据有n&lt;=1000,k&lt;=100000,t=2;<BR>60%的数据有n&lt;=100000,k&lt;=100000,t=2;<BR>80%的数据有n&lt;=10^14,k&lt;maxlongint,t=2;<BR>100%的数据有2&lt;=n&lt;=10^14,1&lt;k&lt;maxlongint,t&lt;=60000<BR>来自西部314&nbsp;七号苦情赛 
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
<tr><td>1
2 21474
</td><td>8
</td></tr></table>
