# 

 
 # 题目背景 
Candy的生日即将到来，飘飘乎居士希望找到一个最美妙的矩阵送个Candy作为礼物<BR> 

 
 # 题目描述 
飘飘乎居士从Pink处得知最美妙的矩阵满足三个条件：首先，它的长和宽都必须和矩阵的边界平行（也就是不可以出现斜的矩阵）；第二：子矩阵横竖都要满足单调递增（可以相等，也就是对于每一个最优子矩阵的元素都要满足a[i][j]&gt;=a[i-1][j]&nbsp;and&nbsp;a[i][j]&gt;=a[i][j-1]，其中a[i][j]表示矩阵第i行第j列的数字）；第三：最优矩阵是在满足上述两个条件中面积最大的矩阵。 

 
 # 输入格式 
第一行，两个正整数n，m<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来n行，每行m个数字，构成一个n*m的矩阵<BR><BR> 

 
 # 输出格式 
一行，代表最优矩阵的面积<BR> 

 
 # 提示 
最优子矩阵为<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;4&nbsp;4<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4&nbsp;4&nbsp;4<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;该矩阵满足横竖都单调递增，并且是所有满足条件中面积最大的。其中矩阵长为3宽为2，面积为6，也就是最后的答案。<BR>对于30%的数据&nbsp;&nbsp;0&lt;n&nbsp;m&lt;=50<BR>对于100%的数据&nbsp;0&lt;n&nbsp;m&lt;=200<BR>对于所有数据&nbsp;a[i][j]&lt;=20000000<BR><BR> 
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
<tr><td>3 4
2 4 4 4
4 4 4 2
3 4 2 5
</td><td>6
</td></tr></table>
