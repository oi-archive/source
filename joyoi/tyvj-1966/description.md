# 

 
 # 题目背景 
Freda：aya&nbsp;Rainbow，怎么没看见你城堡挂旗子呀？<BR>Rainbow：我城堡旗子太难看了肿么办T_T<BR>Freda：lala~那好办，我可以帮你染色呀~<BR>Rainbow：嗯嗯，那就试试吧~&nbsp; 

 
 # 题目描述 
Rainbow城堡的旗子是一个有N个基本单位的长条&gt;_&lt;，每个单位都会被染成前m个大写字母当中的一个颜色。可是，Rainbow认为，两个相邻的单位有相同的颜色很难看的说。所以，Rainbow需要改动一些单位的颜色，使得不存在两个相邻的单位颜色相同。当然了，那些被改动的单位改动之后的颜色也是前m个大写字母当中的一个。Rainbow想请你帮忙计算，它最少要改动多少个单位的颜色才能让旗子好看呢？ 

 
 # 输入格式 
第一行两个整数N、m，表示旗子组成的基本单位数目和颜色的范围。<BR>接下来一行一个长度为N的字符串，字符串的每个字符都是在前m个大写字母的范围内的，表示Rainbow的旗帜。 

 
 # 输出格式 
&nbsp;一行一个整数表示Rainbow最少改动的单位数目。 

 
 # 提示 
样例解释:一种改动方法是ABCACA。当然，还可能有别的改动方法。<BR>对于30%的数据，N&lt;=20.<BR>对于100%的数据，N&lt;=10^5,1&lt;=m&lt;=26. 
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
<tr><td>6 3
ABBACC</td><td>2
</td></tr></table>
