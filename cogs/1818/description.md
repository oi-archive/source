# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<div style="text-indent:21pt;">
<span style="font-size:medium;">传统的Nim游戏是这样的：有一些火柴堆，每堆都有若干根火柴（不同堆的火柴数量可以不同）。两个游戏者轮流操作，每次可以选一个火柴堆拿走若干根火柴。可以只拿一根，也可以拿走整堆火柴，但不能同时从超过一堆火柴中拿。拿走最后一根火柴的游戏者胜利。</span> 
</div>
<div style="text-indent:21pt;">
<span style="font-size:medium;">本题的游戏稍微有些不同：在第一个回合中，第一个游戏者可以直接拿走若干个整堆的火柴。可以一堆都不拿，但不可以全部拿走。第二回合也一样，第二个游戏者也有这样一次机会。从第三个回合（又轮到第一个游戏者）开始，规则和Nim游戏一样。</span> 
</div>
<div style="text-indent:21pt;">
<span style="font-size:medium;">如果你先拿，怎样才能保证获胜？如果可以获胜的话，还要让第一回合拿的火柴总数尽量小。</span> 
</div>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<div>
<span style="font-size:medium;">第一行为整数<i>k</i>。即火柴堆数。第二行包含<i>k</i>个不超过10<sup>9</sup>的正整数，即各堆的火柴个数。</span><span style="font-size:medium;"> </span> 
</div>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<div>
<span style="font-size:medium;">输出第一回合拿的火柴数目的最小值。如果不能保证取胜，输出-1。</span> 
</div>
</div>
<h3>
【样例输入】
</h3>
<pre>6
  5 5 6 6 5 5
  </pre>
<h3>
【样例输出】
</h3>
<pre>21</pre>
<h3>
【提示】
</h3>
<div class="content">
<p>
k&lt;=100
</p>
</div>
<h3>
【来源】
</h3>
<p>
CQOI 2013
</p>
