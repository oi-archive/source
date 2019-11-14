<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>辉辉热衷于洞穴勘测。某天，他按照地图来到了一片被标记为<span style="font-family: Calibri;">JSZX</span><span style="">的洞穴群地区。经过初步勘测，辉辉发现这片区域由</span><span style="font-family: Calibri;">n</span><span style="">个洞穴（分别编号为</span><span style="font-family: Calibri;">1</span><span style="">到</span><span style="font-family: Calibri;">n</span><span style="">）以及若干通道组成，并且每条通道连接了恰好两个洞穴。假如两个洞穴可以通过一条或者多条通道按一定顺序连接起来，那么这两个洞穴就是连通的，按顺序连接在一起的这些通道则被称之为这两个洞穴之间的一条路径。</span></p>
<p>洞穴都十分坚固无法破坏，然而通道不太稳定，时常因为外界影响而发生改变，比如，根据有关仪器的监测结果，<span style="font-family: Calibri;">123</span><span style="">号洞穴和</span><span style="font-family: Calibri;">127</span><span style="">号洞穴之间有时会出现一条通道，有时这条通道又会因为某种稀奇古怪的原因被毁。辉辉有一台监测仪器可以实时将通道的每一次改变状况在辉辉手边的终端机上显示：</span></p>
<p>如果监测到洞穴<span style="font-family: Calibri;">u</span><span style="">和洞穴</span><span style="font-family: Calibri;">v</span><span style="">之间出现了一条通道，终端机上会显示一条指令 </span><span style="font-family: Calibri;">Connect u v</span></p>
<p>如果监测到洞穴<span style="font-family: Calibri;">u</span><span style="">和洞穴</span><span style="font-family: Calibri;">v</span><span style="">之间的通道被毁，终端机上会显示一条指令 </span><span style="font-family: Calibri;">Destroy u v</span></p>
<p>经过长期的艰苦卓绝的手工推算，辉辉发现一个奇怪的现象：无论通道怎么改变，任意时刻任意两个洞穴之间至多只有一条路径。因而，辉辉坚信这是由于某种本质规律的支配导致的。因而，辉辉更加夜以继日地坚守在终端机之前，试图通过通道的改变情况来研究这条本质规律。</p>
<p>然而，终于有一天，辉辉在堆积成山的演算纸中崩溃了……他把终端机往地面一砸（终端机也足够坚固无法破坏），转而求助于你，说道：“你老兄把这程序写写吧”。</p>
<p>辉辉希望能随时通过终端机发出指令 <span style="font-family: Calibri;">Query u v</span><span style="">，向监测仪询问此时洞穴</span><span style="font-family: Calibri;">u</span><span style="">和洞穴</span><span style="font-family: Calibri;">v</span><span style="">是否连通。现在你要为他编写程序回答每一次询问。</span></p>
<p>已知在第一条指令显示之前，<span style="font-family: Calibri;">JSZX</span><span style="">洞穴群中没有任何通道存在。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个正整数<span style="font-family: Calibri;">n</span><span style="">和</span><span style="font-family: Calibri;">m</span><span style="">，分别表示洞穴的个数和终端机上出现过的指令的个数。</span></p>
<p>以下<span style="font-family: Calibri;">m</span><span style="">行，依次表示终端机上出现的各条指令。每行开头是一个表示指令种类的字符串</span><span style="font-family: Calibri;">s</span><span style="">（</span><span style="font-family: Calibri;">"Connect</span>”、”Destroy”或者”Query”，区分大小写），之后有两个整数<span style="font-family: Calibri;">u</span><span style="">和</span><span style="font-family: Calibri;">v (1</span>≤u, v≤n且u≠v) <span style="">分别表示两个洞穴的编号。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对每个<span style="font-family: Calibri;">Query</span><span style="font-family: 宋体;">指令，输出洞穴</span><span style="font-family: Calibri;">u</span><span style="font-family: 宋体;">和洞穴</span><span style="font-family: Calibri;">v</span><span style="font-family: 宋体;">是否互相连通：是输出</span>&rdquo;Yes&rdquo;，否则输出&rdquo;No&rdquo;。（不含双引号）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>200 5</p>
<p>Query 123 127</p>
<p>Connect 123 127</p>
<p>Query 123 127</p>
<p>Destroy 127 123</p>
<p>Query 123 127</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>No</p>
<p>Yes</p>
<p>No</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>10%<span style="">的数据满足</span><span style="font-family: Calibri;">n≤</span>1000, m≤20000</p>
<p>20%<span style="">的数据满足</span><span style="font-family: Calibri;">n≤</span>2000, m≤40000</p>
<p>30%<span style="">的数据满足</span><span style="font-family: Calibri;">n≤</span>3000, m≤60000</p>
<p>40%<span style="">的数据满足</span><span style="font-family: Calibri;">n≤</span>4000, m≤80000</p>
<p>50%<span style="">的数据满足</span><span style="font-family: Calibri;">n≤</span>5000, m≤100000</p>
<p>60%<span style="">的数据满足</span><span style="font-family: Calibri;">n≤</span>6000, m≤120000</p>
<p>70%<span style="">的数据满足</span><span style="font-family: Calibri;">n≤</span>7000, m≤140000</p>
<p>80%<span style="">的数据满足</span><span style="font-family: Calibri;">n≤</span>8000, m≤160000</p>
<p>90%<span style="">的数据满足</span><span style="font-family: Calibri;">n≤</span>9000, m≤180000</p>
<p>100%<span style="">的数据满足</span><span style="font-family: Calibri;">n≤</span>10000, m≤200000</p>
<p> </p>
<p>保证所有Destroy指令将摧毁的是一条存在的通道</p>
<p>本题输入、输出规模比较大，建议<span style="font-family: Calibri;">c\c++</span><span style="">选手使用</span><span style="font-family: Calibri;">scanf</span><span style="">和</span><span style="font-family: Calibri;">printf</span><span style="">进行</span><span style="font-family: Calibri;">I\O</span><span style="">操作以免超时</span></p>
</div>
</div>
</div>