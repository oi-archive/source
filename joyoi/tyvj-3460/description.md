# 

 
 # 题目描述 
<p>
分球（balls.pas/c/cpp)<br><br>【问题描述】<br>　　在一个装满财宝的屋子里，有2N个盒子排成一排。除了两个相邻的空盒外，其余的每个盒子里都装有一个金球或者一个银球，总共有N-1个金球和N-1个银球。以下是一个N=5时的例子，G表示金球，S表示银球：<br> <br><center><img src="/source/joyoi/tyvj-3460/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzQ2MC9wcm9ibGVtc19pbWFnZXMvMjI2OS9iYWxscy5qcGc=.jpg"></img></center><br>　　任意两个相邻的非空的盒子里的球可以移动到两个相邻的空盒中，移动不能改变这两个球的排列顺序。写一个程序，用最少的移动次数把所有的金球都移到所有的银球的左边。<br></p> 

 
 # 输入格式 
<p>
输入文件balls.in<br><br>　　输入文件包含多组数据。第一行为K，表示数据的总数。<br><br>　　每组数据的第一行是N（3≤N≤7），第二行是2N个盒子的初始状态。金球用a表示，银球用b表示，空盒用空格表示。每两组相邻数据用空行隔开。<br></p> 

 
 # 输出格式 
<p>
输出文件balls.out<br><br>　　对于每一组数据，若无解则输出一行NO SOLUTION，若有解，输出一组状态来表示移动的序列，每个状态占一行。每行输出到此状态的移动的步数，紧接着是一个空格，然后是此时的状态。初始状态为第0步，每组数据都要先输出初始状态。如有多种最少移动次数的方案，只需输出任意一种。<br><br>　　相邻的两组数据用一个空行隔开。<br></p> 
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
<tr><td>3
3
abab  

5
abba  abab

6
a  babbababa
</td><td>NO SOLUTION

0 abba  abab
1 abbabaa  b
2 a  abaabbb
3 aaaab  bbb

0 a  babbababa
1 aabbabbab  a
2 aabbab  bbaa
3 aa  abbbbbaa
4 aaaaabbbbb </td></tr></table>
