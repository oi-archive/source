# 

 
 # 题目背景 
USACO&nbsp;OCT09&nbsp;6TH 

 
 # 题目描述 
Farmer&nbsp;John一直努力让他的草地充满鲜美多汁的而又健康的牧草。可惜天不从人愿，他在植物大战人类中败下阵来。邪恶的乳草已经在他的农场的西北部份佔领了一片立足之地。<BR><BR>草地像往常一样，被分割成一个高度為Y(1&nbsp;&lt;=&nbsp;y&nbsp;&lt;=&nbsp;100),&nbsp;宽度為X(1&nbsp;&lt;=&nbsp;x&nbsp;&lt;=&nbsp;100)的直角网格。(1,1)是左下角的格（也就是说坐标排布跟一般的X,Y坐标相同）。乳草一开始佔领了格(Mx,My)。每个星期，乳草传播到已被乳草佔领的格子四面八方的每一个没有很多石头的格（包括垂直与水平相邻的和对角线上相邻的格）。1周之后，这些新佔领的格又可以把乳草传播到更多的格裡面了。<BR><BR>Bessie想要在草地被乳草完全佔领之前尽可能的享用所有的牧草。她很好奇到底乳草要多久才能佔领整个草地。如果乳草在0时刻处於格(Mx,My)，那麼还在那个时刻它们可以完全佔领入侵整片草地呢（对给定的数据总是会发生）？<BR><BR>草地由一个图片表示。"."表示草，而"*"表示大石。比如这个X=4,&nbsp;Y=3的例子。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;....<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;..*.<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.**.<BR><BR>如果乳草一开始在左下角（第1排，第1列），那麼草地的地图将会以如下态势发展：<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;....&nbsp;&nbsp;....&nbsp;&nbsp;MMM.&nbsp;&nbsp;MMMM&nbsp;&nbsp;MMMM&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;..*.&nbsp;&nbsp;MM*.&nbsp;&nbsp;MM*.&nbsp;&nbsp;MM*M&nbsp;&nbsp;MM*M&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;M**.&nbsp;&nbsp;M**.&nbsp;&nbsp;M**.&nbsp;&nbsp;M**.&nbsp;&nbsp;M**M&nbsp;&nbsp;<BR>星期数&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4<BR><BR>乳草会在4星期后佔领整片土地。<BR> 

 
 # 输入格式 
*&nbsp;第一行:&nbsp;四个由空格隔开的整数:&nbsp;X,&nbsp;Y,&nbsp;Mx,&nbsp;My<BR><BR>*&nbsp;第2到第Y+1行:&nbsp;数据的第y+1行由X个字符（"."表示草地，"*"表示大石），描述草地的<BR>	第(Y+2-y)行。 

 
 # 输出格式 
*&nbsp;第一行:&nbsp;一个单独的整数表示最后一个不是大石块的格子被乳草佔领的星期数。 
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
<tr><td>4 3 1 1
....
..*.
.**.
</td><td>4
</td></tr></table>
