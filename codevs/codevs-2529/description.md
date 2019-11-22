<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>As a part of a new advertising campaign, a big company in Gdynia wants to put its logo somewhere in the<br>city. The company is going to spend the whole advertising budget for this year on the logo, so it has to be<br>really huge. One of the managers decided to use whole buildings as parts of the logo.<br>The logo consists of n vertical stripes of diﬀerent heights. The stripes are numbered from 1 to n from left<br>to right. The logo is described by a permutation (s1, s2, . . . , sn) of numbers 1, 2, . . . , n. The stripe number s1<br>is the shortest one, the stripe number s2 is the second shortest etc., ﬁnally the stripe sn is the tallest one. The<br>actual heights of the stripes do not really matter.<br>There are m buildings along the main street in Gdynia. To your surprise, the heights of the buildings are<br>distinct. The problem is to ﬁnd all positions where the logo matches the buildings.<br>Help the company and ﬁnd all contiguous parts of the sequence of buildings which match the logo. A<br>contiguous sequence of buildings matches the logo if the building number s1 within this sequence is the<br>shortest one, the building number s2 is the second shortest, etc. For example a sequence of buildings of heights<br>5, 10, 4 matches a logo described by a permutation (3, 1, 2), since the building number 3 (of height 4) is the<br>shortest one, the building number 1 is the second shortest and the building number 2 is the tallest.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The ﬁrst line of the standard input contains two integers n and m (2 ¬ n ¬ m ¬ 1 000 000). The second line<br>contains n integers si, forming a permutation of the numbers 1, 2, . . . , n. That is, 1 ¬ si ¬ n and si = sj for<br>i = j. The third line contains m integers hi — the heights of the buildings (1 ¬ hi ¬ 109 for 1 ¬ i ¬ m). All<br>the numbers hi are diﬀerent. In each line the integers are separated by single spaces.<br>Additionally, in test cases worth at least 35 points, n ¬ 5 000 and m ¬ 20 000, whereas in test cases worth<br>at least 60 points, n ¬ 50 000 and m ¬ 200 000.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>The ﬁrst line of the standard output should contain an integer k, the number of matches. The second line<br />should contain k integers &mdash; 1-based indices of buildings which correspond to the stripe number 1 from the<br />logo in a proper match. The numbers should be listed in an increasing order and separated by single spaces.<br />If k = 0, your program should print an empty second line.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 10<br>2 1 5 3 4<br>5 6 3 8 12 7 1 10 11 9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br>2 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2 ¬ n ¬ m ¬ 1 000 000</p>
</div>
</div>