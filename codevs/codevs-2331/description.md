<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>A 公司正在举办一个智力双人游戏比赛----取石子游戏，游戏的获胜者将会获得 A 公司提供的丰厚奖金，因此吸引了来自全国各地的许多聪明的选手前来参加比赛。 <br>与经典的取石子游戏相比，A公司举办的这次比赛的取石子游戏规则复杂了很多： <br>总共有N堆石子依次排成一行，第i堆石子有 ai个石子。 <br>开始若干堆石子已被 A公司故意拿走。 <br>然后两个玩家轮流来取石子，每次每个玩家可以取走一堆中的所有石子，但有一个限制条件：一个玩家若要取走一堆石子，则与这堆石子相邻的某堆石子已被取走(之前被某个玩家取走或开始被A公司故意拿走)。注意：第 1堆石子只与第 2堆石子相邻，第N堆石子只与第N-1堆石子相邻，其余的第 i堆石子与第i-1堆和第 i+1 堆石子相邻。 <br>所有石子都被取走时，游戏结束。谁最后取得的总石子数最多，谁就获得了这场游戏的胜利。 <br>作为这次比赛的参赛者之一，绝顶聪明的你，想知道对于任何一场比赛，如果先手者和后手者都使用最优的策略，最后先手者和后手者分别能够取得的总石子数分别是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行是一个正整数N，表示有多少堆石子。输入文件第二行是用空格隔开的N个非负整数a1, a2, …, aN，其中ai表示第i堆石子有多少个石子，ai = 0表示第i堆石子开始被A公司故意拿走。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一行，为两个整数，分别表示都使用最优策略时，最后先手者和后手者各自能够取得的总石子数，并且两个整数间用一个空格隔开。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8 <br>1 2 0 3 7 4 0 9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>17 9 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入的数据保证0≤ai≤100,000,000，并且至少有<br>一个i使得ai = 0。30%的数据满足2≤N≤100，100%的数据满足2≤N≤1,000,000。</p>
</div>
</div>