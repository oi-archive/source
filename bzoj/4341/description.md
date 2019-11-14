
# Description

<div class="content"><div>我们考虑一个有这样功能的网络打印机：他从时刻0开始工作，每一</div>
<div>秒钟他打印一页纸。某些时刻他会收到一些打印任务。我们知道打印机会</div>
<div>收到n个任务，我们将它们分别编号为连续的整数1∼n，并且第i个任</div>
<div>务用三个参数描述：ti表示接到的时间，si表示任务要求你打印多少张，</div>
<div>以及pi表示任务的一个优先级。所有任务的优先级互不相同。当一个打印</div>
<div>机收到一个任务时，任务会进入一个队列并留下直到完成了这个任务为止。</div>
<div>在任务队列非空时，每个时刻，打印机会选择队列里优先级最高的一个任</div>
<div>务，打印一页。你可以想象任务进入队列是瞬间的事情，所以他可以在收</div>
<div>到某个任务的时刻去执行这个任务。</div>
<div>你会得到除了某个任务以外所有任务的信息：你不知道某个任务的优</div>
<div>先级是多少。然而，我们还额外的知道这个任务他完成时的时刻。我们给</div>
<div>你这些信息，请求出这个未知的优先级并对每个任务输出它完成时的时刻。</div>
<p></p></div>

# Input

<div class="content"><div>第一行输入一个整数n(1≤n≤50000)。接下来n行描述一个任务。</div>
<div>第i行有三个整数分别是ti;si;pi(0≤ti≤10^9;1≤si;pi≤10^9)。有且仅有</div>
<div>一个任务（我们不妨称其为任务x)，满足px=−1。所有的优先级互不相</div>
<div>同，最后一行包含一个整数T——任务x完成的时刻,1≤T≤10^15。ti并</div>
<div>不一定互不相同。这个x可以是输入的任意一个任务。</div>
<p></p></div>

# Output

<div class="content"><div>在第一行输出一个整数px——即任务x的优先级（要求1≤px,并请</div>
<div>记住所有任务的优先级必须互不相同）。接下来输出n个数字，第i个数字</div>
<div>表示第i个任务结束时的时间。</div>
<div>我们保证数据有解。如果有多解，输出任意一组解即可。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
4 3 -1<br/>
0 2 2<br/>
1 3 3<br/>
7</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
7 8 4</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris提供SPJ">鸣谢Claris提供SPJ</a></p></div>

