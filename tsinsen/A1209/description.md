<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　小明爱上了炒股。经过近段时间的观察和整理，他发现了如果一个股票出现了某种形态的K线，那么这个股票很可能不久之后就会大涨。小明想利用这种神奇的K线来做一个股票软件。他将一条K线用一个的整数序列a来表示。假设a的长度为L，当且仅当序列(a<sub>1</sub><i>-a</i><sub>0</sub>,<i>a</i><sub>2</sub><i>-a</i><sub>1</sub>,<i>…</i>,<i>a<sub>L</sub>-a<sub>L-</sub></i><sub>1</sub>)为序列p的前缀时，这条K线是一条神奇的K线。但是事情总不是一帆风顺的，小明发现许多K线不是神奇的，但之后也能大涨。不过他发现这些K线都和神奇的K线很接近。为了进一步扩展神奇的K线的用途，小明定义K线a和神奇的K线的差异度：<br/>
　　将a中某一个元素修改成任意值的代价为modify，将a中某一个元素删除的代价为delete。将a变成神奇的K线的最小代价即为K线a和神奇的K线的差异度。<br/>
　　虽然小明自己可以很快地算出某条K线和神奇的K线的差异度，但是如果要做成软件，还得写个程序来计算。你能帮帮他吗？</div>
# 输入格式

<div class="pdcont">　　第一行包含三个正整数n，modify，delete。n表示给出的K线a的长度，modify和delete的含义如题。<br/>
　　第二行n-1个整数，依次表示p<sub>1</sub>到p<sub>n</sub><sub>-1</sub>，含义如题。<br/>
　　第三行n个整数，依次表示给出的K线a中的n个元素。</div>
# 输出格式

<div class="pdcont">　　输出一行一个数表示K线a和神奇的K线的差异度。</div>
# 样例输入

<div class="pddata">8 1 2<br/>
1 2 3 4 5 6 7<br/>
0 1 999 6 10 -999 15 21</div>
# 样例输出

<div class="pddata">3</div>
# 数据规模和约定

<div class="pdcont">　　30%的数据中n≤100；<br/>
　　60%的数据中n≤500；<br/>
　　100%的数据中<br/>
　　n≤1500；<br/>
　　modify，delete≤1000000；<br/>
　　p中每个元素的绝对值均≤1000；<br/>
　　a中每个元素的绝对值均≤1000000。</div>

</div>