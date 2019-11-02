# 

 
 # 题目描述 
<p>
Intervals<br>代号：PRZ<br>　　现给定n个闭区间[ai, bi]，1 <= i <= n。这些区间的并可以表示为一些不相交的闭区间的并。你的任务就是在这些表示方式中找出包含最少区间的方案。你的输出应该按照区间的升序排列。这里如果说两个区间[a, b]和[c, d]是按照升序排列的的，那么我们有a <= b < c <= d。<br><br>任务：<br>　　请写一个程序：<br>　　　在文本文件PRZ.IN中读入这些区间；<br>　　　计算满足给定条件的不相交闭区间；<br>　　　把这些区间按照升序输出到文件PRZ.OUT中。<br></p> 

 
 # 输入格式 
<p>
　　在文本文件PRZ.IN的第一行包含一个整数n，3 <= n <= 50000，为区间的数目。以下n行为对区间的描述，第i行为对第i个区间的描述，为两个整数1 <= ai <= bi <= 1000000，表示一个区间[ai, bi]。<br></p> 

 
 # 输出格式 
<p>
　　你应该在文本文件PRZ.IN中输出计算出来的不相交的区间。每一行都是对一个区间的描述，包括两个用空格分开的整数，为区间的上下界。你应该把区间按照升序排序。<br></p> 
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
5 6
1 4
10 10
6 9
8 10
</td><td>1 4
5 10
</td></tr></table>
