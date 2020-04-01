# 

 
 # 题目描述 
<p>
打孔机是一种在票上打孔的装置， 假设票是一个M*N的矩阵，矩阵行列间距相等，你可以选择在M*N个位置上打穿或不打穿，这样就有 <br>2^(M*N)-1（至少要打一个孔）不同的方案数。 <br><br>但是我们的问题并不是这么简单的，如果两种方案经过如下的若干操作后，打穿的孔刚好重合，那么认为这两个方案是相同的： <br>&#8226;翻转 <br>&#8226;旋转0，90，180，270 <br>&#8226;平行移动 <br>显然如果两种方案上孔的数目不同，那么必然是不同的方案。现在你的问题就是给定M，N，算出所有不同的方案数。 <br><br></p> 

 
 # 输入格式 
<p>
文件包含两个数M(≤6), N (≤10) ,用空格分开。 <br></p> 

 
 # 输出格式 
<p>
只有一行，为所求的方案数。 <br></p> 
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
<tr><td>3 3

</td><td>85</td></tr></table>
