# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;在唐山一中，吃饭是一件很令人头疼的事情，因为你不可能每次都站在队伍前面买饭，所以，你最需要做的一件事就是——跑饭。而跑饭的道路是无比艰难的，因为路是单向的（你要非说成是双向的我也没法，前提是你可以逆着2000+个狂热的跑饭群众而行），所以要合理选择路线。并且，在抵达你的目的地——板面馆之前，你需要先买一些干粮，比如烧饼之类的。现在给你每个干食商店的位置和干食喜爱度，请你设计一个跑饭方案使得在到达板面馆之前能得到尽可能多的干食喜爱度。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行包含两个整数N、M。N表示食品商店的个数，M表示道路条数。接下来M行，每行两个整数，这两个整数都在1到N之间，第i+1行的两个整数表示第i条道&nbsp;路的起点和终点的食品商店编号。接下来N行，每行一个整数，按顺序表示每个食品商店处的干食喜爱度。接下来一行包含两个整数S、P，S表示学校的编号，也就是出发地点。P表示板面馆数目。接下来的一行中有P个整数，表示P个卖板面的食品商店的编号。 

 
 # 输出格式 
输出一个整数，表示到达板面馆之前能得到的最多的干食喜爱度。 

 
 # 提示 
40%的数据n,m&lt;=300&nbsp;&nbsp;&nbsp;100%的数据n,m&lt;=3000&nbsp;<BR><BR><BR>鸣谢：感谢www.tyvj.cn提供比赛平台<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;感谢唐山一中和保定二中老师给予的大力支持<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;感谢SRC、Cannot、Yuan0818、Oldway提供的题目<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;感谢广大OIer的参与 
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
<tr><td>6 7
1 2
2 3
3 5
2 4
4 1
2 6
6 5
10
12
8
16
1
5
1 4
4 3 5 6
</td><td>47</td></tr></table>
