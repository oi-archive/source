# 

 
 # 题目背景 
"天空吹过蓝色的风，我每天都流着泪，做着肥皂般繁华的梦。"在某天晚上，小v从梦中醒来，望着天空里的星星，想摘下一串送给自己的她。<BR> 

 
 # 题目描述 
天空中有一个星座，星座里面的星星被神秘的星线连接成了一个树状的结构，每个星星最多有两个子结点。每个星星都有一定的重量，标记摘第i标号（&lt;6000）的星星重量为Si，摘去规则如下：<BR>&nbsp;&nbsp;&nbsp;对于未摘出的星星，可以选择摘取它，再对其左(右)子女进行重复摘取（即如果第一次选择左子女，摘取顺序就应为：当前星星，左子女，左子女的左子女。。组成一条不间断的星串（可以在任意位置结束，不必到没有左子女为止）(右子女类比于左子女)）{当然摘掉的下次就不能再重复摘取了}，则该次摘取耗费的体力值为星串中所有星星的重量乘积；也可以单独摘取当前星星，耗费体力值即为星星重量值。<BR>总耗费的体力值为每次摘取耗费体力值之和，现在小v想让你帮他设计一个方案，使得把所有星星拆成串时所耗费的体力值最小，你能帮他吗？<BR><BR> 

 
 # 输入格式 
&nbsp;一个整数n，表示该星座中有n个星星<BR>&nbsp;&nbsp;&nbsp;接下来n行，每行四个整数，分别表示为该星星的标号、摘该星星的体力值、其左子女的标号（如果没有则为0），其右子女的标号（同上）<BR><BR><BR> 

 
 # 输出格式 
一个整数s，表示所耗费的最小体力值。<BR> 

 
 # 提示 
数据范围：<BR>对于30%的数据，0&lt;n&lt;=10<BR>对于60%的数据，0&lt;n&lt;=100<BR>对于100%的数据，0&lt;n&lt;=5000,0&lt;=Si&lt;=10<BR><BR>附拆分图解（样例）：<BR><img src="/source/joyoi/tyvj-1292/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI5Mi9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nL3AxMjkyLnBuZw==.png" border=0 align=middle><BR><BR><BR> 
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
1 1 2 5
5 4 0 0
3 5 0 0
2 3 3 4
4 7 0 0


</td><td>19

</td></tr></table>
