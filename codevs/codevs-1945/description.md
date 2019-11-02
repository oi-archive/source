<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农夫栋栋近年收入不景气，正在他发愁如何能多赚点钱时，他听到隔壁的小 朋友在讨论兔子繁殖的问题。 问题是这样的：第一个月初有一对刚出生的小兔子，经过两个月长大后，这 对兔子从第三个月开始，每个月初生一对小兔子。新出生的小兔子生长两个月后 又能每个月生出一对小兔子。问第 n 个月有多少只兔子？ 聪明的你可能已经发现，第 n 个月的兔子数正好是第 n 个 Fibonacci(斐波那 契)数。栋栋不懂什么是 Fibonacci 数，但他也发现了规律：第 i+2 个月的兔子数 等于第 i 个月的兔子数加上第 i+1 个月的兔子数。前几个月的兔子数依次为： 1 1 2 3 5 8 13 21 34 … 栋栋发现越到后面兔子数增长的越快，期待养兔子一定能赚大钱，于是栋栋 在第一个月初买了一对小兔子开始饲养。 每天，栋栋都要给兔子们喂食，兔子们吃食时非常特别，总是每 k 对兔子围 成一圈，最后剩下的不足 k 对的围成一圈，由于兔子特别害怕孤独，从第三个月 开始，如果吃食时围成某一个圈的只有一对兔子，这对兔子就会很快死掉。 我们假设死去的总是刚出生的兔子，那么每个月的兔子数仍然是可以计算的。 例如，当 k=7 时，前几个月的兔子数依次为： 1 1 2 3 5 7 12 19 31 49 80 … 给定 n，你能帮助栋栋计算第 n 个月他有多少对兔子么？由于答案可能非常 大，你只需要告诉栋栋第 n 个月的兔子对数除 p 的余数即可。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入一行，包含三个正整数 n, k, p。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行，包含一个整数，表示栋栋第 n 个月的兔子对数除 p 的余数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入 1】 <br>6 7 100 <br>【样例输入 2】 <br>7 75 <br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">【样例输出 1】</span><span style=""> </span></p>
<p>7 </p>
<p><span style="">【样例输出 2】 </span></p>
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
<p>1≤n≤10<sup>18</sup>， 2≤k≤10<sup>6</sup>，2≤p≤10<sup>9</sup></p>
</div>
</div>