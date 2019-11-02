<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在3月29日举行的女子冰壶世锦赛决赛中，王冰玉、柳荫、岳清爽和周妍组成的中国女子冰壶队以8比6击败了冬奥会和世锦赛双冠王瑞典队，夺得了中国冰壶历史上第一枚世锦赛金牌，创造了历史。美丽、实力兼具的中国冰壶姑娘们也赢得了超高的赞誉。</p>
<p>在冰壶比赛中，给出一个<strong><em>目标点</em></strong><strong><em>P</em></strong>，以及一个规定的正整数r。每一局由甲乙两队轮流投冰壶各8次后，该局比赛结束。此时，哪一方的冰壶最终离<strong><em>目标点</em></strong><strong><em>P</em></strong>更近，该方得分，另一方不得分。得分方每颗离<strong><em>目标点</em></strong><strong><em>P</em></strong>距离小于或等于r、位置较另一队所有冰壶都更接近<strong><em>目标点</em></strong><strong><em>P</em></strong>的冰壶都可以得1分。</p>
<p>比赛最多进行10局。双方之间的某局比赛结束后，落后一方可以弃权。此时，比赛不再进行下去。</p>
<p>已知每一局结束时，双方的每个冰壶离<strong><em>目标点</em></strong><strong><em>P</em></strong>的距离，以及正整数r，请你写一个程序判断两队之间每一局比赛的得分，以及总得分。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件</p>
<p>只有一个正整数r。</p>
<p>以下有若干行(不超过20行),除了最后一行外,每一行有8个正整数(互相之间以一个空格分隔)。</p>
<p>第2行的第j个数表示第1局比赛结束时，甲方的第j个冰壶距离<strong><em>目标点</em></strong><strong><em>P</em></strong>的距离;</p>
<p>第3行的第j个数表示第1局比赛结束时，乙方的第j个冰壶距离<strong><em>目标点</em></strong><strong><em>P</em></strong>的距离;</p>
<p>第4行的第j个数表示第2局比赛结束时，甲方的第j个冰壶距离<strong><em>目标点</em></strong><strong><em>P</em></strong>的距离;</p>
<p>第5行的第j个数表示第2局比赛结束时，乙方的第j个冰壶距离<strong><em>目标点</em></strong><strong><em>P</em></strong>的距离;</p>
<p>    … …</p>
<p>第2k行的第j个数表示第k局比赛结束时，甲方的第j个冰壶距离<strong><em>目标点</em></strong><strong><em>P</em></strong>的距离;</p>
<p>第2k+1行的第j个数表示第k局比赛结束时，乙方的第j个冰壶距离<strong><em>目标点</em></strong><strong><em>P</em></strong>的距离;</p>
<p>如果有一方中途弃权，则最后一行(偶数行)只有一个整数-1，表示此时发生弃权情况。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件</p>
<p>每行有二个整数，中间以一个冒号分隔，表示每一局比赛甲乙双方的比分(甲得分在前)。</p>
<p>最后一行有二个整数，中间以一个冒号分隔，表示甲乙双方比赛的最终得分(甲得分在前)。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>12<br>5 60 25 74 71 100 3 93<br>66 75 70 66 52 73 67 14<br>93 84 74 99 79 64 89 22<br>65 5 95 59 80 8 35 61<br>65 61 49 60 58 50 32 85<br>68 38 96 38 82 64 26 93<br>74 92 47 21 97 30 45 78<br>44 99 90 27 3 46 55 34<br>49 45 83 3 18 1 67 23<br>60 47 95 81 17 1 87 85<br>18 74 74 84 29 20 27 71<br>37 60 26 56 23 65 67 49<br>57 7 62 92 52 5 10 69<br>46 97 88 28 76 27 66 7<br>89 89 94 31 11 20 1 17<br>19 48 35 6 77 61 45 21<br>52 11 76 70 73 99 85 55<br>90 25 20 7 64 24 94 4<br>3 43 32 74 10 93 35 77<br>77 100 63 91 10 73 22 57</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2:0<br>0:2<br>0:0<br>0:1<br>0:0<br>0:0<br>1:0<br>1:0<br>0:2<br>1:0<br>5:5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>70%的数据，双方均不弃权，比赛进行10局。</p>
<p>100%的数据，每只冰壶距离目标点P的距离不超过100。</p>
</div>
</div>