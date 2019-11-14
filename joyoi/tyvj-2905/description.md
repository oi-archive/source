# 

 
 # 题目描述 
<p>
cc是个超级帅哥，口才又好，rp极高（这句话似乎降rp），又非常的幽默，所以很多mm都跟他关系不错。然而，最关键的是，cc能够很好的调解各各妹妹间的关系。mm之间的关系及其复杂，cc必须严格掌握她们之间的朋友关系，好一起约她们出去，cc要是和不是朋友的两个mm出去玩，后果不堪设想……<br> cc只掌握着一些mm之间的关系，但是cc比较聪明，他知道a和b是朋友，b和c 是朋友，那么a和c也是朋友。<br>下面给出m对朋友关系, cc 定了p次约会，每次约会找两个mm，如果这两个mm是朋友，那么不会出乱子，输出‘safe’，要是不是朋友，那么cc必然会挨……，输出‘cc cry’（T_T）。<br></p> 

 
 # 输入格式 
<p>
第一行为n，m，p。n为mm的数量，cc知道m对朋友关系，有p次约会。<br>2到n+1 行，每行一个字符串，为第i个mm的名字。{字符串长度<=11,且全大写}<br>以下m行，每行两个字符串，用空格隔开 ，为有朋友关系的两个mm的名字。<br>以下p行，每行为两个字符串，用空格隔开，为这p次约会中两个mm的名字。<br>{保证数据不会出现没有出现过的名字}<br></p> 

 
 # 输出格式 
<p>
输出P行表示第i次约会的情况，输出‘safe’或者‘cc cry’</p> 

 
 # 提示 
<p>
【数据范围】<br>0 < m <= 2008<br>0 < p <= 2008<br></p> 
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
<tr><td>3 1 1
AAA
BBB
CCC
AAA CCC
AAA BBB
</td><td>cc cry</td></tr></table>
