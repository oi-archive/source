# 

 
 # 题目描述 
夷陵之战打响，陆逊奉命抵抗刘备的进攻。陆逊认为:取得这场战争胜利的关键就是拥有足够的情报!(T_T)<BR>陆逊手下有若干个情报站，每个情报站里有若干个情报小队，情报站内部每两个小队之间可能存在多条情报通道，每条通道传递情报具有一定的时间，各情报站之间不许互传情报。陆逊在每个情报站的两个不同小队里分别安排情报员，然后在每个情报站里选取一个小队作为对外情报传递出口，让这两名情报员通过这里向外传递情报，为保证信息通畅，要求两条情报总传递时间最小，但不允许情报经过同一个小队（对外出口小队除外）。&nbsp;<BR>所有情报外传出口确定后，陆逊会派出一名武官与最多k个情报出口建立传信通道，并使这个武官作为一个新的传信出口取代之前他所联接的传信出口，如此不断增加武官，直到只有一个可接受所有信息的总传信出口，直接受陆逊指挥(最后一个武官到陆逊不花费时间)。所有武官建立的传信通道传信时间都是相同的，为q。<BR>要求输出当所有情报员发出情报后，最短多长时间陆逊可以收到所有信息。 

 
 # 输入格式 
第一行三个整数N，q，k，表示共有N个情报站，武官建立的传信通道传信时间q，武官与最多k个情报出口建立传信通道。<BR>下面有N个部分，描述了N个情报站的情况。<BR>对于每一部分：<BR>第一行有m，x，a，b。表示共有m个情报小队，每个情报小队编号为1~m，有x条传信通道，情报员位于第a和第b小队。接下来x行，每行分别是整数u，v，t。表示情报小队u，v之间存在一条传信通道，传信时间为t。 

 
 # 输出格式 
输出共N+1行。前N行表示每个情报站中对外传信出口所在小队的序号。(如果有多个，输出序号最小的一个)<BR>最后一行，输出一个整数T，表示陆逊得到所有情报的最短时间。 

 
 # 提示 
数据保证每个情报站的连通性。<BR>100%数据N≤100，2≤k≤10，1≤q≤100。对于所有小分队，m≤100，2≤x≤5000，1≤t≤100。<BR><BR>样例解释：<BR>两个情报站的传信通道皆为：<BR>(1)-------------------(3)<BR>&nbsp;\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/<BR>&nbsp;&nbsp;&nbsp;\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;/<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\&nbsp;&nbsp;&nbsp;/<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2]<BR>都取2号小队为传递出口，并且1小队、3小队到2小队的最短时间为2。<BR>然后设置一个武官，分别与之建立连接，其连接线路的通讯时间为2<BR>则总的最短时间为4。(最后若干名直接与陆逊相连的武官或传递出口不消耗时间)连云港模拟赛&nbsp;29日上午&nbsp;第2题 
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
<tr><td>2 2 2
3 3 1 3
1 2 2
1 3 5
2 3 1
3 3 1 3
1 2 2
1 3 5
2 3 1</td><td>2
2
4</td></tr></table>
