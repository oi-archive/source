# 

 
 # 题目描述 
<p>
拦截匪徒问题（catch.pas/c/cpp）<br><br>【问题描述】<br>　　Lordaeron市的地图是一个由N个点组成的无向图。每个点代表一个区。现在第P区发生了抢劫案，而警察为了截住劫匪，得埋伏在一个劫匪必经的区域。由于不知道劫匪会向哪个区域逃窜，所以Arthas市长要求你计算出对于任意一个劫匪可能逃向的区J，找出一个一定可以截住劫匪的区K（K<>p,k<>j），即劫匪从P区逃向J区，必经过K区。由于地区J可能为匪徒的老巢所在，所以警察希望能在路上拦住匪徒，而不是前往J区。<br></p> 

 
 # 输入格式 
<p>
　　输入文件catch.in第一行为N，P（1<=P<=N<=200)<br>　　接下来为N*N的矩阵A，Aij=1表示I区与j区有路相连，Aij=0则反之。<br></p> 

 
 # 输出格式 
<p>
　　输出文件catch.out输出N-1行，按顺序从j=1,2,…p-1,p+1,…,n依次输出对于每一个j，警察可以在哪些点埋伏。有多个点的话，要按从小到大顺序依次输出。没有的话那一行输出NO。<br></p> 
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
<tr><td>5 1
0 1 1 0 0
1 0 1 1 0
1 1 0 0 0
0 1 0 0 1
0 0 0 1 0
</td><td>NO
NO
2
2 4</td></tr></table>
