<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有n个小朋友排成一列。每个小朋友手上都有一个数字，这个数字可正可负。规定每个小朋友的特征值等于排在他前面（包括他本人）的小朋友中连续若干个（最少有一个）小朋友手上的数字之和的最大值。<br>作为这些小朋友的老师，你需要给每个小朋友一个分数，分数是这样规定的：第一个小朋友的分数是他的特征值，其它小朋友的分数为排在他前面的所有小朋友中（不包括他本人），小朋友分数加上其特征值的最大值。<br>请计算所有小朋友分数的最大值，输出时保持最大值的符号，将其绝对值对p取模后输出。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个正整数n、p，之间用一个空格隔开。<br>第二行包含n个数，每两个整数之间用一个空格隔开，表示每个小朋友手上的数字。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，包含一个整数，表示最大分数对p取模的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>[Sample 1]<br>5 997<br>1 2 3 4 5<br>[Sample 2]<br>5 7<br>-1 -1 -1 -1 -1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>[Sample 1]<br>21<br>[Sample 2]<br>-1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】<br>样例1小朋友的特征值分别为1、3、6、10、15，分数分别为1、2、5、11、21，最大值21对997的模是21。<br>样例2小朋友的特征值分别为-1、-1、-1、-1、-1，分数分别为-1、-2、-2、-2、-2，最大值-1对7的模为-1，输出-1。<br> <br>【数据范围】<br>对于50%的数据，1&amp;le;n&amp;le;1,000，1&amp;le;p&amp;le;1,000所有数字的绝对值不超过1000；<br>对于100%的数据，1&amp;le;n&amp;le;1,000,000，1&amp;le;p&amp;le;10^9，其他数字的绝对值均不超过10^9。</p>
</div>
</div>