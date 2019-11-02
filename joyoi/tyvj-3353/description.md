# 

 
 # 题目描述 
<p>
超级市场（supermarket.pas\c\cpp） <br><br>【题目描述】 <br>　　超市里有一批商品prod需要销售。每件商品x∈prod都有一个销售期限dx，商品x在其销售期限dx内售出后可获得利润px。销售期限dx是一个时间单位的整数倍，每件商品的销售过程都需要1个完整的时间单位（也即，每个时间单位只能销售一件商品）。你的任务是对给定px和dx的一批商品，安排其销售顺序，使其销售利润最大化。<br>　　例如一批商品prod={a，b，c，d}，其中(pa,da)=(50,2)（表示商品a的销售利润是50，销售期限是2个时间单位），(pb,db)=(10,1), (pc,dc)=(20,2),  (pd,dd)=(30,1)。则可能的销售顺序如右表所示，其中{d，a}表示在时间0开始销售商品d，在时间1完成销售商品d，同时开始销售商品a，在时间2完成销售商品a。这样d和a两件商品分别在其销售期限内得以完成销售，共获得利润80。这个利润是所有销售顺序中最大的。<br><br><center><img src="/source/joyoi/tyvj-3353/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM1My9wcm9ibGVtc19pbWFnZXMvMjEzMS8xLmpwZw==.jpg"></img></center></p> 

 
 # 输入格式 
<p>
　　输入文件supermarket.in：<br>　　包含n+1行，其中第一行是一个整数n（0≤n≤10000），表示共有n件商品，接下来n行数据表示n件商品的销售利润和销售期限，每行两个正整数，第一个数表示该商品的销售利润p（1≤p≤10000），第二个数表示该商品的销售期限d（1≤d≤10000）。数与数之间用空格隔开。<br></p> 

 
 # 输出格式 
<p>
　　输出文件supermarket.out：<br>　　只包含1个正整数，表示最大销售利润数。<br></p> 
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
<tr><td>7
20  1
2   1
10  3
100  2
8   2
5   20
50  10
</td><td>185</td></tr></table>
