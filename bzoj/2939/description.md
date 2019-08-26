
# Description

<div class="content"><div align="center"></div>
<div style="text-indent: 21pt"><span style="font-size: medium">一个滑雪队在Byte山上组织了一次训练。山的北坡有一个滑雪场，所有的滑雪者都要从山上的起点站滑到山下的终点站。此次训练中各队员同时出发到终点站会合，除了始末两处外，队员们的滑雪路径不能相交，且山上的滑雪道只能从上往下滑。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">滑雪道的分布地图由多块被林地连接的空地组成，每块空地都处于不同的高度。两块空地间至多由一块林地连接。滑雪过程中，滑雪者可以选择路径访问任一空地（但不必全部经过）。各滑雪道只在空地相会，既不穿隧道，也不临空飞越。</span></div>
<div><span style="font-size: medium"><b>任务：</b></span></div>
<div style="text-indent: 18pt"><span style="font-size: medium">编写一个程序完成下列工作：</span></div>
<div style="margin: 0cm 0cm 0pt 36pt; text-indent: -18pt"><span style="font-size: medium">●<span style="font: 7pt &#39;Times New Roman&#39;">   </span>读入滑雪场的地图；</span></div>
<div style="margin: 0cm 0cm 0pt 36pt; text-indent: -18pt"><span style="font-size: medium">●<span style="font: 7pt &#39;Times New Roman&#39;">     </span>算出能参加训练的最大队员数；</span></div>
<div style="margin: 0cm 0cm 0pt 36pt; text-indent: -18pt"><span style="font-size: medium">●<span style="font: 7pt &#39;Times New Roman&#39;">     </span>把结果输出</span></div></div>

# Input

<div class="content"><div> <span style="font-size: medium">第一行是空地的数目n，2≤n≤5000。以下n-1行，每行都有一些用空格分开的整数，第(i+1)行的数字描述的是从空地i沿林地往下可到达的其它空地。该行第一个整数k表示这些空地的个数，以下k个整数即它们的编号，按从东到西的顺序排列(即通向各空地的林地的位置)。空地从1到n编号。起点站建于空地1，终点站建于空地n。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">  仅一行，包括一个整数，即能参加训练的最大人数。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">15<br/>
5 3 5 9 2 4<br/>
1 9<br/>
2 7 5 <br/>
2 6 8<br/>
1 7<br/>
1 10<br/>
2 14 11<br/>
2 10 12<br/>
2 13 10<br/>
3 13 15 12<br/>
2 14 15<br/>
1 15<br/>
1 15<br/>
1 15<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

