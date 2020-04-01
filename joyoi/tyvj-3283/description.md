# 

 
 # 题目描述 
<p>
所有的M数<br><br>问题描述:<br>　　n个数排成一排。一个数的M数是指的在这个数的左边且比它小的数中最靠近它（即最靠右）的那个数。依次给出这n个数，请求出所有这n个数相对应的M数。<br></p> 

 
 # 输入格式 
<p>
　　从文件allm.in中读入数据。<br>　　数据的第一行是一个正整数n，表示一共有多少个数。<br>　　第二行有n个用空格隔开的正整数，它们从左至右给出了数列中的n个数。这些数保证小于2^31。<br><br></p> 

 
 # 输出格式 
<p>
　　输出一行用空格隔开的n个数到文件allm.out。<br>　　这些数对应输入数据中的数的M数。如果输入中某个数没有M数（即它左边的数都不比它小），请输出0。<br></p> 

 
 # 提示 
<p>
时间限制：<br>　　各测试点1秒。<br><br>内存限制：<br>　　你的程序将被分配10MB的运行空间。<br><br>数据规模：<br>　　对于50%的数据，n <= 1000；<br>　　对于100%的数据，n <= 500 000。<br><br></p> 
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
<tr><td>7
3 1 2 7 6 7 4
</td><td>0 0 1 2 2 6 2
</td></tr></table>
