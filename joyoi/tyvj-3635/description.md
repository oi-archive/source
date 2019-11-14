# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-3635/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzYzNS9wcm9ibGVtc19pbWFnZXMvMjQ4OC8xMTk0XzEuanBn.jpg"><br><img border="0" src="/source/joyoi/tyvj-3635/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzYzNS9wcm9ibGVtc19pbWFnZXMvMjQ4OC8xMTk0XzIuanBn.jpg"><br><br></p> 

 
 # 输入格式 
<p>
第一行是一个正整数S，表示宝盒上咒语机的个数，（1≤S≤50）。文件以下分为S块，每一块描述一个咒语机，按照咒语机0,咒语机1&#8222;&#8222;咒语机S－1的顺序描述。每一块的格式如下。 一块的第一行有两个正整数n,m。分别表示该咒语机中元件的个数、咒语源输出元的个数（1≤m≤n≤50）。 接下来一行有m个数，表示m个咒语源输出元的标号（都在0到n-1之间）。<br>接下来有n行，每一行两个数。第i行（0≤i≤n-1）的两个数表示pi,0和pi,1（当然，都在0到n-1之间）。</p> 

 
 # 输出格式 
<p>
第一行有一个正整数t,表示最长升级序列的长度。</p> 
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
1 1
0
0 0
2 1
0
1 1
0 0
3 1
0
1 1
2 2
0 0
4 1
0
1 1
2 2
3 3
0 0

</td><td>3</td></tr></table>
