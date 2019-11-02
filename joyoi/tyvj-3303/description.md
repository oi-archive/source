# 

 
 # 题目描述 
<p>
Problem 2 : grid<br>连接格点<br><br>问题描述：<br>　　有一个M行N列的点阵，相邻两点可以相连。一条纵向的连线花费一个单位，一条横向的连线花费两个单位。某些点之间已经有连线了，试问至少还需要花费多少个单位才能使所有的点全部连通。<br><br></p> 

 
 # 输入格式 
<p>
　　第一行输入两个正整数m和n。<br>　　以下若干行每行四个正整数x1,y1,x2,y2，表示第x1行第y1列的点和第x2行第y2列的点已经有连线。输入保证|x1-x2|+|y1-y2|=1。<br><br></p> 

 
 # 输出格式 
<p>
　　输出使得连通所有点还需要的最小花费。<br><br></p> 

 
 # 提示 
<p>
时间限制：<br>　　各测试点1秒。<br><br>内存限制：<br>　　你的程序将被分配32MB的运行空间。<br><br>数据规模：<br>　　m,n <= 1000</p> 
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
<tr><td>输入样例
2 2
1 1 2 1

</td><td>输出样例
3
</td></tr></table>
