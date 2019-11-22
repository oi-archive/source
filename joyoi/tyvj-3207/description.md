# 

 
 # 题目描述 
<p>
航空路线问题(airl.cpp/c/pas)<br><br>【问题描述】<br><br>　　给定一张航空图，图中顶点代表城市，边代表2城市间的直通航线。现要求找出一条满足下述限制条件的且途经城市最多的旅行路线。<br>　　(1)从最西端城市出发，单向从西向东途经若干城市到达最东端城市，然后再单向从东向西飞回起点(可途经若干城市)。<br>　　(2)除起点城市外，任何城市只能访问1次。<br><br>【编程任务】<br><br>　　对于给定的航空图，试设计一个算法找出一条满足要求的最佳航空旅行路线。</p> 

 
 # 输入格式 
<p>
由文件airl.in提供输入数据。<br>　　文件第1 行有2个正整数N 和V，N 表示城市数，N <100，V 表示直飞航线数。接下来的N行中每一行是一个城市名，可乘飞机访问这些城市。城市名出现的顺序是从西向东。也就是说，设i,j 是城市表列中城市出现的顺序，当i > j 时，表示城市i 在城市j 的东边，而且不会有2 个城市在同一条经线上。城市名是一个长度不超过15 的字符串，串中的字符可以是字母或阿拉伯数字。例如，AGR34或BEL4。<br>　　再接下来的V 行中，每行有2 个城市名，中间用空格隔开，如 city1 city2 表示city1到city2 有一条直通航线，从city2 到city1 也有一条直通航线。</p> 

 
 # 输出格式 
<p>
程序运行结束时，将最佳航空旅行路线输出到文件airl.out 中。<br>　　文件第1 行是旅行路线中所访问的城市总数M。接下来的M＋1 行是旅行路线的城市名，每行写1 个城市名。首先是出发城市名，然后按访问顺序列出其它城市名。注意，最后1行（终点城市）的城市名必然是出发城市名。如果问题无解，则输出“No Solution!”。</p> 
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
<tr><td>8 9
Vancouver
Yellowknife
Edmonton
Calgary
Winnipeg
Toronto
Montreal
Halifax
Vancouver Edmonton
Vancouver Calgary
Calgary Winnipeg
Winnipeg Toronto
Toronto Halifax
Montreal Halifax
Edmonton Montreal
Edmonton Yellowknife
Edmonton Calgary</td><td>7
Vancouver
Edmonton
Montreal
Halifax
Toronto
Winnipeg
Calgary
Vancouver</td></tr></table>
