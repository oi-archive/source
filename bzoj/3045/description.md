
# Description

<div class="content"><p><span style="font-size: medium">Rainbow和Freda终于走出了幻象迷宫，不过经历了汪星人的一场入侵，Freda的城堡和Rainbow的城堡之间的电话线路出了故障，使得只有满足某种要求的两个电话号码之间才可以直接通信。<br/>
每台电话都有一个独一无二的号码，用一个十位的十进制数字串表示。电话a和b之间能直接通信，当且仅当“a与b之间仅有一个数字不同”，或者“交换a的某两位上的数字后，a与b相同”。而a、b之间建立通信联系所需要的时间为cost[ lcp(a,b) ]，其中lcp(a,b)表示a、b的最长公共前缀的长度，lcp(a,b)越大，通信时间越快，cost[]是个常数数组。<br/>
另外，如果a、b能通信，b、c能通信，那么a、c也能借助b来通信。a、c借助b建立通信联系所用时间是cost[ lcp(a,b) ]+ cost[ lcp(b,c) ]。<br/>
现在Freda想给Rainbow打电话，请你告诉Freda，她最快需要多少时间才能与与Rainbow建立通信联系？</span></p></div>

# Input

<div class="content"><p><br/>
<font size="4">第一行一个整数N，表示电话号码的个数。<br/>
第二行10个整数，第i个整数表示cost[i-1]，即当两个能够直接通信的号码的最长公共前缀为i-1时，二者之间建立通信联系所需的时间。<br/>
接下来N行每行一个整数表示电话号码。第一个是Freda的电话号码，第N个是Rainbow的电话号码。</font></p></div>

# Output

<div class="content"><p> </p>
<p><span style="font-size: medium">一个整数，表示所求时间。若Freda和Rainbow不能建立通信联系，输出-1。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
5<br/>
100 10 10 10 1 1 1 1 1 1<br/>
9123493342<br/>
3123493942<br/>
9223433942<br/>
3223493942<br/>
9223433945<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
211<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于 100% 的数据，保证2&lt;=N&lt;=50000，每个电话号码是一个独一无二的十位十进制数字串，1&lt;=cost[1..10]&lt;=1000。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Poetize7">Poetize7</a></p></div>

