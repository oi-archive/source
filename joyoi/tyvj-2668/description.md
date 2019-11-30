# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2668/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjY2OC9wcm9ibGVtc19pbWFnZXMvMzE0MS8xODcxLmpwZw==.jpg"> </p> 

 
 # 输入格式 
<p>
输入文件的第一行为一个整数 N(N ≤ 10)和 M(1 ≤ M ≤ 1000)，表示属性集中<br>的属性个数和函数依赖集中的依赖个数。这里我们默认大写字母中的前 N 个字<br>母为我们所考虑的属性。接下来的 M 行每行一个字符串表示一个函数依赖，如<br>AB-->DE。(中间的蕴含符号是由减号和大于号组成。另外需要说明的是，只有当<br>我们同时得到 A和 B 的时候，才能推出D和 E） 。 <br></p> 

 
 # 输出格式 
<p>
第一行希望你输出你找到的候选码的个数K。 接下来的 K行每行<br>输出一个候选码。候选码本身按字母顺序排列，所有候选码按照字典顺序排列输<br>出。如果没有找到候选码，输出“No candidate key”(不含引号)。 <br> </p> 

 
 # 提示 
<p>
对于30%的测试数据，满足只有二元联系(即不存在函数依赖左边或右边的<br>属性个数超过 1 个)。 <br>对于 40%的测试数据，满足N ≤ 5。 <br>对于 70%的测试数据，满足M ≤ 100。 <br>对于100%的测试数据，满足 1 ≤ N ≤ 10, 1 ≤ M ≤ 1000。 <br> </p> 
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
<tr><td>5 5 
AB->C 
AC->B 
AD->E 
BC->D 
E->A 
</td><td>4 
AB 
AC 
BE 
CE </td></tr></table>
