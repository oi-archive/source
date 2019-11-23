# 

 
 # 题目背景 
裸体就意味着身体。 

 
 # 题目描述 
“第一分钟，X说，要有矩阵，于是便有了一个里面写满了0的n×m矩阵。<BR>第二分钟，L说，要能修改，于是便有了将左上角为(a,b)，右下角为(c,d)的一个矩形区域内的全部数字加上一个值的操作。<BR>第三分钟，k说，要能查询，于是便有了求给定矩形区域内的全部数字和的操作。<BR>第四分钟，彩虹喵说，要基于二叉树的数据结构，于是便有了数据范围。<BR>第五分钟，和雪说，要有耐心，于是便有了时间限制。<BR>第六分钟，吃钢琴男说，要省点事，于是便有了保证运算过程中及最终结果均不超过32位有符号整数类型的表示范围的限制。<BR>第七分钟，这道题终于造完了，然而，造题的神牛们再也不想写这道题的程序了。”<BR>							——《上帝造裸题的七分钟》<BR>所以这个神圣的任务就交给你了。<BR> 

 
 # 输入格式 
输入数据的第一行为X&nbsp;n&nbsp;m，代表矩阵大小为n×m。<BR>从输入数据的第二行开始到文件尾的每一行会出现以下两种操作：<BR>&nbsp;&nbsp;&nbsp;&nbsp;L&nbsp;a&nbsp;b&nbsp;c&nbsp;d&nbsp;delta	——&nbsp;代表将(a,b),(c,d)为顶点的矩形区域内的所有数字加上delta。<BR>&nbsp;&nbsp;&nbsp;&nbsp;k&nbsp;a&nbsp;b&nbsp;c&nbsp;d&nbsp;&nbsp;&nbsp;&nbsp;	——&nbsp;代表求(a,b),(c,d)为顶点的矩形区域内所有数字的和。<BR><BR>请注意，k为小写。<BR> 

 
 # 输出格式 
针对每个k操作，在单独的一行输出答案。 

 
 # 提示 
对于10%的数据，1&nbsp;≤&nbsp;n&nbsp;≤&nbsp;16,&nbsp;1&nbsp;≤&nbsp;m&nbsp;≤&nbsp;16,&nbsp;操作不超过200个.<BR>对于60%的数据，1&nbsp;≤&nbsp;n&nbsp;≤&nbsp;512,&nbsp;1&nbsp;≤&nbsp;m&nbsp;≤&nbsp;512.<BR>对于100%的数据，1&nbsp;≤&nbsp;n&nbsp;≤&nbsp;2048,&nbsp;1&nbsp;≤&nbsp;m&nbsp;≤&nbsp;2048,&nbsp;1&nbsp;≤&nbsp;delta&nbsp;≤&nbsp;500,操作不超过200000个,保证运算过程中及最终结果均不超过32位带符号整数类型的表示范围。<BR>by&nbsp;XLk 
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
<tr><td>X 4 4
L 1 1 3 3 2
L 2 2 4 4 1
k 2 2 3 3
</td><td>12
</td></tr></table>
