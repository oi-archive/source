# 

 
 # 题目描述 
<p>
Problem 3 : pair<br>无序字母对<br><br>问题描述：<br>　　给定n个各不相同的无序字母对（区分大小写，无序即字母对中的两个字母可以位置颠倒）。请构造一个有n+1个字母的字符串使得每个字母对都在这个字符串中出现。<br><br></p> 

 
 # 输入格式 
<p>
　　第一行输入一个正整数n。<br>　　以下n行每行两个字母，表示这两个字母需要相邻。<br><br></p> 

 
 # 输出格式 
<p>
　　输出满足要求的字符串。<br>　　如果没有满足要求的字符串，请输出“No Solution”。<br>　　如果有多种方案，请输出前面的字母的ASCII编码尽可能小的（字典序最小）的方案<br><br></p> 

 
 # 提示 
<p>
时间限制：<br>　　各测试点1秒。<br><br>内存限制：<br>　　你的程序将被分配32MB的运行空间。<br><br>数据规模：<br>　　不同的无序字母对个数有限，n的规模可以通过计算得到。</p> 
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
<tr><td>样例输入
4
aZ
tZ
Xt
aX

</td><td>样例输出
XaZtX
</td></tr></table>
