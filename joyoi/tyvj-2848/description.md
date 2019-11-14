# 

 
 # 题目描述 
<p>
某大学准备在校园中构建校园网络，已知在校园中选好了N（N<=100）个点，并准备在这些点安装网络设备和电脑。若要将这N个点互相连接起来，问怎样连线布线才能使得总距离最短。</p> 

 
 # 输入格式 
<p>
输入文件的第一行为一个正整数N。<br>接下来有一个N*N的矩阵，矩阵中第I行第J列的数值Aij（Aij〈100）表示终端点I到终端点J的距离。<br></p> 

 
 # 输出格式 
<p>
输出最短距离。</p> 
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
0 1 4 87 21 
1 0 28 68 32 
4 28 0 17 38 
87 68 17 0 43 
21 32 38 43 0
</td><td>43</td></tr></table>
