<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>JYY很喜欢打保龄球，虽然技术不高，但是还是总想着得高分。这里JYY将向你介绍他所参加的特殊保龄球比赛的规则，然后请你帮他得到尽量多的分数。 </p>
<p>一场保龄球比赛一共有N个轮次，每一轮都会有10个木瓶放置在木板道的另一端。每一轮中，选手都有两次投球的机会来尝试击倒全部的10个木瓶。对于每一次投球机会，选手投球的得分等于这一次投球所击倒的木瓶数量。选手每一轮的得分是他两次机会击倒全部木瓶的数量。 </p>
<p>对于每一个轮次，有如下三种情况： </p>
<p>1、“全中”：如果选手第一次尝试就击倒了全部10个木瓶，那么这一轮就称为“全中”。在一个“全中”轮中，由于所有木瓶在第一次尝试中都已经被击倒，所以选手不需要再进行第二次投球尝试。同时，在计算总分时，选手在下一轮的得分将会被乘2计入总分。 </p>
<p>2、“补中”：如果选手使用两次尝试击倒了10个木瓶，那么这一轮就称为“补中”。同时，在计算总分时，选手在下一轮中的第一次尝试的得分将会被乘以2计入总分。 </p>
<p>3、“失误”：如果选手未能通过两次尝试击倒全部的木瓶，那么这一轮就被称为“失误”。同时，在计算总分时，选手在下一轮的得分会被计入总分，没有分数被翻倍。 </p>
<p>此外，如果第N轮是“全中”，那么选手可以进行一次附加轮：也就是，如果第N轮是“全中”，那么选手将一共进行N+1轮比赛。显然，在这种情况下，第N+1轮的分数一定会被加倍。 </p>
<p>附加轮的规则只执行一次。也就是说，即使第N+1轮选手又打出了“全中”，也不会进行第N+2轮比赛。因而，附加轮的成绩不会使得其他轮的分数翻番。 </p>
<p>最后，选手的总得分就是附加轮规则执行过，并且分数按上述规则加倍后的每一轮分数之和。 </p>
<p>JYY刚刚进行了一场N个轮次的保龄球比赛，但是，JYY非常不满意他的得分。 </p>
<p>JYY想出了一个办法：他可以把记分表上，他所打出的所有轮次的顺序重新排列，这样重新排列之后，由于翻倍规则的存在，JYY就可以得到更高的分数了！ </p>
<p>当然了，JYY不希望做的太假，他希望保证重新排列之后，所需要进行的轮数和重排前所进行的轮数是一致的：比如如果重排前JYY在第N轮打出了“全中”，那么重排之后，第N轮还得是“全中”以保证比赛一共进行N+1轮；同样的，如果JYY第N轮没有打出“全中”，那么重排过后第N轮也不能是全中。 </p>
<p>请你帮助JYY计算一下，他可以得到的最高的分数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数N，表示保龄球比赛所需要进行的轮数。 </p>
<p>接下来包含N或者N+1行，第i行包含两个非负整数Xi 和 Yi  ，表示JYY在这一轮两次投球尝试所得到的分数，Xi  表示第一次尝试，Yi  表示第二次尝试。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出一行一个整数，表示JYY最大可能得到的分数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 </p>
<p>5 2 </p>
<p>10 0 </p>
<p>3 7 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>44</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据满足 N≤50。</p>
</div>
</div>