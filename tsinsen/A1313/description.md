<div id="pcont1" style="margin-top:20px; display:block;">
<div class="pdcont">　　大意：<br/>
　　给你一个无向带权连通图，每条边是黑色或白色。让你求一棵最小权的恰好有need条白色边的生成树。<br/>
　　题目保证有解。</div>
# 输入格式

<div class="pdcont">　　第一行V,E,need分别表示点数，边数和需要的白色边数。<br/>
　　接下来E行<br/>
　　每行s,t,c,col表示这边的端点(点从0开始标号)，边权，颜色(0白色1黑色)。</div>
# 输出格式

<div class="pdcont">　　一行表示所求生成树的边权和。</div>
# 数据规模和约定

<div class="pdcont">　　0:V&lt;=10<br/>
　　1,2,3:V&lt;=15<br/>
　　0,..,19:V&lt;=50000,E&lt;=100000<br/>
　　所有数据边权为[1,100]中的正整数。</div>
# 样例输入

<div class="pddata">2 2 1<br/>
0 1 1 1<br/>
0 1 2 0</div>
# 样例输出

<div class="pddata">2</div>

</div>