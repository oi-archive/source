<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>背景</p>
<p>在双人对决的竞技性比赛，如乒乓球、羽毛球、国际象棋中，最常见的赛制是淘汰赛和循环赛。前者的特点是比赛场数少，每场都紧张刺激，但偶然性较高。后者的特点是较为公平，偶然性较低，但比赛过程往往十分冗长。<br>本题中介绍的瑞士轮赛制，因最早使用于 1895 年在瑞士举办的国际象棋比赛而得名。它可以看作是淘汰赛与循环赛的折衷，既保证了比赛的稳定性，又能使赛程不至于过长。</p>
<p>2*N 名编号为1~2N 的选手共进行R 轮比赛。每轮比赛开始前，以及所有比赛结束后，都会按照总分从高到低对选手进行一次排名。选手的总分为第一轮开始前的初始分数加上已参加过的所有比赛的得分和。总分相同的，约定编号较小的选手排名靠前。每轮比赛的对阵安排与该轮比赛开始前的排名有关：第 1 名和第2 名、第3 名和第4名、……、第2K – 1 名和第2K 名、…… 、第 2N – 1 名和第2N 名，各进行一场比赛。每场比赛胜者得1 分，负者得0 分。也就是说除了首轮以外，其它轮比赛的安排均不能事先确定，而是要取决于选手在之前比赛中的表现。<br>现给定每个选手的初始分数及其实力值，试计算在 R 轮比赛过后，排名第Q 的选手编号是多少。我们假设选手的实力值两两不同，且每场比赛中实力值较高的总能获胜。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行是三个正整数 N、R、Q，每两个数之间用一个空格隔开，表示有2*N 名选手、R 轮比赛，以及我们关心的名次Q。<br>第二行是 2*N 个非负整数s1, s2, …, s2N，每两个数之间用一个空格隔开，其中si 表示编号为i 的选手的初始分数。<br>第三行是 2*N 个正整数w1, w2, …, w2N，每两个数之间用一个空格隔开，其中wi 表示编号为i 的选手的实力值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，包含一个整数，即 R 轮比赛结束后，排名第Q 的选手的编号。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 4 2<br>7 6 6 7<br>10 5 20 15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围<br>对于 30%的数据，1 ≤ N≤ 100；<br>对于 50%的数据，1 ≤ N≤ 10,000；<br>对于 100%的数据，1 ≤ N≤ 100,000，1 ≤ R≤ 50，1 ≤ Q≤ 2N，0 ≤ s1, s2, …, s2N ≤ 108，1 ≤ w1,w2, …, w2N ≤ 108。</p>
</div>
</div>