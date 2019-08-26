
# Description

<div class="content"><div>Farmer John finds that his cows are each easier to milk when they have another cow nearby for moral </div>
<div>support. He therefore wants to take his Mcows (M≤1,000,000,000, M even) and partition them into M/2</div>
<div> pairs. Each pair of cows will then be ushered off to a separate stall in the barn for milking. The </div>
<div>milking in each of these M/2 stalls will take place simultaneously.To make matters a bit complicated</div>
<div>, each of Farmer John&#39;s cows has a different milk output. If cows of milk outputs Aand B are paired </div>
<div>up, then it takes a total of A+Bunits of time to milk them both.Please help Farmer John determine th</div>
<div>e minimum possible amount of time the entire milking process will take to complete, assuming he pair</div>
<div>s the cows up in the best possible way.</div>
<div></div>
<div>
<div>John有n种牛(n&lt;=100000)每种牛有数量x与时间y牛的总数为m要将m头牛分为m/2对，每对的时间花费为两牛时间之</div>
<div>和问最大的那对的最小值m&lt;=1e9 y&lt;=1e9</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N(1≤N≤100,000). Each of the next N lines contains two integers x </div>
<div>and y, indicating that FJ has x cows each with milk output y (1≤y≤1,000,000,000). The sum of the x</div>
<div>&#39;s is M, the total number of cows.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Print out the minimum amount of time it takes FJ&#39;s cows to be milked, assuming they are optimally </div>
<div>paired up.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 8<br/>
2 5<br/>
1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
Here, if the cows with outputs 8+2 are paired up, and those with outputs 5+5 are paired up, the both<br/>
 stalls take 10 units of time for milking. Since milking takes place simultaneously, the entire proc<br/>
ess would therefore complete after 10 units of time. Any other pairing would be sub-optimal, resulti<br/>
ng in a stall taking more than 10 units of time to milk.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

