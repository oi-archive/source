<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Tom最近在研究一个有趣的排序问题。<br/>
　　<img width="197" height="163" src="source/tsinsen/A1169/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9TUhldGhmeVQ=.do"/>.<br/>
<br/>
<br/>
　　如图所示，通过2个栈S1和S2，Tom希望借助以下4种操作实现将输入序列升序排序。<br/>
　　操作a<br/>
　　如果输入序列不为空，将第一个元素压入栈S1<br/>
　　操作b<br/>
　　如果栈S1不为空，将S1栈顶元素弹出至输出序列<br/>
　　操作c<br/>
　　如果输入序列不为空，将第一个元素压入栈S2<br/>
　　操作d<br/>
　　如果栈S2不为空，将S2栈顶元素弹出至输出序列<br/>
　　如果一个1~n的排列P可以通过一系列操作使得输出序列为1，2，…，(n-1)，n，Tom就称P是一个“可双栈排序排列”。例如(1,3,2,4)就是一个“可双栈排序序列”，而(2,3,4,1)不是。下图描述了一个将(1,3,2,4)排序的操作序列：&lt;a,c,c,b,a,d,d,b&gt;<br/>
　　<img width="487" height="556" src="source/tsinsen/A1169/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9VE5ZUm1hYUw=.do"/>.<br/>
<br/>
　　当然，这样的操作序列有可能有几个，对于上例(1,3,2,4)，&lt;a,c,c,b,a,d,d,b&gt;是另外一个可行的操作序列。Tom希望知道其中字典序最小的操作序列是什么。</div>
# 输入格式

<div class="pdcont">　　输入的第一行是一个整数n。<br/>
　　第二行有n个用空格隔开的正整数，构成一个1~n的排列。</div>
# 输出格式

<div class="pdcont">　　输出一行，如果输入的排列不是“可双栈排序排列”，输出数字0；否则输出字典序最小的操作序列，每两个操作之间用空格隔开，行尾没有空格。</div>
# 样例输入

<div class="pddata">4<br/>
1 3 2 4</div>
# 样例输出

<div class="pddata">a b a a b b a b</div>
# 样例输入

<div class="pddata">4<br/>
2 3 4 1</div>
# 样例输出

<div class="pddata">0</div>
# 样例输入

<div class="pddata">3<br/>
2 3 1</div>
# 样例输出

<div class="pddata">a c a b b d</div>
# 数据规模和约定

<div class="pdcont">　　30%的数据满足： n&lt;=10<br/>
　　50%的数据满足： n&lt;=50<br/>
　　100%的数据满足： n&lt;=1000</div>

</div>