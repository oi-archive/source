<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　利用空闲时间，BX希望外出工作，工作开始之前，公司就会给BX一个评估值<i>X<sub>0</sub></i>，之后每天BX的评估值都是根据上一天的评估值和当天公司的运行状况得出，即<i>X<sub>i</sub></i>=<i>X<sub>i-1</sub></i>+<i>D<sub>i</sub></i>,但是每天的评估值有一个上限，也就是说完整的评估公式因该是<i>X</i><sub>i</sub>=min{<i>X<sub>i-1</sub></i>+<i>D<sub>i</sub></i>,<i>L<sub>i</sub></i>}。<br/>
　　现在BX已经知道了该公司对自己的初始评估值<i>X<sub>0</sub></i>、公司每天的运行状况<i>Di</i>、每天的评估上限<i>Li</i>，他的空闲时间是从第<i>A</i>天到第<i>B</i>天，他希望找到一段时间<i>i</i>，<i>j</i> (<i>A</i>≤<i>i</i>≤<i>j</i>≤<i>B</i>)，使得从第<i>i</i>天开始工作，到第<i>j</i>天结束后的评估值最大。当然如果任意一段时间的工作得到评估值都&lt;初始评估值<i>X<sub>0</sub></i>，BX可以选择不工作，从而得到最大的评估值。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含两个整数<i>N</i><i>、M</i>，分别表示总共工作天数和询问数。<br/>
　　第二行<i>N</i>个数，表示<i>D<sub>i</sub></i>。<br/>
　　第三行<i>N</i>个数，表示<i>L<sub>i</sub></i>。<br/>
　　以下<i>M</i>行，每行3个数<i>A</i>、<i>B</i>、<i>X<sub>0</sub></i>，表示一次询问。</div>
# 输出格式

<div class="pdcont">　　M行，每行输出一个整数，表示评估的最大值</div>
# 样例输入

<div class="pddata">6 3<br/>
-6 5 3 2 -3 4<br/>
8 10 8 1 9 9<br/>
1 3 9<br/>
2 6 3<br/>
3 4 0</div>
# 样例输出

<div class="pddata">10<br/>
8<br/>
3</div>
# 数据规模和约定

<div class="pdcont">　　对于30%数据，满足<i>N</i>,<i>M</i>&lt;101<br/>
　　对于60%数据，满足<i>N</i>,<i>M</i>&lt;10001<br/>
　　对于100%数据,满足<i>N</i>,<i>M</i>&lt;50001,|<i>D<sub>i</sub></i>|&lt;10001,0≤<i>L<sub>i</sub></i>&lt;1000000001</div>

</div>