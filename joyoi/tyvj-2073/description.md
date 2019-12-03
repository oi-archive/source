# 

 
 # 题目背景 
NOIP&nbsp;2012&nbsp;提高组&nbsp;题3 

 
 # 题目描述 
小&nbsp;A&nbsp;和小&nbsp;B&nbsp;决定利用假期外出旅行,他们将想去的城市从&nbsp;1&nbsp;到&nbsp;N&nbsp;编号,且编号较小的城市在编号较大的城市的西边,已知各个城市的海拔高度互不相同,记城市&nbsp;i&nbsp;的海拔高度为Hi&nbsp;,城市&nbsp;i&nbsp;和城市&nbsp;j&nbsp;之间的距离&nbsp;d[i,j]恰好是这两个城市海拔高度之差的绝对值,即d[i,&nbsp;j]&nbsp;=&nbsp;|H&nbsp;i&nbsp;?&nbsp;Hj&nbsp;|。<br>旅行过程中,小&nbsp;A&nbsp;和小&nbsp;B&nbsp;轮流开车,第一天小&nbsp;A&nbsp;开车,之后每天轮换一次。他们计划<br>选择一个城市&nbsp;S&nbsp;作为起点,一直向东行驶,并且最多行驶&nbsp;X&nbsp;公里就结束旅行。小&nbsp;A&nbsp;和小&nbsp;B的驾驶风格不同,小&nbsp;B&nbsp;总是沿着前进方向选择一个最近的城市作为目的地,而小&nbsp;A&nbsp;总是沿着前进方向选择第二近的城市作为目的地(注意:本题中如果当前城市到两个城市的距离相同,则认为离海拔低的那个城市更近)。如果其中任何一人无法按照自己的原则选择目的城市,或者到达目的地会使行驶的总距离超出&nbsp;X&nbsp;公里,他们就会结束旅行。<br>在启程之前,小&nbsp;A&nbsp;想知道两个问题:<br>1.对于一个给定的&nbsp;X=X0,从哪一个城市出发,小&nbsp;A&nbsp;开车行驶的路程总数与小&nbsp;B&nbsp;行驶的路程总数的比值最小(如果小&nbsp;B&nbsp;的行驶路程为&nbsp;0,此时的比值可视为无穷大,且两个无穷大视为相等)。如果从多个城市出发,小&nbsp;A&nbsp;开车行驶的路程总数与小&nbsp;B&nbsp;行驶的路程总数的比值都最小,则输出海拔最高的那个城市。<br>2.&nbsp;对任意给定的&nbsp;X=Xi&nbsp;和出发城市&nbsp;Si,小&nbsp;A&nbsp;开车行驶的路程总数以及小&nbsp;B&nbsp;行驶的路程总数。 

 
 # 输入格式 
第一行包含一个整数&nbsp;N,表示城市的数目。<br>第二行有&nbsp;N&nbsp;个整数,每两个整数之间用一个空格隔开,依次表示城市&nbsp;1&nbsp;到城市&nbsp;N&nbsp;的海拔高度,即&nbsp;H1,H2,......,Hn,且每个&nbsp;Hi&nbsp;都是不同的。<br>第三行包含一个整数&nbsp;X0。<br>第四行为一个整数&nbsp;M,表示给定&nbsp;M&nbsp;组&nbsp;Si&nbsp;和&nbsp;Xi。<br>接下来的&nbsp;M&nbsp;行,每行包含&nbsp;2&nbsp;个整数&nbsp;Si&nbsp;和&nbsp;Xi,表示从城市&nbsp;Si&nbsp;出发,最多行驶&nbsp;Xi&nbsp;公里。 

 
 # 输出格式 
