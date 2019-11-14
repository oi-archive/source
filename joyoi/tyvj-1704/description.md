# 

 
 # 题目背景 
石家庄二中&nbsp;真理检验杯NOIP模拟赛&nbsp;第三题&nbsp;2011.8<BR> 

 
 # 题目描述 
在女神snowharmony的指引下，博客www.lydrainbowcat.tk中的宠物绿豆蛙Cat?Frog!来到了一片神奇的土地上，在这里它可以搜寻到很多很多的宝藏。<BR>绿豆蛙从起点出发,&nbsp;可能穿过一些有向道路到达另一些地点。绿豆蛙每次到达一处地点，它会挖掘到一些宝藏，或者付钱购买一些新的铲子（鉴于当地的土地异常地坚硬），这个过程一直持续下去，直到绿豆蛙到达终点。女神snowharmony将会计算绿豆蛙在寻宝过程中花的钱和挖到的宝藏，最终决定是否教给绿豆蛙一些新的技能。<BR>为了获得这些技能，绿豆蛙设法了解到了每个地点贮藏的宝藏价值Vi（若Vi为负数，则表示到该地必须付钱购买新铲子）以及道路的连接情况。没有道路到达的地点为起点，没有道路通向其他地方的地点为终点，起点和终点不止一个。绿豆蛙的任务是，选择一个起点，一个终点，和一条道路，使得最后获得最多的宝藏。<BR> 

 
 # 输入格式 
输入数据的第一行有两个整数n和m，代表地点数和道路数(1&nbsp;≤&nbsp;n&nbsp;≤&nbsp;100000,&nbsp;0&nbsp;≤&nbsp;m&nbsp;≤&nbsp;1000000)。&nbsp;<BR>接下来的n行每行一个整数，代表各个地点的宝藏价值（或必须付出的钱数）Vi&nbsp;，(0&nbsp;≤&nbsp;|Vi|&nbsp;≤&nbsp;20000)&nbsp;<BR>接下来的m行每行两个整数x，y，代表一条从x到y的有向道路。保证每条道路只出现一次，并且道路不形成环。&nbsp;<BR> 

 
 # 输出格式 
一个数，表示最多能获得的宝藏数。&nbsp; 

 
 # 提示 
由于压缩包过大、TYVJ服务器上传问题，实际数据中M最大为300000Poj3249 
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
<tr><td>6 5
1
2
2
3
3
4
1 2
1 3
2 4
3 4
5 6
</td><td>7</td></tr></table>
