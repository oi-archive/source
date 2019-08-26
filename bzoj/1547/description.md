
# Description

<div class="content">Irena和Sirup正准备下个周末的Party。为这个Party,他们刚刚买了一个非常大的圆桌。他们想邀请每个人，但他们现在不知道如何分配座次。Irena说当有超过K个女孩座位相邻（即这些女孩的座位是连续的，中间没有男孩）的话，她们就会说一整晚的话而不和其他人聊天。
Sirup没有其他选择，只有同意她。然而，作为一名数学家，他很快地痴迷于所有可能方案。
题目说明：
N个人围绕着圆桌坐着，其中一些是男孩，另一些是女孩。你的任务是找出所有合法的方案数，使得不超过K个女孩座位是连续的。
循环同构会被认为是同一种方案。
</div>

# Input

<div class="content">第一行有一个数T，表示以下有T组数据，每组数据有两个整数N，K。
每组数据之间有一个空行隔开。
</div>

# Output

<div class="content">输出T行，每行顺次对应一组测试数据。
每组数据你需要输出最后的方案数除以100000007的余数。

</div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
<br/>
3 1<br/>
<br/>
3 3<br/>
<br/>
4 1<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
4<br/>
3<br/>
<br/>
解释：<br/>
第一组数据的方案是：MMM，MMW (M是男孩, W是女孩)。<br/>
第二组数据的方案是：MMM，MMW，MWW，WWW。<br/>
第三组数据的方案是：MMMM, MMMW,MWMW。<br/>
<br/>
约束和限制：<br/>
对于20%的数据T &lt; = 20;<br/>
对于100%的数据T &lt; = 50;<br/>
对于20%的数据N,K &lt; = 20;<br/>
对于100%的数据N,K &lt; = 2000;<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=HNOI2009集训Day4&amp;ipsc 2008 Large Party">HNOI2009集训Day4&amp;ipsc 2008 Large Party</a></p></div>

