# 

 
 # 题目描述 
n阶拉丁方指满足每行、每列都恰好包含1~n这n个正整数的n阶方阵。<BR>一个四阶拉丁方的例子：<BR>1&nbsp;4&nbsp;2&nbsp;3<BR>4&nbsp;2&nbsp;3&nbsp;1<BR>2&nbsp;3&nbsp;1&nbsp;4<BR>3&nbsp;1&nbsp;4&nbsp;2<BR>将一个拉丁方的某两行（或某两列）完全对换，称作一次变换。容易知道变换过后的矩阵仍然是一个拉丁方。<BR>例如，变换上面这个拉丁方的第1、3列，得到新的拉丁方如下：<BR>2&nbsp;4&nbsp;1&nbsp;3<BR>3&nbsp;2&nbsp;4&nbsp;1<BR>1&nbsp;3&nbsp;2&nbsp;4<BR>4&nbsp;1&nbsp;3&nbsp;2<BR>再变换它的2、4行，得到：<BR>2&nbsp;4&nbsp;1&nbsp;3<BR>4&nbsp;1&nbsp;3&nbsp;2<BR>1&nbsp;3&nbsp;2&nbsp;4<BR>3&nbsp;2&nbsp;4&nbsp;1<BR>假如由一个拉丁方经过若干次变换能够得到另一个，则称这两个拉丁方是同构的。<BR> 

 
 # 输入格式 
输入第一行是一个正整数n。<BR>接下来的n行，每行包括n个数，表示第一个拉丁方。<BR>接下来是一个空行。<BR>再接下来的n行，每行包括n个数，表示第二个拉丁方。<BR>输入数据都是正确的，不必检验。<BR> 

 
 # 输出格式 
输入包括一行：如果两个拉丁方不是同构的，输出-1；如果是同构的，请输出一个整数m，表示由第一个拉丁方变换到第二个所需的最少变换次数。 

 
 # 提示 
对于20%的数据，3≤n≤5；<BR>对于60%的数据，3≤n≤50；<BR>对于100%的数据，3≤n≤300。<BR>寒假模拟赛&nbsp;提高组&nbsp;day2-2 
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
<tr><td>4
1 4 2 3
4 2 3 1
2 3 1 4
3 1 4 2

2 4 1 3
4 1 3 2
1 3 2 4
3 2 4 1
</td><td>2
</td></tr></table>
