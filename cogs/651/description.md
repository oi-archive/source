# 题目描述


<div>【问题描述】</div>
<div style="text-indent: 24pt">探险队长凯因意外的弄到了一份黑暗森林的藏宝图，于是，探险队一行人便踏上了寻宝之旅，去寻找传说中的宝藏。</div>
<div style="text-indent: 24pt">藏宝点分布在黑暗森林的各处，每个点有一个值，表示藏宝的价值。它们之间由一些小路相连，小路不会形成环，即两个藏宝点之间有且仅有一条通路。探险队从其中的一点出发，每次他们可以留一个人在此点开采宝藏，也可以不留，然后其余的人可以分成若干队向这一点相邻的点走去。需要注意的是，如果他们把队伍分成两队或者两队以上，就必须留一个人在当前点，提供联络和通讯，当然这个人也可以一边开采此地的宝藏。并且，为了节约时间，队伍在前往开采宝藏的过程中是不会走回头路的。现在你作为队长的助理，根据已有的藏宝图，请计算探险队所能开采的最大宝藏价值。</div>
<div style="text-indent: 24pt"> </div>
<div>【输入】</div>
<div style="text-indent: 24pt">输入格式(输入文件名<span>seek.in</span>)</div>
<div style="text-indent: 24pt">第1行有两个正整数，n(1≤n≤100)表示藏宝点的个数，m(1≤m≤100)表示探险队的人数。</div>
<div style="text-indent: 24pt">第2行是，n个不超过100的正整数，分别表示1到n每个点的宝藏价值。</div>
<div style="text-indent: 24pt">接下来的n-1行，每行两个数，x和y(1≤x，y≤n，x≠y)，表示藏宝点x与Y之间有一条路，数据保证不会有重复的路出现。</div>
<div style="text-indent: 24pt">假设一开始探险队在点1处。</div>
<div style="text-indent: 24pt"> </div>
<div>【输出】</div>
<div style="text-indent: 24pt">输出格式(输出文件名seek．out)</div>
<div style="text-indent: 24pt">一个整数，表示探险队所能获得最大的宝藏价值。</div>
<div style="text-indent: 24pt"> </div>
<div>【输入输出样例】</div>
<div style="text-indent: 24pt">输入样例(<span>seek.in)</span></div>
<div style="text-indent: 24pt">5 3</div>
<div style="text-indent: 24pt">1 3 7 2 8</div>
<div style="text-indent: 24pt">1 2</div>
<div style="text-indent: 24pt">2 3</div>
<div style="text-indent: 24pt">1 4</div>
<div style="text-indent: 24pt">4 5</div>
<div style="text-indent: 24pt">输出样例(<span>seek.out);</span></div>
<div style="text-indent: 24pt">16</div>
