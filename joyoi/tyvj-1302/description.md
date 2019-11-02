# 

 
 # 题目背景 
Taston是Guiolk联盟派到Summer联盟刺探消息的间谍，虽然Guiolk联盟已经覆灭了，他无法汇报刺探到的消息，但是Taston仍然不忘记他的使命，于是他就尽可能地搞破坏。<BR>在Summer冲击Winter联盟前线的同时，Taston接到了Summer上级的命令。他不能违抗命令，否则会暴露身份，但是他可以让Summer联盟浪费战斗力。<BR> 

 
 # 题目描述 
Taston接到的命令是：切断Winter联盟从S星球到T星球的运输航线。<BR>Taston侦查后发现，Winter联盟在S星球和T星球附近控制了N个星球（包括S星球、T星球），星球编号从1到N。共有M条从一个星球到另一个星球的航线。Taston要控制一条航线，需要派出相应多的战舰C[i,j]。<BR>Taston将派出一些战舰占领一定的航线，使得Winter联盟无法把物资从S星球运输T星球，即Winter联盟把物资要从S星球运输T星球，必须经过被Summer联盟占领的航线。<BR>Taston可以控制Summer联盟的P架战舰，他想把这些战舰全部派出去占领航线，来浪费Summer联盟的战斗力。<BR>Taston制作的侦查地图上显示了占领每条航线需要派出的战舰数量C[i,j]。Taston需要向上级汇报侦查地图，为了不被上级怀疑，Taston要派出最少战舰来完成任务。但是侦查地图是Taston制作的，&nbsp;Taston可以在汇报前随心所欲地将侦查地图上显示的占领每条航线需要派出的战舰数量C[i,j]改为G[i,j]<BR>Taston要在手上P架战舰全部派出去并不被怀疑的情况下，修改侦查地图（Taston不喜欢减少，所以只能增加每条航线需要派出的战舰数量），但是修改地图很麻烦，Taston希望所有修改了的航线G[i,j]-C[i,j]的和最小。<BR> 

 
 # 输入格式 
第一行两个正整数N、M，分别表示星球个数和航线数量。<BR>第二行三个数非负整数S、T、P，表示要切断从S星球到T星球的运输航线，Taston手上有P架战舰。<BR>接下来有M行，每行三个数A、B、C[a,b]，表示从A星球到B星球的航线，原本需要C[a,b]架战舰占领。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;如果无需派出战舰便能完成任务，输出“0&nbsp;Warship.”。<BR>如果用P架战舰不能完成任务或者原侦查地图最少就要派出P架战舰，输出“Taston&nbsp;is&nbsp;angry!”。<BR>如果可以完成输出“X&nbsp;Warship(s).”，修改后的侦查地图最少需要的战舰数量正好是P架时，所有航线|G[i,j]-C[i,j]|和的最小值。<BR> 

 
 # 提示 
<img src="/source/joyoi/tyvj-1302/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTMwMi9odHRwOi8vdHl2ai5jcHd6LmNuL1Byb2JsZW1JbWcvUDEzMDItMS5ibXA=.bmp" border=0 align=middle><BR><img src="/source/joyoi/tyvj-1302/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTMwMi9odHRwOi8vdHl2ai5jcHd6LmNuL1Byb2JsZW1JbWcvcDEzMDItMi5ibXA=.bmp" border=0 align=middle><BR>(这是其中的一种情况)<BR>1≤N≤100，1≤M≤500，1≤S、T≤N，0≤P≤10^7。1≤A、B≤N，1≤C[a,b]≤10^4。<BR>其中对于40%的数据1≤N≤10。<BR>两个星球之间不一定只有一条航道。<BR>From&nbsp;EZ_gx/EZ_lzh 
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
<tr><td>5 4
1 5 1000
1 2 10
2 5 10
2 3 10
3 5 1000
</td><td>1970 Warship(s).
</td></tr></table>
