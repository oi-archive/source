# 

 
 # 题目描述 
<p>
矩形包装<br><br>问题描述：<br>　　给定4个矩形。请找出一个最小的矩形盒子使得这4个矩形可以不重叠地放置进去。<br>　　矩形放入盒子时要求矩形的边和盒子的边平行。矩形可以旋转90度后放入。<br>　　有可能存在面积均达到最小但盒子的具体长宽不一样的情况。因此，你需要把所有满足面积最小的不同规格的盒子都求出来。<br></p> 

 
 # 输入格式 
<p>
　　从文件packrec.in中读入4行数据，每行有两个用空格隔开的正整数，代表一个矩形的长和宽。这些正整数保证不超过50。</p> 

 
 # 输出格式 
<p>
　　将你的答案输出到文件packrec.out中。你的答案的第一行是一个正整数，代表最小需要的盒子大小。接下来的若干行输出所有可行的方案，分别用两个用空格隔开的正整数p和q (p<=q)来表示盒子的两个边长。这些方案的输出应该以p值的升序排列。</p> 

 
 # 提示 
<p>
时间限制：<br>　　各测试点1秒。<br><br>内存限制：<br>　　你的程序将被分配10MB的运行空间。<br></p> 
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
<tr><td>1 2
2 3
3 4
4 5

</td><td>40
4 10
5 8
</td></tr></table>
