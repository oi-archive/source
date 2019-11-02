# 

 
 # 题目背景 
JSOI&nbsp;2009第一试第一题 

 
 # 题目描述 
“一个长度为l的数列a[i]，若相邻两数之间的差a[i]-a[i-1](2&lt;=i&lt;=l)全部相同，则这个数列为等差数列。”火星特级数学老师jyy，正在给他的火星学生们上数学课。<BR>为了检验学生的掌握情况，jyy布置了一道习题：给定一个长度为N(1&lt;=N&lt;=100000)的数列，初始时第i个数为vi（vi是整数，-100000&lt;=vi&lt;=100000),学生们要按照jyy的给出的操作步骤来改变数列中某些项的值。操作步骤的具体形式为:"A&nbsp;s&nbsp;t&nbsp;a&nbsp;b"(s,t,a,b均为整数，1&lt;=s&lt;=t&lt;=N,-100000&lt;=a,b&lt;=100000),它表示，在序列的[s,t]区间上加上初值为a，步长为b的等差数列。即vi变为vi+a+b*(i-s)(对于s&lt;=i&lt;=t)。<BR>在焦头烂额地计算之余，可怜的火星学生还得随时回答jyy提出的问题。问题的形式为："B&nbsp;s&nbsp;t"(s,t均为整数，1&lt;=s&lt;=t&lt;=N),表示jyy询问当前序列的[s,t]区间最少能划分成几段，使得每一段都是等差数列。比如说1&nbsp;2&nbsp;3&nbsp;5&nbsp;7最少能划分成2段，一段是1&nbsp;2&nbsp;3，另一段是5&nbsp;7。询问是需要同学们计算出答案后，作为作业交上来的。<BR>虽然操作数加问题数总共只有Q(1&lt;=Q&lt;=100000)个，jyy还是觉得这个题很无聊很麻烦。于是他想让你帮他计算一份标准答案。 

 
 # 输入格式 
第一行：1个整数N，第2..N+1行：每行一个整数。第i+1行表示vi。<BR>第N+2行：1个整数Q，第N+3..N+Q+2行：每行描述了一个操作或问题，格式如题中所述，不含引号。 

 
 # 输出格式 
若干行，每行一个整数，表示对一个问题的回答。请按照输入中的顺序依次给出答案。 

 
 # 提示 
样例说明：原数列1&nbsp;3&nbsp;-1&nbsp;-4&nbsp;7.经过操作之后，数列变为1&nbsp;2&nbsp;3&nbsp;5&nbsp;7.如题目中所述，最少能划分成2段。<BR>数据规模&nbsp;对30%的数据，N，Q&lt;=5000 
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
<tr><td>5
1
3
-1
-4
7
2
A 2 4 -1 5
B 1 5</td><td>2
</td></tr></table>
