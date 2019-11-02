# 

 
 # 题目描述 
<p>
FJ's N (1 <= N <= 10,000) cows conveniently indexed 1..N are standing<br>in a line.  Each cow has a positive integer height (which is a bit<br>of secret). You are told only the height H (1 <= H <= 1,000,000)<br>of the tallest cow along with the index I of that cow.<br><br>FJ has made  a list of R (0 <= R <= 10,000) lines of the form "cow<br>17 sees cow 34". This means that cow 34 is at least as tall as cow<br>17, and that every cow between 17 and 34 has a height that is<br>strictly smaller than that of cow 17.<br><br>For each cow from 1..N, determine its maximum possible height, such<br>that all of the information given is still correct. It is guaranteed<br>that it is possible to satisfy all the constraints.<br><br>有n(1 <= n <= 10000)头牛从１到n线性排列，每头牛的高度为h[i](1 <= i <= n),现在告诉你这里面的牛的最大高度为maxH,而且有r组关系，每组关系输入两个数字，假设为a和b,表示第a头牛能看到第b头牛，能看到的条件是a, b之间的其它牛的高度都严格小于min(a, b),而b >= a.要求输出每头牛的最大高度。</p> 

 
 # 输入格式 
<p>
* Line 1: Four space-separated integers: N, I, H and R<br><br>* Lines 2..R+1: Two distinct space-separated integers A and B (1 <= A,<br>        B <= N), indicating that cow A can see cow B.<br><br></p> 

 
 # 输出格式 
<p>
* Lines 1..N: Line i contains the maximum possible height of cow i.<br><br></p> 
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
<tr><td>9 3 5 5
1 3
5 3
4 3
3 7
9 8


INPUT DETAILS:

There are 9 cows, and the 3rd is the tallest with height 5.
</td><td>5
4
5
3
4
4
5
5
5</td></tr></table>
