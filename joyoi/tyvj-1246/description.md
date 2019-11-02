# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;乌龟非常热爱跳格子，尤其是写有数字的格子。他发明了一种新型的跳格子游戏。<BR><img src="/source/joyoi/tyvj-1246/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI0Ni9odHRwOi8vd3d3LnR5dmouY246ODA4MC9wcm9ibGVtaW1nLzMuYm1w.bmp" border=0 align=middle><BR><BR>在一列格子中（共N个格子），每个格子上都写着分数Di，乌龟要从第一个格子开始跳，跳到最后一个格子上。（第一个格子的分数不能得到，因为乌龟没有跳到第一个格子上）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;乌龟一次最多跳P格，最少跳1格。乌龟跳T格，跳到第x个格子上时，跳跃的得分是T*Dx。<BR>&nbsp;&nbsp;&nbsp;&nbsp;总得分等于各次跳跃得分之和。<BR>&nbsp;&nbsp;&nbsp;&nbsp;为了让游戏更有趣味，乌龟希望总得分除以M的余数最大。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入的第一行有三个正整数N，P，M。空格隔开。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来N行，每行1个数，为每个格子的分数Di（非负整数）。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出仅包含一个数字，为总得分除以M的余数的最大值。 

 
 # 提示 
对于10%的数据，P≤1。<BR>对于40%的数据，2≤N≤5，1＜P≤2。<BR>对于100%的数据，P≤10≤N≤100，M≤10000。<BR>EZ_lzh。第一次举办比赛，出得不好或有错，请多包涵。 
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
<tr><td>5 2 12
5
4
6
7
1
</td><td>8
</td></tr></table>
