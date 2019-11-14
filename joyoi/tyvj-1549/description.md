# 

 
 # 题目描述 
猪仙最恨几何题……于是魂之挽歌给他弄了一堆几何题做……<BR>猪仙做每道题都需要一定的时间t[i]，如果他开始做某题，那么一定会把它做完<BR>如果猪仙没有做某题的话，魂之挽歌会藐视他，藐视度为x[i]<BR>为了更多的藐视猪仙，魂之挽歌不会把所有的时间都让猪仙去做题的，所以每道题魂之挽歌会在a[i]时刻发给猪仙，也就是说a[i]时刻之前主线不能做第i道题。<BR>猪仙一共有T的时间，他希望总藐视度最小。 

 
 # 输入格式 
&nbsp;第一行两个正整数T，N(T&lt;=10000,N&lt;=100)。<BR>&nbsp;接下来有n行，每行三个数a[i],t[i],x[i]<BR>a[i]&lt;=T,t[i]&lt;=T,x[i]&lt;=2000<BR><BR> 

 
 # 输出格式 
&nbsp;仅一个正整数，表示最小藐视度。<BR> 
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
<tr><td>5 3
1 1 2
1 3 5
4 1 3</td><td>0</td></tr></table>
