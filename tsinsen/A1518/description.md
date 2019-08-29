<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　cxm最近在玩一个叫做猴子挖矿的游戏。<br/>
　　这个游戏由两个玩家参加。开始时地图中会随机生成一些矿点，玩家需要操作自己的猴子探索未知的道路，抢占对方的矿点。已经占领的矿点每回合会产生1单位的矿石。玩家用手中的矿石可以购买路灯、护盾、传送等道具。最终获得矿石较多的玩家获胜。<br/>
　　cxm对这个游戏进行了一些改动。现在游戏在一个有n个点，m条边的有向图上进行，为了方便起见，cxm用1到n的整数来表示地图中的点。<br/>
　　玩家只有一个，但他拥有无限数量的猴子。游戏最开始时，所有的猴子都在第1个点。每一回合，所有的猴子必须沿着图中的一条有向边移动到下一个点。玩家可以给不同的猴子指定不同的路线，但不能让猴子呆在原地不动。无路可走的猴子会在下一回合消失。<br/>
　　游戏开始时为第0回合。从第S回合开始，到第T回合结束（包括第S回合和T回合），每回合每个点都会出产1单位的矿石。如果在该回合玩家有至少一只猴子在出产矿石的点，那么玩家将获得这个矿石，否则这个矿石会在下一回合消失。<br/>
　　现在cxm想知道，在图中的每个点他分别最多可以获得多少个矿石。</div>
# 输入格式

<div class="pdcont">　　标准输入。输入第一行包含四个正整数n,m,S,T，分别表示有向图中点的个数，边的个数，开始出产的时间和结束出产的时间。<br/>
　　接下来m行，每行包含2个1到n的整数x,y，用空格隔开，表示有一条从第x个点到第y个点的有向边。</div>
# 输出格式

<div class="pdcont">　　标准输出。输出n行，每行包含一个整数，按照1到n的顺序依次表示在每个点可以获得的矿石个数。</div>
# 样例输入

<div class="pddata">5 7 0 19<br/>
1 3<br/>
1 4<br/>
1 5<br/>
3 2<br/>
2 1<br/>
3 4<br/>
5 5</div>
# 样例输出

<div class="pddata">7<br/>
6<br/>
7<br/>
13<br/>
19</div>
# 样例说明

<div class="pdcont">　　样例的有向图如图所示：<br/>
<img src="source/tsinsen/A1518/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9bmpyZU5uRTQ=.do" width="264" height="251"/><br/>
　　1→3→2有一个长度为3的环，可以让一大群猴子在该环上运动，每隔3回合可以回到1一次。猴群在相应的时间可以获得1、2、3三个点的矿石。每当猴群到达1时，用两只猴子分别沿1→4和1→3→4两条路径前往4，可以获得4相邻两个回合的矿石。<br/>
　　第1回合令1只猴子到5之后一直沿5→5停留在5，可以获得从第1回合起在5的所有矿石。<br/>
　　每个点可以获得矿石的回合如下：<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr valign="top" style="border:solid 1.0pt"><td style="border:solid 1.0pt"><br/>
</td><td style="border:solid 1.0pt">0<br/>
</td><td style="border:solid 1.0pt">1<br/>
</td><td style="border:solid 1.0pt">2<br/>
</td><td style="border:solid 1.0pt">3<br/>
</td><td style="border:solid 1.0pt">4<br/>
</td><td style="border:solid 1.0pt">5<br/>
</td><td style="border:solid 1.0pt">6<br/>
</td><td style="border:solid 1.0pt">7<br/>
</td><td style="border:solid 1.0pt">8<br/>
</td><td style="border:solid 1.0pt">9<br/>
</td><td style="border:solid 1.0pt">10<br/>
</td><td style="border:solid 1.0pt">11<br/>
</td><td style="border:solid 1.0pt">12<br/>
</td><td style="border:solid 1.0pt">13<br/>
</td><td style="border:solid 1.0pt">14<br/>
</td><td style="border:solid 1.0pt">15<br/>
</td><td style="border:solid 1.0pt">16<br/>
</td><td style="border:solid 1.0pt">17<br/>
</td><td style="border:solid 1.0pt">18<br/>
</td><td style="border:solid 1.0pt">19<br/>
</td></tr><tr valign="top" style="border:solid 1.0pt"><td style="border:solid 1.0pt">1<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td></tr><tr valign="top" style="border:solid 1.0pt"><td style="border:solid 1.0pt">2<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td></tr><tr valign="top" style="border:solid 1.0pt"><td style="border:solid 1.0pt">3<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td></tr><tr valign="top" style="border:solid 1.0pt"><td style="border:solid 1.0pt">4<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td></tr><tr valign="top" style="border:solid 1.0pt"><td style="border:solid 1.0pt">5<br/>
</td><td style="border:solid 1.0pt">×<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td><td style="border:solid 1.0pt">○<br/>
</td></tr></tbody></table></div>
# 数据规模和约定

<div class="pdcont">　　对于10%的数据，保证对于任意两个不同的点x和y，如果存在一条路径从x到达y，则不存在路径从y到达x。<br/>
　　另有40%的数据，保证S≥9×10<sup>14</sup>。其中，有占全部数据20%的数据保证T-S≤50000。<br/>
　　对于100%的数据，保证0&lt;n≤100，0&lt;m≤300，0≤S≤T≤10<sup>15</sup>。</div>

</div>