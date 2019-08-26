
# Description

<div class="content"><div>FJ打算好好修一下农场中某条凹凸不平的土路。按奶牛们的要求，修好后的路面高度应当单调上升或单调下降，也</div>
<div>就是说，高度上升与高度下降的路段不能同时出现在修好的路中。 整条路被分成了N段，N个整数A_1, ... , A_N </div>
<div>(1 &lt;= N &lt;= 2,000)依次描述了每一段路的高度(0 &lt;= A_i &lt;= 1,000,000,000)。FJ希望找到一个恰好含N个元素的</div>
<div>不上升或不下降序列B_1, ... , B_N，作为修过的路中每个路段的高度。由于将每一段路垫高或挖低一个单位的花</div>
<div>费相同，修路的总支出可以表示为： |A_1 - B_1| + |A_2 - B_2| + ... + |A_N - B_N| 请你计算一下，FJ在这</div>
<div>项工程上的最小支出是多少。FJ向你保证，这个支出不会超过2^31-1。</div></div>

# Input

<div class="content"><div>* 第1行: 输入1个整数：N </div>
<div>* 第2..N+1行: 第i+1行为1个整数：A_i</div></div>

# Output

<div class="content"><p>* 第1行: 输出1个正整数，表示FJ把路修成高度不上升或高度不下降的最小花费</p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
1<br/>
3<br/>
2<br/>
4<br/>
5<br/>
3<br/>
9</span></div>

# Sample Output

<div class="content"><span class="sampledata">//FJ将第一个高度为3的路段的高度减少为2，将第二个高度为3的路段的高度增加到5，总花费为|2-3|+|5-3| = 3<br/>
，并且各路段的高度为一个不下降序列 1,2,2,4,5,5,9。</span></div>

# Hint

<div class="content"><p></p><p><font size="3">2017.11.07新加两组数据By </font>Alextokc</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