输出共&nbsp;M+1&nbsp;行。<br>第一行包含一个整数&nbsp;S0,表示对于给定的&nbsp;X0,从编号为&nbsp;S0&nbsp;的城市出发,小&nbsp;A&nbsp;开车行驶的路程总数与小&nbsp;B&nbsp;行驶的路程总数的比值最小。<br>接下来的&nbsp;M&nbsp;行,每行包含&nbsp;2&nbsp;个整数,之间用一个空格隔开,依次表示在给定的&nbsp;Si&nbsp;和Xi&nbsp;下小&nbsp;A&nbsp;行驶的里程总数和小&nbsp;B&nbsp;行驶的里程总数。 

 
 # 提示 
【输入输出样例&nbsp;1&nbsp;说明】<br>[图片]<br>各个城市的海拔高度以及两个城市间的距离如上图所示。<br>如果从城市&nbsp;1&nbsp;出发,可以到达的城市为&nbsp;2,3,4,这几个城市与城市&nbsp;1&nbsp;的距离分别为&nbsp;1,1,2,但是由于城市&nbsp;3&nbsp;的海拔高度低于城市&nbsp;2,所以我们认为城市&nbsp;3&nbsp;离城市&nbsp;1&nbsp;最近,城市&nbsp;2&nbsp;离城市1&nbsp;第二近,所以小&nbsp;A&nbsp;会走到城市&nbsp;2。到达城市&nbsp;2&nbsp;后,前面可以到达的城市为&nbsp;3,4,这两个城市与城市&nbsp;2&nbsp;的距离分别为&nbsp;2,1,所以城市&nbsp;4&nbsp;离城市&nbsp;2&nbsp;最近,因此小&nbsp;B&nbsp;会走到城市&nbsp;4。到达城市&nbsp;4&nbsp;后,前面已没有可到达的城市,所以旅行结束。<br>如果从城市&nbsp;2&nbsp;出发,可以到达的城市为&nbsp;3,4,这两个城市与城市&nbsp;2&nbsp;的距离分别为&nbsp;2,1,由于城市&nbsp;3&nbsp;离城市&nbsp;2&nbsp;第二近,所以小&nbsp;A&nbsp;会走到城市&nbsp;3。到达城市&nbsp;3&nbsp;后,前面尚未旅行的城市为4,所以城市&nbsp;4&nbsp;离城市&nbsp;3&nbsp;最近,但是如果要到达城市&nbsp;4,则总路程为&nbsp;2+3=5&gt;3,所以小&nbsp;B&nbsp;会直接在城市&nbsp;3&nbsp;结束旅行。<br>如果从城市&nbsp;3&nbsp;出发,可以到达的城市为&nbsp;4,由于没有离城市&nbsp;3&nbsp;第二近的城市,因此旅行还未开始就结束了。<br>如果从城市&nbsp;4&nbsp;出发,没有可以到达的城市,因此旅行还未开始就结束了。<br><br>【输入输出样例&nbsp;2&nbsp;说明】<br>当&nbsp;X=7&nbsp;时,如果从城市&nbsp;1&nbsp;出发,则路线为&nbsp;1&nbsp;-&gt;&nbsp;2&nbsp;-&gt;&nbsp;3&nbsp;-&gt;&nbsp;8&nbsp;-&gt;&nbsp;9,小&nbsp;A&nbsp;走的距离为&nbsp;1+2=3,小&nbsp;B&nbsp;走的距离为&nbsp;1+1=2。(在城市&nbsp;1&nbsp;时,距离小&nbsp;A&nbsp;最近的城市是&nbsp;2&nbsp;和&nbsp;6,但是城市&nbsp;2&nbsp;的海拔更高,视为与城市&nbsp;1&nbsp;第二近的城市,所以小&nbsp;A&nbsp;最终选择城市&nbsp;2;走到&nbsp;9&nbsp;后,&nbsp;A&nbsp;只有城市&nbsp;10&nbsp;可以走,没有第&nbsp;2&nbsp;选择可以选,所以没法做出选择,结束旅行)<br>如果从城市&nbsp;2&nbsp;出发,则路线为&nbsp;2&nbsp;-&gt;&nbsp;6&nbsp;-&gt;&nbsp;7&nbsp;,小&nbsp;A&nbsp;和小&nbsp;B&nbsp;走的距离分别为&nbsp;2,4。<br>如果从城市&nbsp;3&nbsp;出发,则路线为&nbsp;3&nbsp;-&gt;&nbsp;8&nbsp;-&gt;&nbsp;9,小&nbsp;A&nbsp;和小&nbsp;B&nbsp;走的距离分别为&nbsp;2,1。<br>如果从城市&nbsp;4&nbsp;出发,则路线为&nbsp;4&nbsp;-&gt;&nbsp;6&nbsp;-&gt;&nbsp;7,小&nbsp;A&nbsp;和小&nbsp;B&nbsp;走的距离分别为&nbsp;2,4。<br>如果从城市&nbsp;5&nbsp;出发,则路线为&nbsp;5&nbsp;-&gt;&nbsp;7&nbsp;-&gt;&nbsp;8&nbsp;,小&nbsp;A&nbsp;和小&nbsp;B&nbsp;走的距离分别为&nbsp;5,1。<br>如果从城市&nbsp;6&nbsp;出发,则路线为&nbsp;6&nbsp;-&gt;&nbsp;8&nbsp;-&gt;&nbsp;9,小&nbsp;A&nbsp;和小&nbsp;B&nbsp;走的距离分别为&nbsp;5,1。<br>如果从城市&nbsp;7&nbsp;出发,则路线为&nbsp;7&nbsp;-&gt;&nbsp;9&nbsp;-&gt;&nbsp;10,小&nbsp;A&nbsp;和小&nbsp;B&nbsp;走的距离分别为&nbsp;2,1。<br>如果从城市&nbsp;8&nbsp;出发,则路线为&nbsp;8&nbsp;-&gt;&nbsp;10,小&nbsp;A&nbsp;和小&nbsp;B&nbsp;走的距离分别为&nbsp;2,0。<br>如果从城市&nbsp;9&nbsp;出发,则路线为&nbsp;9,小&nbsp;A&nbsp;和小&nbsp;B&nbsp;走的距离分别为&nbsp;0,0(旅行一开始就结束了)。<br>如果从城市&nbsp;10&nbsp;出发,则路线为&nbsp;10,小&nbsp;A&nbsp;和小&nbsp;B&nbsp;走的距离分别为&nbsp;0,0。<br>从城市&nbsp;2&nbsp;或者城市&nbsp;4&nbsp;出发小&nbsp;A&nbsp;行驶的路程总数与小&nbsp;B&nbsp;行驶的路程总数的比值都最小,<br>但是城市&nbsp;2&nbsp;的海拔更高,所以输出第一行为&nbsp;2。<br><br>【数据范围】<br>对于&nbsp;30%的数据,有&nbsp;1≤N≤20,1≤M≤20;<br>对于&nbsp;40%的数据,有&nbsp;1≤N≤100,1≤M≤100;<br>对于&nbsp;50%的数据,有&nbsp;1≤N≤100,1≤M≤1,000;<br>对于&nbsp;70%的数据,有&nbsp;1≤N≤1,000,1≤M≤10,000;<br>对于&nbsp;100%的数据,&nbsp;1≤N≤100,000,有1≤M≤10,000,<br>-1,000,000,000≤Hi≤1,000,000,000,0≤X0≤1,000,000,000,1≤Si≤N,0≤Xi≤1,000,000,000,数据保证&nbsp;Hi&nbsp;互不相同NOIP&nbsp;2012 
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
<tr><td>【输入样例 1】
4
2 3 4 1
3
4
1 3
2 3
3 3
4 3
【输入样例 2】
10
4 5 6 1 2 3 7 8 9 10
7
10
1 7
2 7
3 7
4 7
5 7
6 7
7 7
8 7
9 7
10 7
</td><td>【输出样例 1】
1 1
2 0
0 0
0 0

【输出样例 2】
2
3 2
2 4
2 1
2 4
5 1
5 1
2 1
2 0
0 0
0 0</td></tr></table>
