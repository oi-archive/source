# 

 
 # 题目描述 
<p>
最近，Elaxia和w**的关系特别好，他们很想整天在一起，但是大学的学习太紧张了，他们<br>必须合理地安排两个人在一起的时间。Elaxia和w**每天都要奔波于宿舍和实验室之间，他们<br>希望在节约时间的前提下，一起走的时间尽可能的长。<br>现在已知的是Elaxia和w**所在的宿舍和实验室的编号以及学校的地图：地图上有N个路<br>口，M条路，经过每条路都需要一定的时间。<br>具体地说，就是要求无向图中，两对点间最短路的最长公共路径。</p> 

 
 # 输入格式 
<p>
第一行：两个整数N和M（含义如题目描述）。<br>第二行：四个整数x1、y1、x2、y2（1 ≤ x1 ≤ N，1 ≤ y1 ≤ N，1 ≤ x2 ≤ N，1 ≤<br>≤ N），分别表示Elaxia的宿舍和实验室及w**的宿舍和实验室的标号（两对点分别<br>x1,y1和x2,y2）。<br>接下来M行：每行三个整数，u、v、l（1 ≤ u ≤ N，1 ≤ v ≤ N，1 ≤ l ≤ 10000），表<br>u和v之间有一条路，经过这条路所需要的时间为l。<br>出出出格格格式式式：：：<br>一行，一个整数，表示每天两人在一起的时间（即最长公共路径的长度）。</p> 

 
 # 输出格式 
<p>
一行，一个整数，表示每天两人在一起的时间（即最长公共路径的长度）</p> 

 
 # 提示 
<p>
对于30%的数据，N ≤ 100；<br>对于60%的数据，N ≤ 1000；<br>对于100%的数据，N ≤ 1500，输入数据保证没有重边和自环。</p> 
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
<tr><td>9 10
1 6 7 8
1 2 1
2 5 2
2 3 3
3 4 2
3 9 5
4 5 3
4 6 4
4 7 2
5 8 1
7 9 1
</td><td>3</td></tr></table>
