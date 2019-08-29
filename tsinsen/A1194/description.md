<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　小 T 是一名质量监督员，最近负责检验一批矿产的质量。这批矿产共有n 个矿石，从1到n 逐一编号，每个矿石都有自己的重量wi 以及价值vi。检验矿产的流程是：<br/>
　　1、给定m 个区间[Li，Ri]；<br/>
　　2、选出一个参数W；<br/>
　　3、对于一个区间[Li，Ri]，计算矿石在这个区间上的检验值Yi ：<br/>
<img width="560" height="66" src="source/tsinsen/A1194/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9REdZTlE4UUc=.do"/><br/>
<br/>
　　这批矿产的检验结果Y 为各个区间的检验值之和。即：Y=sumYi<br/>
　　若这批矿产的检验结果与所给标准值S 相差太多，就需要再去检验另一批矿产。小T不想费时间去检验另一批矿产，所以他想通过调整参数W 的值，让检验结果尽可能的靠近标准值S，即使得S-Y 的绝对值最小。请你帮忙求出这个最小值。</div>
# 输入格式

<div class="pdcont">　　输入第一行包含三个整数 n，m，S，分别表示矿石的个数、区间的个数和标准值。<br/>
　　接下来的 n 行，每行2 个整数，中间用空格隔开，第i+1 行表示i 号矿石的重量wi 和价值vi 。<br/>
　　接下来的 m 行，表示区间，每行2 个整数，中间用空格隔开，第i+n+1 行表示区间[Li,Ri]的两个端点Li 和Ri。注意：不同区间可能重合或相互重叠。</div>
# 输出格式

<div class="pdcont">　　输出只有一行，包含一个整数，表示所求的最小值。</div>
# 样例输入

<div class="pddata">5 3 15<br/>
1 5<br/>
2 5<br/>
3 5<br/>
4 5<br/>
5 5<br/>
1 5<br/>
2 4<br/>
3 3</div>
# 样例输出

<div class="pddata">10</div>
# 数据规模和约定

<div class="pdcont">　　对于 10%的数据，有1≤n，m≤10；<br/>
　　对于 30%的数据，有1≤n，m≤500；<br/>
　　对于 50%的数据，有1≤n，m≤5,000；<br/>
　　对于 70%的数据，有1≤n，m≤10,000；<br/>
　　对于 100%的数据，有1≤n，m≤200,000，0 &lt; wi, vi≤106，0 &lt; S≤1012，1≤Li≤Ri≤n。</div>

</div>