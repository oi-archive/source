<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    在某个遥远的国家里，有 n个城市。编号为 1,2,3,…,n。这个国家的政府修建了m 条双向道路，每条道路连接着两个城市。政府规定从城市 S 到城市T需要收取的过路费为所经过城市之间道路长度的最大值。如：A到B长度为 2，B到C 长度为3，那么开车从 A经过 B到C 需要上交的过路费为 3。<br><span style="">    佳佳是个做生意的人，需要经常开车从任意一个城市到另外一个城市，因此他需要频繁地上交过路费，由于忙于做生意，所以他无时间来寻找交过路费最低的行驶路线。然而， 当他交的过路费越多他的心情就变得越糟糕。 作为秘书的你，需要每次根据老板的起止城市，提供给他从开始城市到达目的城市，最少需要上交多少过路费。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行是两个整数 n 和m，分别表示城市的个数以及道路的条数。 <br>    接下来 m 行，每行包含三个整数 a，b，w（1≤a，b≤n，0≤w≤10^9），表示a与b之间有一条长度为 w的道路。<br><span style="">    接着有一行为一个整数 q，表示佳佳发出的询问个数。 <br></span><span style="">    再接下来 q行，每一行包含两个整数 S，T（1≤S,T≤n，S≠T）, 表示开始城</span><span style="">市S 和目的城市T。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 输出共q行，每行一个整数，分别表示每个询问需要上交的最少过路费用。输入数据保证所有的城市都是连通的。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5 <br>1 2 10 <br>1 3 20 <br>1 4 100 <br>2 4 30 <br>3 4 10 <br>2 <br>1 4 <br>4 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>20 <br>20</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 30%的数据，满足 1≤ n≤1000，1≤m≤10000，1≤q≤100； <br>对于 50%的数据，满足 1≤ n≤10000，1≤m≤10000，1≤q≤10000； <br> 对于 100%的数据，满足 1≤ n≤10000，1≤m≤100000，1≤q≤10000；</p>
</div>
</div>