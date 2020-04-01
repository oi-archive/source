
# Description

<div class="content"><div>Farmer John&#39;s nemesis, Farmer Nhoj, has NN cows (1≤N≤10^5), conveniently numbered 1…N. They have </div>
<div>unexpectedly turned up at Farmer John&#39;s farm, so the unfailingly polite Farmer John is attempting to</div>
<div> give them gifts.To this end, Farmer John has brought out his infinite supply of gifts, and Nhoj&#39;s c</div>
<div>ows have queued up in front of him, with cow 11 at the head of the queue and cow N at the tail. Farm</div>
<div>er John was expecting that at every timestep, the cow at the head of the queue would take a gift fro</div>
<div>m Farmer John and go to the tail of the queue. However, he has just realized that Nhoj&#39;s cows are no</div>
<div>t that polite! After receiving her gift, each cow may not go to the tail of the queue, but rather ma</div>
<div>y cut some number of cows at the tail, and insert herself in front of them. Specifically, cow ii wil</div>
<div>l always cut exactly cici cows (0≤ci≤N-1).Farmer John knows that some cows might receive multiple </div>
<div>gifts; as he has an infinite supply, this does not worry him. But he is worried that some cows might</div>
<div> become unhappy if they do not get any gifts.Help Farmer John find the number of cows who never rece</div>
<div>ive any gifts, no matter how many gifts are handed out.</div>
<div>
<div>有 N (1 &lt;= N &lt;= 10^5)头牛按顺序排成一列，编号从1到N，1 号牛在队头，N 号牛在队尾。每次位于队头的牛 i </div>
<div>拿到一个礼物，然后插入到从队尾数 c_i 头牛之前的位置。举个栗子： 初始队列 1 2 3 4 5， c_1 = 2，c_2 = </div>
<div>3，则第一次操作后的序列为 2 3 4 1 5，第二次操作后的序列为 3 2 4 1 5 。重复无限次操作，求最后有几头牛</div>
<div>拿不到礼物。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line contains a single integer, N.</div>
<div>The second line contains N space-separated integers c1,c2,…,cN</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Please output the number of cows who cannot receive any gifts.</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 2 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

