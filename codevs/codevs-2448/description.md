<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>为了救出心爱的公主Julie，Billy来到了恶魔的城堡。经过了三天三夜的浴血奋战，魔王殿已近在咫尺。</p>
<p>这是一条狭长的通道，Billy在位置0，而魔王殿在位置n+1。在每个单位时间，Billy可以往左或往右移动一个单位，或者原地不动。每个格子的上方都有石头<strong><span style="text-decoration: underline;">周期性</span></strong>的往下砸，格子i的周期为c<sub>i</sub>。对于格子i上方的石头，可以用c<sub>i</sub>个整数来描述：h[1], h[2], …, h[c<sub>i</sub>]，表示在时间t=kc<sub>i</sub>+x（1&lt;=x&lt;=c<sub>i</sub>）时处于该格子上将被砸掉h[x]格血。其中h[x]=0表示该时刻没有石头砸下来。</p>
<p>计算Billy最少损失多少格血后可以到达魔王殿。假设Billy是不会死的。注意从位置1也是可以回到位置0的，且在位置0不损血。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包括一个整数n，表示通道的长度。以下n行，依次表示格子1, 2, 3, …, n的情况。每行第一个整数为c<sub>i</sub>(1&lt;=c<sub>i</sub>&lt;=10)，表示石头下落周期，接下来有c<sub>i</sub>个整数，分别为h[1], h[2], ..., h[c<sub>i</sub>]。(0&lt;=h[x]&lt;=100)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个整数HP，表示血的最小损失。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>2 1 0</p>
<p>2 0 1</p>
<p>1 2</p>
<p>7 0 1 1 1 1 1 1</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据满足：0&lt;=n&lt;=20</p>
<p>100%的数据满足：0&lt;=n&lt;=1000</p>
</div>
</div>