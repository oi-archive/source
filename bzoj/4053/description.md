
# Description

<div class="content"><div>小J要坐地铁到小M家去玩。有很多的地铁站，有很多条双向的地铁线路连接它们。从一个站到一个直接相邻的站都只要1min，换线不需要时间。给你地铁图，你的任务是帮助小J安排他的路线，使得换乘（在一条线路上回头也算换乘）次数尽量少，且让他坐的尽量久。</div></div>

# Input

<div class="content"><p>第一行包含一个数T，代表数据组数</p>
<div>每一组测试数据如下:</div>
<div>每组数据用一个回车开头，接下来的两行以“Stops:”和”Lines:”(不包含引号)开头，并且分别包含站点和线路的名称，之间用一个逗号和一个空格隔开。接下来对于每条线路有单独的一行，以线路的名称+” route:”开头，后面包含它经过的站点，之间用一个逗号和一个空格隔开。最后两行告诉你小J与小M的位置。<span class="Apple-tab-span" style="white-space: pre;">	</span></div></div>

# Output

<div class="content"><p> 对于每组测试数据，打印单独的一行代表小J的最优线路（详情请见样例数据），保证最优路径存在。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
<br/>
Stops: OxfordCircus, PiccadillyCircus, HydeParkCorner, King’sCross, GreenPark, Arsenal, Victoria, Highbury&amp;Islington, LeicesterSquare<br/>
Lines: Blue, Cyan<br/>
Cyan route: Highbury&amp;Islington, King’sCross, OxfordCircus, GreenPark, Victoria<br/>
Blue route: HydeParkCorner, GreenPark, PiccadillyCircus, LeicesterSquare, King’sCross, Arsenal<br/>
Johny lives at King’sCross<br/>
Michelle lives at GreenPark<br/>
<br/>
Stops: OxfordCircus, PiccadillyCircus, HydeParkCorner, King’sCross, GreenPark, Arsenal, Victoria, Highbury&amp;Islington, LeicesterSquare<br/>
Lines: Blue, Cyan<br/>
Cyan route: Highbury&amp;Islington, King’sCross, OxfordCircus, GreenPark, Victoria<br/>
Blue route: HydeParkCorner, GreenPark, PiccadillyCircus, LeicesterSquare, King’sCross, Arsenal<br/>
Johny lives at PiccadillyCircus<br/>
Michelle lives at LeicesterSquare<br/>
<br/>
Stops: OxfordCircus, PiccadillyCircus, HydeParkCorner, King’sCross, GreenPark, Arsenal, Victoria, Highbury&amp;Islington, LeicesterSquare<br/>
Lines: Blue, Cyan<br/>
Cyan route: Highbury&amp;Islington, King’sCross, OxfordCircus, GreenPark, Victoria<br/>
Blue route: HydeParkCorner, GreenPark, PiccadillyCircus, LeicesterSquare, King’sCross, Arsenal<br/>
Johny lives at Victoria<br/>
Michelle lives at HydeParkCorner</span></div>

# Sample Output

<div class="content"><span class="sampledata">optimal travel from King’sCross to GreenPark: 1 line, 3 minutes<br/>
optimal travel from PiccadillyCircus to LeicesterSquare: 1 line, 1 minute<br/>
optimal travel from Victoria to HydeParkCorner: 2 lines, 7 minutes</span></div>

# Hint

<div class="content"><p></p><p> 站点数&lt;=300000    线路数&lt;=100000   线路总长度&lt;=1000000   名称长度&lt;=50  名称可以包括字母、数字、减号(-)、单引号(&#39;)、and标志(&amp;)，保证没有自环。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

