
# Description

<div class="content"><div>
<div>Bessie and Elsie have each baked N pies (1≤N≤10^5). Each of the 2N pies has a tastiness value acco</div>
<div>rding to Bessie and a (possibly different) tastiness value according to Elsie.Bessie is thinking abo</div>
<div>ut giving one of her pies to Elsie. If Elsie receives a pie from Bessie, she will feel obligated to </div>
<div>give one of her pies to Bessie. So as to not appear stingy nor flamboyant, Elsie will try to pick a </div>
<div>pie that is at least as tasty (in Elsie&#39;s eyes) as the pie she received, but no more than D units ta</div>
<div>stier (0≤D≤10^9). Such a pie may not exist, in which case Elsie will adopt a pseudonym and exile h</div>
<div>erself to Japan.But if Elsie does give Bessie a pie in return, Bessie will similarly try to give Els</div>
<div>ie a pie which is at least as tasty but no more than DD units tastier (in Bessie&#39;s eyes) as the pie </div>
<div>Elsie just gave her. Should this be impossible, Bessie too will exile herself. Otherwise she will gi</div>
<div>ve her chosen pie to Elsie. This cycle will continue until one of the cows is exiled, an unhappy out</div>
<div>come, or one of the cows receives a pie which she accords a tastiness value of 0, in which case the </div>
<div>gift exchange will end and both cows will be happy.Note that a pie may not be gifted twice, nor can </div>
<div>either cow return a pie gifted to her.For each of the NN pies Bessie could select as her initial gif</div>
<div>t to Elsie, determine the minimum number of pies that could possibly be gifted in the resulting exch</div>
<div>ange before the cows are happy.</div>
<div>两只牛，牛A和牛B，他们对水果派的品味不同，每个人都有n&lt;=1e5个派，每个派都有两种得分a[i], b[i]，其中a[</div>
<div>i]是牛A对该派的评分，b[i]是牛B的评分, 0 &lt;= a[i], b[i] &lt;= 1e9。两只牛开始礼尚往来，从牛A开始，它选一</div>
<div>个pie给牛B，设这个pie的评分是(a[i], b[i])。此时牛B为了不失礼节（不太小气，也不要太谄媚）要选出一个B</div>
<div>评分在[b[i], b[i]+d]范围内的pie(a[j], b[j])，给A。同理，A又要选出一个A评分在[a[j], a[j]+d]范围内的pi</div>
<div>e给B，如此往复。每个pie都只能传递一次。如果A收到了一个A评分为0的pie，或者B收到了一个B评分为0的pie，</div>
<div>那么礼尚往来就愉快的结束了。否则，就不愉快结束（即一个人无法选出合法的pie给对方时）。下面让你输出，</div>
<div>对于A的每一个pie，如果第一轮A把这个pie交给B，礼尚往来最少可以几轮愉快结束？如果无法愉快结束，就输出-1</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line contains the two integers N and D.</div>
<div>The next 2N lines contain two space-separated integers each, </div>
<div>respectively denoting the value of a particular pie according to Bessie, and the value of that pie according to Elsie.</div>
<div>The first N lines refer to Bessie&#39;s pies, and the remaining N lines refer to Elsie&#39;s pies.</div>
<div>It is guaranteed that all tastiness values are in the range [0,10^9]</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>There should be N lines in the output. </div>
<div>Line i should contain a single integer: the minimum number of pies that could be gifted in a happy gift </div>
<div>exchange started with Bessie&#39;s pie i. </div>
<div>If no gift exchange starting with pie i is happy, then line i should contain the single integer -1 instead.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
1 1<br/>
5 0<br/>
4 2<br/>
1 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

