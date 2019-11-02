# 

 
 # 题目描述 
小W是一片新造公墓的管理人。公墓可以看成一块N×M的矩形，矩形的每个格点，要么<BR>种着一棵常青树，要么是一块还没有归属的墓地。<BR>当地的居民都是非常虔诚的基督徒，他们愿意提前为自己找一块合适墓地。为了体现自<BR>己对主的真诚，他们希望自己的墓地拥有着较高的虔诚度。<BR>一块墓地的虔诚度是指以这块墓地为中心的十字架的数目。一个十字架可以看成中间是<BR>墓地，墓地的正上、正下、正左、正右都有恰好k棵常青树。<BR>小W希望知道他所管理的这片公墓中所有墓地的虔诚度总和是多少。<BR> 

 
 # 输入格式 
输入文件religious.in的第一行包含两个用空格分隔的正整数N和M，表示公墓的宽和长，<BR>因此这个矩形公墓共有(N+1)&nbsp;×(M+1)个格点，左下角的坐标为(0,&nbsp;0)，右上角的坐标为(N,&nbsp;M)。<BR>第二行包含一个正整数W，表示公墓中常青树的个数。<BR>第三行起共W行，每行包含两个用空格分隔的非负整数xi和yi，表示一棵常青树的坐标。<BR>输入保证没有两棵常青树拥有相同的坐标。<BR>最后一行包含一个正整数k，意义如题目所示。<BR> 

 
 # 输出格式 
输出文件religious.out仅包含一个非负整数，表示这片公墓中所有墓地的虔诚度总和。为<BR>了方便起见，答案对2,147,483,648取模。<BR> 

 
 # 提示 
[样例说明]<BR><img src="/source/joyoi/tyvj-1169/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTE2OS9Qcm9ibGVtSW1nXDExNjktMS5qcGc=.jpg" border=0 align=middle><BR>图中，以墓地(2,&nbsp;2)和(2,&nbsp;3)为中心的十字架各有3个，即它们的虔诚度均为3。其他墓地<BR>的虔诚度为0。<BR><BR>[数据规模和约定]<BR>对于30%的数据，满足1&nbsp;≤&nbsp;N,&nbsp;M&nbsp;≤&nbsp;1,000。<BR>对于60%的数据，满足1&nbsp;≤&nbsp;N,&nbsp;M&nbsp;≤&nbsp;1,000,000。<BR>对于100%的数据，满足1&nbsp;≤&nbsp;N,&nbsp;M&nbsp;≤&nbsp;1,000,000,000，0&nbsp;≤&nbsp;xi&nbsp;≤&nbsp;N，0&nbsp;≤&nbsp;yi&nbsp;≤&nbsp;M，1&nbsp;≤&nbsp;W&nbsp;≤&nbsp;100,000，<BR>1&nbsp;≤&nbsp;k&nbsp;≤&nbsp;10。<BR>存在50%的数据，满足1&nbsp;≤&nbsp;k&nbsp;≤&nbsp;2。<BR>存在25%的数据，满足1&nbsp;≤&nbsp;W&nbsp;≤&nbsp;10000。<BR> 
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
<tr><td>5 6
13
0 2
0 3
1 2
1 3
2 0
2 1
2 4
2 5
2 6
3 2
3 3
4 3
5 2
2
</td><td>6
</td></tr></table>
