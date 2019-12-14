# 

 
 # 题目描述 
<p>
在桌面上有一排硬币，共N枚，每一枚硬币均为正面朝上。现在要把所有的硬币翻转成反面朝上，规则是每次可翻转任意N-1枚硬币（正面向上的被翻转为反面向上，反之亦然）。求一个最短的操作序列（将每次翻转N-1枚硬币称为一次操作）。</p> 

 
 # 输入格式 
<p>
只有一个自然数N（N为不大于100的偶数）。</p> 

 
 # 输出格式 
<p>
	输出文件的第一行包含一个整数S，表示最少需要的操作次数。接下来的S行每行分别表示每次操作后桌上硬币的状态（一行包含N个整数（0或1），表示每个硬币的状态：0——正面向上，1——反面向上，不允许出现多余空格）。<br>对于有多种操作方案的情况，则只需输出一种。<br></p> 
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
<tr><td>4</td><td>4
0111
1100
0001
1111</td></tr></table>
