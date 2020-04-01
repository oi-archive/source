
# Description

<div class="content"><div align="center"></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">开辟新航路以后，欧洲的海上贸易日益繁荣，许多商人带领着他们的船队，在世界各地来往穿梭。这其中有位很有头脑的</span><span style="font-size: 12pt">XX</span><span style="font-size: 12pt">船长，他十分重视收集各港口的供需情报，并以此确定他的下一步计划，通过减少运输的时间来获取更多的利益。他的情报包括以下的内容：</span></div>
<div style="text-justify: inter-ideograph; text-indent: 1cm; line-height: 20pt; text-align: justify"><span style="font-size: 12pt">1．<span style="font: 7pt &#39;Times New Roman&#39;">           </span></span><span style="font-size: 12pt">一幅完整的航海图。这其中包含了陆地、海洋以及各港口的位置。船只每次只能沿上下左右四个方向移动一格</span><span style="font-size: 12pt">(</span><span style="font-size: 12pt">不可移到陆地上和地图外</span><span style="font-size: 12pt">,</span><span style="font-size: 12pt">可移进港口</span><span style="font-size: 12pt">)</span><span style="font-size: 12pt">，且每次移动都需航行一天。</span></div>
<div style="text-justify: inter-ideograph; text-indent: 1cm; line-height: 20pt; text-align: justify"><span style="font-size: 12pt">2．<span style="font: 7pt &#39;Times New Roman&#39;">           </span></span><span style="font-size: 12pt">各港口可供应的货物。当然，每种货物不可能到处都买的到，否则就用不着船队了。因此，规定每种货物最多只有</span><span style="font-size: 12pt">20</span><span style="font-size: 12pt">个的港口供应。</span></div>
<div style="text-justify: inter-ideograph; text-indent: 1cm; line-height: 20pt; text-align: justify"><span style="font-size: 12pt">3．<span style="font: 7pt &#39;Times New Roman&#39;">           </span></span><span style="font-size: 12pt">各港口需要的货物。与情报</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">不同的是，各港所需的货物是变化的，即</span><span style="font-size: 12pt">XX</span><span style="font-size: 12pt">船长是逐渐得到新情报的。同时，每当他得到一个新的货物需求</span><span style="font-size: 12pt">(i,j)(</span><span style="font-size: 12pt">表示港口</span><span style="font-size: 12pt">j</span><span style="font-size: 12pt">需要货物</span><span style="font-size: 12pt">i)</span><span style="font-size: 12pt">，他必须马上作出决策：选择几号船完成此任务。因为要计算出怎样最优是比较困难的，所以船长采取了这样一个近似的方法：找出“完成新任务所需时间”最少的船，将其用来完成新任务，若有多艘这样的船，则从中选择编号最小的。</span><span style="font-size: 12pt">(</span><span style="font-size: 12pt">“完成新任务所需时间”包含两个过程：航行到一个供应货物</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">的港口并上货和将货物</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">运到港口</span><span style="font-size: 12pt">j</span><span style="font-size: 12pt">并卸货，其中上货和卸货的时间忽略不计。因为上货港口的选择不同，所需的时间也会不同，所以，必须对上货的港口进行选择，使该船的“完成新任务所需时间”尽量短</span><span style="font-size: 12pt">)</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">XX</span><span style="font-size: 12pt">船长想要知道的是：他的所有船只共需多少时间来完成这些任务，即所有船只完成各自任务的时间和。</span></div>
<div style="line-height: 20pt"><b> </b></div></div>

# Input

<div class="content"><div style="line-height: 20pt"><span style="font-size: 12pt">    </span><span style="font-size: 12pt">第一行是是六个数</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">M</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">port_num</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">good_num</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">ship_num</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">start</span><span style="font-size: 12pt">，表示航海图的长、宽，以及港口总数、货物种类和船长拥有的船只数、所有船的初始位置</span><span style="font-size: 12pt">(</span><span style="font-size: 12pt">停泊的港口编号</span><span style="font-size: 12pt">)</span><span style="font-size: 12pt">。</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">    </span><span style="font-size: 12pt">以下</span><span style="font-size: 12pt">N+1</span><span style="font-size: 12pt">行是一个</span><span style="font-size: 12pt">N×M</span><span style="font-size: 12pt">的矩阵，在矩阵中</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">分别对应海洋、港口和陆地。港口的编号对应由上至下，由左至右</span><span style="font-size: 12pt">(</span><span style="font-size: 12pt">由上至下优先</span><span style="font-size: 12pt">)</span><span style="font-size: 12pt">的读入顺序，第一个读入的港口编号为</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">，第二个读入的港口编号为</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">……</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">    </span><span style="font-size: 12pt">第</span><span style="font-size: 12pt">N+2</span><span style="font-size: 12pt">行到第</span><span style="font-size: 12pt">N+port_num+1</span><span style="font-size: 12pt">行按编号顺序给出了各港口供应的货物，其格式为：</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">       N1 p11  p12  … p1N1</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">       N2 p21  p22  … p2N2</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">       … … … … …</span></div>
<div style="text-indent: 21.25pt; line-height: 20pt"><span style="font-size: 12pt">   Ni pi1  pi2  … piNi</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">       … … … … …</span></div>
<div style="text-indent: 21.25pt; line-height: 20pt"><span style="font-size: 12pt"> Nport_num pport_num1 pport_num2 … pport_numNport_num</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">       Ni</span><span style="font-size: 12pt">是港口</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">供应的货物总数，</span><span style="font-size: 12pt">pij</span><span style="font-size: 12pt">是港口</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">供应的第</span><span style="font-size: 12pt">j</span><span style="font-size: 12pt">种货物编号。</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">     </span><span style="font-size: 12pt">第</span><span style="font-size: 12pt">N+port_num+2</span><span style="font-size: 12pt">行是一个数</span><span style="font-size: 12pt">Total</span><span style="font-size: 12pt">，表示情报</span><span style="font-size: 12pt">3</span><span style="font-size: 12pt">中获得的任务总数，以下</span><span style="font-size: 12pt">Total</span><span style="font-size: 12pt">行按情报获得的时间给出了</span><span style="font-size: 12pt">Total</span><span style="font-size: 12pt">个任务，每个任务占一行，包含两个数</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">j</span><span style="font-size: 12pt">，表示港口</span><span style="font-size: 12pt">j</span><span style="font-size: 12pt">需要货物</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">。</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">文件一行中相临两数用一个或多个空格隔开。</span></div>
<div style="line-height: 15pt"><b> </b></div></div>

# Output

<div class="content"><div style="line-height: 20pt"><span style="font-size: 12pt"> </span><span style="font-size: 12pt">仅有一个数</span><span style="font-size: 12pt">T</span><span style="font-size: 12pt">，是你的程序得出的所有船只完成各自任务的时间和。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 3 4 2 1<br/>
0 1 0 0 0<br/>
2 2 2 0 0<br/>
0 1 2 0 2<br/>
0 2 2 0 1<br/>
0 0 0 0 0<br/>
1 3<br/>
3 1 2 4<br/>
1 4<br/>
4<br/>
1 3<br/>
2 3<br/>
3 2<br/>
4 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">54<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据范围<br/><br/>
       1≤N、M≤100，1≤port_num≤100,1≤good_num</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

