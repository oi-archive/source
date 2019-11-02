<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>You are gathering readings of acidity level in a very long river in order to determine the health of the river.</p>
<p>你正在收集一条长河的酸性等级读数来判断这条河流的健康程度。</p>
<p>You have placed N sensors (2 ≤ N ≤ 2 000 000) in the river, and each sensor gives an integer reading R (1 ≤ R ≤ 1 000).</p>
<p>你放了N(2 ≤ N ≤ 2 000 000)个读数器在这条河里，每个读数器会读出一个数值R(1 ≤ R ≤ 1 000)。</p>
<p>For the purposes of your research, you would like to know the frequency of each reading, and ﬁnd the absolute difference between the two most frequent readings.</p>
<p>作为研究的目的，你想知道每个读数的出现次数，然后找到最高频的两个读数之间的差值是多大。</p>
<p>If there are more than two readings that have the highest frequency, the difference computed should be the largest such absolute difference between two readings with this frequency. If there is only one reading with the largest frequency, but more than one reading with the second largest fre- quency, the difference computed should be the largest absolute difference between the most fre- quently occurring reading and any of the readings which occur with second-highest frequency.</p>
<p>如果有多个最高频读数和次高频读数，则计算出他们之间最大的差值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The ﬁrst line of input will be the integer N (2 ≤ N ≤ 2 000 000), the number of sensors. The next N lines each contain the reading for that sensor, which is an integer R (1 ≤ R ≤ 1 000). You should assume that there are at least two different readings in the input.</p>
<p>第一行包含一个整数N (2 ≤ N ≤ 2 000 000)，代表读数器的个数。接下来N行每行一个整数代表各个读数器的读数R (1 ≤ R ≤ 1 000)。你可以假设输入至少包含2个不同的读数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>Output the positive integer value representing the absolute difference between the two most fre- quently occurring readings, subject to the tie-breaking rules outlined above.</p>
<p>输出一个正整数，代表最高频读数和次高频读数的最大差值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入 1： 5 1 1 1 4 3</p>
<p>样例输入 2： 4 10 6 1 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出 1： 3</p>
<p>样例输出 2： 9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>