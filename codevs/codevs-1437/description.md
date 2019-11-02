<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>—30的用52张不考虑花色的游戏。人头牌（K，Q，J）的值是10，A的值是1，任何其他牌的值是它们的面值（如2，3，4等）。牌从牌堆的顶端发起，先发7张牌，从左至右形成七组，当给最右边一组发了一张牌后，下一张牌就应发最左边的一组。每个一组发一张牌时，查看这组牌以下的组合的总合是否为10，20，或者30。</p>
<p>前两张和最后一张，第一张和最后二张或最后三张。</p>
<p>如果是这样，就抽三张牌并将其放在牌堆的底部。对于这个问题，总是按上面给出的顺序查看牌。按牌在组中出现的顺序将它们取出来并放在牌堆的底部。当抽出三张牌时，又可能出现三张可以抽出的牌。如果是这样，再将它们抽出。如此重复直至再也不能从这组牌抽出符合条件的牌为止。</p>
<p>举例来说，假设有组牌含5，9，7，3。5是第一张牌，然后发出6。前两张牌加最后一张牌（5+9+6）等于20。抽出这三张牌后这组牌变成7，3。而牌堆的最底部变为6，6上面的一张牌是9，9上面的一张牌是5。</p>
<p> </p>
<p>如果发的不是6而是Q，那么5+9+10=24, 5+3+10=18,但7+3+10=20，因此最后三张牌可以抽走，剩下5，9。</p>
<p> </p>
<p> </p>
<p>如果有一组只有三张牌且这组牌的和为10，20或30，那么这组牌被抽走后就“消失”了。这就是说，随后的发牌将跳过现在成为空的这组牌的位置。当所有的牌组都消失，你就获胜。当你无牌可发时，你游戏失败。当前两种情况都不发生时，出现平局。</p>
<p> </p>
<p>任务：编写一个程序，将初始的牌堆作为输入，完成10—20—30游戏。</p>

<img src="/source/codevs/codevs-1437/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNDM3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2Mzk2NDk5NC42NjAuMDkwNjIxNjQzMDYwMy5qcGc=.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> 每组输入由52个整数组成，由空格和/或结束分开。整数表示初始牌堆的面值。第一个整数是牌堆的最顶端的牌。在最后一张牌后输入0标志输入结束。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对每组输入，输出游戏结果是胜，负还是平局，并输出游戏结果决定前所发的牌数。（假如游戏状态发生重复，意味着平局）使用&ldquo;输出样例&rdquo;部分的格式输出。</p>
<p class="p0">&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 6 5 10 10 4 10 10 10 4 5 10 4 5 10 9 7 6 1 7 6 9 5 3 10 10 4 10 9 2 1</p>
<p>10 1 10 10 10 3 10 9 8 10 8 7 1 2 8 6 7 3 3 8 2 </p>
<p>4 3 2 10 8 10 6 8 9 5 8 10 5 3 5 4 6 9 9 1 7 6 3 5 10 10 8 10 9 10 10 7</p>
<p>2 6 10 10 4 10 1 3 10 1 1 10 2 2 10 4 10 7 7 10</p>
<p>10 5 4 3 5 7 10 8 2 3 9 10 8 4 5 1 7 6 7 2 6 9 10 2 3 10 3 4 4 9 10 1 1</p>
<p>10 5 10 10 1 8 10 7 8 10 6 10 10 10 9 6 2 10 10</p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>win:66</p>
<p>lose:82</p>
<p>Draw:73</p>

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