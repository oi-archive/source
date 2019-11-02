<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　<span>Rainbow和Freda终于走出了幻象迷宫，不过经历了汪星人的一场入侵，Freda的城堡和Rainbow的城堡之间的电话线路出了故障，使得只有满足某种要求的两个电话号码之间才可以直接通信。</span></p>
<p><span>　　<span>每台电话都有一个独一无二的号码，用一个十位的十进制数字串表示。电话a和b之间能直接通信，当且仅当“a与b之间仅有一个数字不同”，或者“交换a的某两位上的数字后，a与b相同”。而a、b之间建立通信联系所需要的时间为cost[ lcp(a,b) ]，其中cost[]是一个常数数组，lcp(a,b)表示a、b的最长公共前缀的长度，lcp(a,b)越大，通信时间越快。</span><br><span>　　另外，如果a、b能通信，b、c能通信，那么a、c也能借助b来通信。a、c借助b建立通信联系所用时间是cost[ lcp(a,b) ]+ cost[ lcp(b,c) ]。</span><br><span>　　现在Freda想给Rainbow打电话，请你告诉Freda，她最快需要多少时间才能与与Rainbow建立通信联系？</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行一个整数N，表示电话号码的个数。</p>
<p><span><span>　　第二行10个整数，第i个整数表示cost[i-1]，即当两个能够直接通信的号码的最长公共前缀为i-1时，二者之间建立通信联系所需的时间。</span><br><span>　　接下来N行每行一个整数表示电话号码。第一个是Freda的电话号码，第N个是Rainbow的电话号码。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　一个整数，表示所求时间。若Freda和Rainbow不能建立通信联系，输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>100 10 10 10 1 1 1 1 1 1<br>9123493342<br>3123493942<br>9223433942<br>3223493942<br>9223433945</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>211</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>　　对于 30% 的数据，2&lt;=N&lt;=100。<br>　　对于 50% 的数据，2&lt;=N&lt;=1000。<br>　　对于 70% 的数据，2&lt;=N&lt;=20000。<br>　　对于 100% 的数据，保证2&lt;=N&lt;=50000，每个电话号码是一个独一无二的十位十进制数字串，1&lt;=cost[0..9]&lt;=2^31-1。</p>
<p> </p>
<p>来源：Nescafe 23</p>
</div>
</div>