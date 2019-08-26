
# Description

<div class="content"><div><span style="font-size: medium"><span style="color: #555555">旅行商认定如何优化旅行路线是一个非常棘手的计算问题，所以他决定沿着线性的多瑙河开展他的业务。他有一条快船能够在瞬间沿着多瑙河把他从任意开始的位置带到任意目的地，但是这条船很费油。它逆流而上(驶向源头的方向)每米花费U元，顺流而下每米花费D元(驶离源头的方向）。</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">沿着多瑙河有N个展销会是旅行商所感兴趣的。每个展销会只持续一天。对于任意一个展销会X，旅行商知道：①展销日期是Tx(该日期是从旅行商买船之日算起过去的天数)，②展销地点是Lx(该地点用它与源头的距离表示，单位为米)，③参加该展销会能赚到的钱数是Mx元。旅行商开始和结束旅程的地点都是他位于多瑙河边的家S (用它与源头的距离表示，单位为米)。</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">请帮助旅行商选择他是否参加，如果参加应该以什么样的顺序参加哪些展销会才能在旅行结束时获得最多的总收益。旅行商的总收益定义为他参加的所有展销会的收益和，减去他在河上顺流和逆流航行的总花费。</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">注意：如果展销会A在展销会B之前举行并且旅行商要参加这两个展销会，旅行商必须先参加A，之后才能参加B(即他不能先参加B后参加A)。当两个展销会在同一天举行，他可以按任意顺序参加这两个展销会。旅行商在一天之内参加的展销会的数目没有限制，但是他不能参加同一个展销会两次并在一个展销会上获得两次收益。他可以经过他已经参加过的展销会而不再获得任何收益。</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">任务</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">写一个程序，给定所有展销会的日期、地点和收益，以及旅行商的家的位置和他旅行的花费，计算他在旅行结束时可能获得的最大的总收益。</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">数据规模</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">1</span><span style="color: #555555">≤N≤500,000     展销会的数目</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">1</span><span style="color: #555555">≤D≤U≤10          旅行每米的花费，逆流而上(U)和顺流而下(D)</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">1</span><span style="color: #555555">≤S≤500,001     旅行商的家的位置</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">1</span><span style="color: #555555">≤Tk≤500,000       展销会k举行的日期</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">1</span><span style="color: #555555">≤Lk≤500,001       展销会k的地点</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">1</span><span style="color: #555555">≤Mk≤4,000      旅行商参加展销会k所能获得的收益</span></span></div></div>

# Input

<div class="content"><div><span style="font-size: medium"><span style="color: #555555">你的程序需要从标准输入读人下列数据：</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">· 第一行依次包含整数N，U，D和S，整数之间用空格隔开。</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">· 接下来的N行描述了N个展销会的情况(不按特定顺序)。这N行中的第k<sup>th</sup>行描述了第k<sup>th</sup>个展销会的情况，它包含三个整数(整数之间分别用一个空格隔开)分别表示展销会的日期Tk，地点Lk，和收益Mk。</span></span></div>
<div><span style="font-size: medium"><span style="color: #555555">注意：输人中给出的所有地点都是不同的。即没有两个展销会在同一个地点举行，也没有展销会在旅行商的家的位置上举行。</span></span></div></div>

# Output

<div class="content"><div><span style="font-size: medium"><span style="color: #555555">你的程序必须向标准输出写入一行，该行包含一个整数：旅行商结束旅行时能够获得的最大总收益。</span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 3 100<br/>
2 80 100<br/>
20 125 130<br/>
10 75 150<br/>
5 120 110<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">50</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

