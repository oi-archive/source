# 

 
 # 题目描述 
<p>
停机位置（rebel.pas/c/cpp）<br><br>【题目描述】<br><br>　　太空漫步者Luke带领着他的反抗军舰队，成功推翻了Endor星的帝国统治。舰队怀着胜利后的喜悦，会到他们的主基地去膜拜女神苍井空。<br>　　他们正飞向停机场，停机场有N个停机位置排成一行，标号从1到N依次排列。舰队中共有N个飞船，每个飞船都有标号和等级，标号为i的飞船的等级记为Ri。飞船依次到达停机场，但舰队有一个不成文的规定：飞船所停的位置，其标号不能大于飞船的等级。<br>　　问有多少种不同的R序列，使得所有的飞船都能找到其停机位置？<br></p> 

 
 # 输入格式 
<p>
第一行一个正整数case，为数据的组数。<br>接下来case行每行代表一组数据，为一个正整数N，如题所示。<br></p> 

 
 # 输出格式 
<p>
对于每组数据，输出所求的答案mod 100 000 007。<br></p> 

 
 # 提示 
<p>
【数据范围】<br>对于10%的数据，有1≤N≤8<br>对于20%的数据，有1≤N≤100<br>对于100%的数据，有1≤N≤1000000</p> 
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
1
2
3</td><td>1
3
16</td></tr></table>
