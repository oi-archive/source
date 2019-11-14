<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>A Sports Day is being held in a primary school in Gdynia. The most important part of the event is the Annual<br>Football Cup.<br>Several children gathered at the football pitch, where teams were to be formed. As everyone wanted to<br>belong to the best team, the players could not reach an agreement. Some of them threatened not to play,<br>others started to cry and now nobody is sure if the tournament will take place at all.<br>Byteman, a sports teacher, is in charge of organizing the tournament. He decided to split the children into<br>teams himself, so that no player would be unhappy with her team. The i-th of the n children on the pitch<br>(numbered 1 through n) said that she will be unhappy with her team if the team consists of less than ai<br>players.<br>Apart from satisfying the children’s requirements, Byteman would like to maximize the total number of<br>teams. If there are still many possibilities, he requests the size of the largest team to be as small as possible.<br>As it turned out to be quite a diﬃcult task, Byteman asked you for help.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>In the ﬁrst line of the standard input there is one integer n (1 ¬ n ¬ 1 000 000). Then, n lines follow. The i-th<br>of these lines contains a single integer ai (1 ¬ ai ¬ n) that denotes the minimum team size that satisﬁes the<br>child number i.<br>Additionally, in test cases worth at least 50 points, n will not exceed 5 000.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>In the ﬁrst line of the standard output your program should write a single integer t equal to the maximum<br />possible number of teams. Then, t lines containing a description of the teams should follow. The i-th of these<br />lines should contain an integer si (1 &not; si &not; n) denoting the size of the i-th team, and then si integers<br />k1, k2, . . . , ksi (1 &not; kj &not; n for j = 1, 2, . . . , si), denoting the numbers of children belonging to the team i. If<br />there are many possible answers, you can output any of the solutions which minimize the size of the largest<br />team (among all the solutions consisting of exactly t teams).</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>2<br>1<br>2<br>2<br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br>2 4 2<br>3 5 1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1 ¬ n ¬ 1 000 000</p>
</div>
</div>