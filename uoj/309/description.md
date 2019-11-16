# 题目描述

<p>九条可怜是一个可爱的男孩子，虽然表面上看起来人畜无害，但他有一个隐藏身份——宇宙OJ舰队的太阳系司令官，专门掌管宇宙OJ舰队在太阳系的部署。</p>
<p>太阳系可以抽象成一个大平面，其中横纵坐标都是整数的点是可以用来存放战舰的，太阳系中存放着若干战舰，每一艘战舰都存放在整点上（由于战舰和宇宙的尺度相比太小，一个整点可以存放任意多艘战舰），同时，每条战舰都有一门主炮，主炮的威力与战舰的能量储存成正比。</p>
<p>九条可怜平日的工作就是调动这些战舰并给战舰武装充能，他一次性可以调动一行或者一列的战舰，并向垂直于选中行列的方向移动，或者可以使用激光充能器对一横行或者一竖行的战舰整体充能相同的能量值。</p>
<p>Sylvia是一个热爱学习的女孩子，虽然表面上看起来人畜无害，但她其实是宇宙OJ舰队的太阳系监察组组长，专门监督九条可怜的工作状况。</p>
<p>Sylvia认为，如果一横行或者一纵列的战舰普遍能量不足，则很可能会成为敌人攻击的切入点，于是她十分注重一横行或者一纵列的战舰的能量值的最大值，而且会经常向九条可怜提出这些询问。</p>
<p>可怜的九条可怜对着Sylvia的询问十分懵逼，然而他又不愿在Sylvia面前破坏自己勇敢，谋略，智慧的光辉形象，于是他找到了你，来解决Sylvia提出的这些问题。</p>

# 输入格式


<p>第一行一个正整数 $n$，表示战舰的数目。</p>
<p>接下来 $n$ 行，每行三个整数 $x_i,y_i,e_i$ 表示每艘战舰的初始坐标和能量值。</p>
<p>接下来一行一个正整数 $m$，表示九条可怜的操作数目与Sylvia询问数目之和。</p>
<p>接下来$m$行，每行格式为下列六种之一：</p>
<p>$\texttt{XMOVE x d}$：给所有横坐标等于 $x$ 的战舰的横坐标加上 $d$</p>
<p>$\texttt{XADD x p}$：给所有横坐标等于 $x$ 的战舰的能量值加上 $p$</p>
<p>$\texttt{YMOVE y d}$：给所有纵坐标等于 $y$ 的战舰的纵坐标加上 $d$</p>
<p>$\texttt{YADD y p}$：给所有纵坐标等于 $y$ 的战舰的能量值加上 $p$</p>
<p>$\texttt{XQUERY x}$：询问横坐标等于 $x$ 的战舰的能量值的最大值</p>
<p>$\texttt{YQUERY y}$：询问纵坐标等于 $y$ 的战舰的能量值的最大值</p>
<p><strong>注意，输入的所有参数都是整数，输入的 $x$ 和 $y$ 可能会寻找不到任何一艘战舰，这种情况下，如果是 $\texttt{MOVE,ADD}$ 操作你可以直接无视，如果是$\texttt{QUERY}$操作则询问答案认为是$0$.</strong></p>

# 输出格式


<p>对于每个 $\texttt{XQUERY}$ 和 $\texttt{YQUERY}$ 操作输出一行一个整数表示询问的答案。</p>

# 样例一


<h4>input</h4>
<pre>5
1 4 1
2 3 2
3 5 3
4 1 4
5 2 5
9
XADD 1 1
XQUERY 1
YADD 3 2
XQUERY 2
YMOVE 2 3
YQUERY 2
XQUERY 5
XMOVE 5 2
XQUERY 2

</pre>

<h4>output</h4>
<pre>2
4
0
5
4

</pre>



# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>本题采用捆绑测试，对于每个子任务，只有通过其中全部数据才可以获得分数。</p>
<p>对于全部数据， $1 \leq n,m \leq 2 \times 10^5; 0 \leq |x_i|,|y_i| \leq 10^9; 1 \leq e_i \leq 10^9$，对于所有询问有 $0 \leq |x|,|y|,|d|,p \leq 10^9$，且在任何时刻任何点的横纵坐标在 $[-10^9,10^9]$ 内，且能量值不超过 $10^9$.</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>限制</th>
</tr></thead><tbody><tr><td>1</td><td>20</td><td>$n,m \leq 5000$</td></tr><tr><td>2</td><td>20</td><td>没有 $\texttt{XMOVE,YMOVE}$ 操作</td></tr><tr><td>3</td><td>20</td><td>没有 $\texttt{XADD,YADD}$ 操作</td></tr><tr><td>4</td><td>40</td><td>$n,m \leq 2 \times 10^5$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=309">样例数据下载</a></p>
