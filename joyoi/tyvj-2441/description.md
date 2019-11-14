# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2441/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjQ0MS9wcm9ibGVtc19pbWFnZXMvMjgzOS8xNTY2XzEuanBn.jpg"><br><img border="0" src="/source/joyoi/tyvj-2441/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjQ0MS9wcm9ibGVtc19pbWFnZXMvMjgzOS8xNTY2XzIuanBn.jpg"><br><br></p> 

 
 # 输入格式 
<p>
第一行包含两个整数n, m，分别表示上下两个管道中球的数目。<br>第二行为一个AB字符串，长度为n，表示上管道中从左到右球的类型。其中A表示浅色球，B表示深色球。<br>第三行为一个AB字符串，长度为m，表示下管道中的情形。 <br></p> 

 
 # 输出格式 
<p>
仅包含一行，即为 Sigma(Ai^2) i从1到k 除以1024523的余数。 <br><br></p> 

 
 # 提示 
<p>
样例即为文中(图3)。共有两种不同的输出序列形式，序列BAB有1种产生方式，而序列BBA有2种产生方式，因此答案为5。 <br>【大致数据规模】<br>约30%的数据满足 n, m ≤ 12； <br>约100%的数据满足n, m ≤ 500。<br><br></p> 
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
<tr><td>2 1
AB
B

</td><td>5</td></tr></table>
