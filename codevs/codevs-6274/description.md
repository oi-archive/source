<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这道题我没定级，不要问我为什么[坏笑]</p><p><br></p><p>ZZH和sqrt_-1之间的战役终于打响了！！！</p><p>他们两个决定用编程一决高下，而他们俩用来决斗的这道题是这样的：</p><p>有一个大小为n*m（n行m列），且每个格子里都有一定数量的金币。初始时，ZZH和sqrt_-1均在第一排正中（m为偶数，则正中为列数的一半，如8列的正中为第4列）。他们每次可以向下面一排离他们最近的3个格子移动（即↙、↓、↘，若在边缘，则可移动范围变小）。求最后到达最后一排时，他们能获得的最多金币数量。</p><p>ZZH大佬推崇使用贪心算法（每次移动到下面一排三个格子中金币最多的一个格子）</p><p>但冷静沉着的sqrt_-1则想使用动态规划来求解这道题。</p><p>现在他们两个的决斗内容是，使用动态规划解决这道题的答案能否比贪心解决这道题的答案还要大K（动归答案-贪心答案≥k？），若能，代表sqrt_-1获胜，并输出“ZZH is the loser."</p><p>若不能，代表ZZH获胜，并输出“sqrt_-1 is the loser,but he is smarter than ZZH."，并换行输出动归答案和贪心答案的差。</p><p><br></p><p>※若ZZH下面三个格子内钱币最多的格子大于1个，则他会选择尽量靠左行走。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共N+1行：第一行，n、m、k.(n:行数 m:列数 k：最终动规要比贪心多钱币数量)</p><p>第2至N+1行： 每行共m个数，表示迷宫内每个格子内的金币数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>两行，第一行为结果，<br/></p><p>若能，输出“ZZH is the loser.&quot;</p><p>若不能，输出“sqrt_-1 is the loser,but he is smarter than ZZH.&quot;。</p><p><br/></p><p>第二行，输出动规答案和贪心答案的差。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5 8<br></p><p>4 2 4 5 6</p><p>2 6 5 2 5</p><p>1 1 1 7 9</p><p>1 1 2 1 9</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>ZZH is the loser.</p><p>13</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，n,m,k≤100。</p><p>对于70%的数据，n,m,k≤1000。</p><p>对于100%的数据，n,m≤2000,k≤10000,且每一格的钱币数≤2000</p><p><br></p><p>样例说明：</p><p>ZZH的路线：4→6→1→1 ans:12</p><p>sqrt_-1的路线：4→5→7→9 ans:25</p><p>差为13.</p><p><br></p><p>P.S.  ZZH小学狗在6305出了一道几乎一样的题，明显是在抄袭，对此sqrt_-1表示很不满~ </p><p>P.S.2 就在我刚发完上一条抄袭吐槽后，ZZH又在他的题上写我在抄袭，且假装自己很大度，其实大家可以根据题号先后顺序来判定谁在抄袭的啦</p><p>本人版权意识强，请见谅~~O(∩_∩)O</p><p><br></p><p>Made By sqrt_-1</p><p>SQRT题目系列II</p>
</div>
</div>