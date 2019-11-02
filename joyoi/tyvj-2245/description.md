# 

 
 # 题目描述 
<p>
给你一个N个点M条边的图(M >= N - 1)，每条边有个权值Ci，前面N – 1条边构成一颗树，现在你需要给每条边伪造一个权值Di，使得前N– 条边构成的生成树是该图的最小生成树，并且使Sigma(Di)-Sigma(Ci)(1<=i<=M 最小。<br></p> 

 
 # 输入格式 
<p>
第一行两个数N, M。<br>接下来M行每行三个数ai,bi,ci，表示一条边，保证无重边无自环。<br><br></p> 

 
 # 输出格式 
<p>
仅一行，表示最小花费。<br></p> 

 
 # 提示 
<p>
30%的数据，N<=60, M <= 400。<br>100%的数据，N<=1000, M<= 10000。<br></p> 
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
<tr><td>4 5 
4 1 7 
2 1 5 
3 4 4 
4 2 5 
1 3 1
</td><td>
6</td></tr></table>
