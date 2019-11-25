# 

 
 # 题目描述 
轰地一声，applepi和sideman的大战开始了。为了躲避手持凳子的applepi，sideman使出瞬移绝技在机房里到处乱窜。但是不幸的是，applepi也有一双神眼，能够统计sideman在乱窜中会在哪些地方出现，以及出现的次数。于是他就可以抄起板凳往次数最多的那个位置砸去，毕竟这样砸中的几率比较高嘛。但是由于高一的同学也在机房的某些位置，applepi不能砸向高一同学所在的位置。 

 
 # 输入格式 
第一行两个数n，m，表示sideman有可能在某n个位置出现、机房里有m个高一的同学。<br>接下来n行，每行两个整数x，y，代表sideman出现的坐标位置。<br>接下来m行，每行两个整数x，y，代表高一同学所在的坐标位置。<br>数据保证对于坐标不同的位置，x，y的和不相同。<br> 

 
 # 输出格式 
applepi将会砸向的坐标位置的横坐标x，纵坐标y，中间用空格隔开。若有多个位置可以砸，输出x+y最小的那个位置。保证可以有地方砸。 

 
 # 提示 
对于&nbsp;100%&nbsp;的数据，保证1&lt;=n,m&lt;=1000,0&lt;=x,y&lt;=1000000。 
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
<tr><td>3 1
1 2
2 2
1 2
1 2
</td><td>2 2</td></tr></table>
