<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Your friend owns a hotel at the seaside in Gdynia. The summer season is just starting and he is overwhelmed<br>by the number of oﬀers from potential customers. He asked you for help in preparing a reservation system for<br>the hotel.<br>There are n rooms for rent in the hotel, the i-th room costs your friend ci zlotys of upkeep (only if it is<br>rented) and has a capacity of pi people. You may assume that the upkeep of a room is never cheaper than the<br>upkeep of any smaller room, that is, of any room which can hold a smaller number of people.<br>The reservation system will be receiving multiple oﬀers, each of them specifying the amount of zlotys for<br>rental of any room (vj) for one particular day and the minimal capacity of the requested room (dj). For each<br>oﬀer, only a single room can be rented. And conversely: each room can accommodate only a single oﬀer. Your<br>friend has decided not to accept more than o oﬀers.<br>Knowing you are a skilled programmer, your friend asked you to implement the part of the system which<br>ﬁnds the maximum proﬁt (total income from renting out rooms minus their upkeep) he can make by accepting<br>some of the oﬀers.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The ﬁrst line of the standard input contains three integers n, m, and o (1 ¬ n,m ¬ 500 000, 1 ¬ o ¬ min(m, n)),<br>denoting the number of rooms in the hotel, the number of oﬀers received and the maximum number of oﬀers<br>your friend is willing to accept. The next n lines describe the rooms, with the i-th of these lines containing two<br>integers ci, pi representing the upkeep of the room in zlotys and the capacity of the room (1 ¬ ci, pi ¬ 109).<br>The next m lines describe the oﬀers, with the j-th of these lines containing two integers vj , dj representing<br>the oﬀered rental price in zlotys and the minimal capacity of the requested room (1 ¬ vj , dj ¬ 109).<br>You may assume that in test cases worth 40 points in total an additional inequality n,m ¬ 100 holds.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>The ﬁrst and only line of the standard output should contain one integer equal to the maximum proﬁt your<br />friend can achieve accepting at most o of the oﬀers. Note that the proﬁt might get big.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2 2<br>150 2<br>400 3<br>100 2<br>200 1<br>700 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>400</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1 ¬ n,m ¬ 500 000</p>
</div>
</div>