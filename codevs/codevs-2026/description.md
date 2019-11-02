<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    没头脑和不高兴是一对形影不离的好朋友，他们一起上学也一起玩耍。<br>    这天，这对好朋友聚在一起玩纸牌游戏。他们所玩的纸牌总共有N 张，每一张上面都有一个1 N 的数组，任意两张纸牌上的数字都不相同。根据他们制定的游戏规则，在每局游戏的开始，所有的牌需要按照从1 N 的顺序排好。在开心地完了一局牌之后，他们发现牌的顺序被弄得乱七八遭，将它们排好序是一件挺麻烦的事情。<br>    他们讲凌乱的纸牌在桌面上排成一排，然后开始了排序工作。不高兴由于在上一局游戏中输了牌，非常不高兴。他只将其中(奇数位置) 的牌排成了升序，然后把剩下的任务推给了没头脑。没头脑非常没头脑，他采取了一个有些笨的排序方式。每次，他找到两张相邻并且顺序不对的牌交换他们，直到整个序列被排好序为止。<br>    乐于探究的你，想要研究在初始排列随机的情况下没头脑花在交换纸牌上的时间。假设没头脑每交换一对纸牌花费的时间为1，你希望求出他排序时间的期望。此外，为了更好地分析这个问题，你还希望能够计算出所花时间的方差。更进一步地，如果(被不高兴排好序的位置发生了变化)，你是否还能求出没头脑用来排序的时间期望呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入文件共M + 1 行。<br>    第一行包含两个正整数N,M。<br>    接下来M 行，每行包含三个整数l,r,v。其中1≤l≤r≤N,v为0,1。若v = 0 则表示不高兴不再对l 到r 之间的位置排序；反之若v = 1 则表示被不高兴排序的位置将涵盖l 到r。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 输出文件共M + 2 行。每行输出一个形如p / q 的有理数，其中gcd(p,q) =1,q&ge; 1,p,q为自然数。<br />&nbsp; &nbsp; 第一行输出在初始条件下没头脑排序时间的期望。<br />&nbsp; &nbsp; 第二行输出在初始条件下没头脑排序时间的方差。<br />&nbsp; &nbsp; 接下来M行，每行分别输出在对不高兴排序的位置进行了前若干次修改之后没头脑排序时间的期望。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3<br>2 3 0<br>2 2 1<br>1 3 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2/3<br>2/9<br>3/2<br>1/1<br>0/1</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N≤100000,M≤10<sup>5</sup></p>
</div>
</div>