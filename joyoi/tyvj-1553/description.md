# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;和其他三个花心的oier不同。flying同学是一个特别钟情的人，不过悲剧的事，他惹她女朋友生气了。女朋友看他一直在编程就给flying制造了一个有向图。这个图有N个点，M条边。flying在点1，他的GF在点2。这显然是一个最短路问题。可生气的女孩子是不好惹的，她会砸碎一条边，而且flying无法估计哪条边会被砸碎。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在请告诉flying，从点1到点2的最坏情况下的最短路径长度 

 
 # 输入格式 
第一行两个正整数N和M，表示点数和边数<BR>接下来M行。每行三个正整数u，v，c，表示点u到点v有一条距离为c的道路<BR>（2&lt;n,m&lt;=1000） 

 
 # 输出格式 
一个整数，表示使用最优行走方案后最坏情况下的路径长度<BR>如果不存在这种情况，输出-1<BR>答案不超过maxlongint 

 
 # 提示 
L.Taring 
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
<tr><td>样例输入1
5 5
1 3 1
1 4 1
3 5 1
4 5 1
5 2 1
样例输入2
2 3
1 2 636
2 1 251
1 2 429

</td><td>样例输出1
-1
样例输出2
636
</td></tr></table>
