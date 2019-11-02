# 

 
 # 题目描述 
<p>
[问题描述]<br>　　兴趣小组的同学来自各个学校，为了增加友谊，晚会上又进行了一个传话游戏，如果a认识b，那么a收到某个消息，就会把这个消息传给b，以及所有a认识的人。<br>　　如果a认识b，b不一定认识a。<br>　　所有人从1到n编号，给出所有“认识”关系，问如果i发布一条新消息，那么会不会经过若干次传话后，这个消息传回给了i，1 <= i <= n 。<br></p> 

 
 # 输入格式 
<p>
[输入文件]<br>　　输入文件message.in中的第一行是两个数n( n < 1000)和m( m < 10000 )，两数之间有一个空格，表示人数和认识关系数。<br>　　接下来的m行，每行两个数a和b，表示a认识b。1 <= a, b <= n。认识关系可能会重复给出，但一行的两个数不会相同。<br></p> 

 
 # 输出格式 
<p>
[输出文件]<br>　　输出文件message.out中一共有n行，每行一个字符T或F。第i行如果是T，表示i发出一条新消息会传回给i；如果是F，表示i发出一条新消息不会传回给i。<br></p> 
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
<tr><td>4 6
1 2
2 3
4 1
3 1
1 3
2 3
</td><td>T
T
T
F
</td></tr></table>
