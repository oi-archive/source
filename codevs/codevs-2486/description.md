<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　七夕祭上，Vani牵着cl的手，在明亮的灯光和欢乐的气氛中愉快地穿行。这时，在前面忽然出现了一台太鼓达人机台，而在机台前坐着的是刚刚被精英队伍成员XLk、Poet_shy和lydrainbowcat拯救出来的的applepi。看到两人对太鼓达人产生了兴趣，applepi果断闪人，于是cl拿起鼓棒准备挑战。然而即使是在普通难度下，cl的路人本性也充分地暴露了出来。一曲终了，不但没有过关，就连鼓都不灵了。Vani十分过意不去，决定帮助工作人员修鼓。</p>
<p>　　鼓的主要元件是M个围成一圈的传感器。每个传感器都有开和关两种工作状态，分别用1和0表示。显然，从不同的位置出发沿顺时针方向连续检查K个传感器可以得到M个长度为K的01串。Vani知道这M个01串应该是互不相同的。而且鼓的设计很精密，M会取到可能的最大值。现在Vani已经了解到了K的值，他希望你求出M的值，并给出字典序最小的传感器排布方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　一个整数K。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　一个整数M和一个二进制串，由一个空格分隔。表示可能的最大的M，以及字典序最小的排布方案，字符0表示关，1表示开。你输出的串的第一个字和最后一个字是相邻的。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8 00010111</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例说明 <br>　　得到的8个01串分别是000、001、010、101、011、111、110和100。注意前后是相邻的。长度为3的二进制串总共只有8种，所以M = 8一定是可能的最大值。</p>
<p>数据范围与约定 <br>　　对于全部测试点，2≤K≤11。</p>
<p>来源：Nescafe 18</p>
</div>
</div>