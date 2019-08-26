
# Description

<div class="content"><div>Why did the cow cross the road? We may never know the full reason, but it is certain that Farmer Joh</div>
<div>n&#39;s cows do end up crossing the road quite frequently. In fact, they end up crossing the road so oft</div>
<div>en that they often bump into each-other when their paths cross, a situation Farmer John would like t</div>
<div>o remedy.Farmer John raises N breeds of cows (1≤N≤100,000), and each of his fields is dedicated to</div>
<div> grazing for one specific breed; for example, a field dedicated to breed 12 can only be used for cow</div>
<div>s of breed 12 and not of any other breed. A long road runs through his farm. There is a sequence of </div>
<div>NN fields on one side of the road (one for each breed), and a sequence of N fields on the other side</div>
<div> of the road (also one for each breed). When a cow crosses the road, she therefore crosses between t</div>
<div>he two fields designated for her specific breed.Had Farmer John planned more carefully, he would hav</div>
<div>e ordered the fields by breed the same way on both sides of the road, so the two fields for each bre</div>
<div>ed would be directly across the road from each-other. This would have allowed cows to cross the road</div>
<div> without any cows from different breeds bumping into one-another. Alas, the orderings on both sides </div>
<div>of the road might be different, so Farmer John observes that there might be pairs of breeds that cro</div>
<div>ss. A pair of different breeds (a,b) is &#34;crossing&#34; if any path across the road for breed aa must int</div>
<div>ersect any path across the road for breed bb.Farmer John would like to minimize the number of crossi</div>
<div>ng pairs of breeds. For logistical reasons, he figures he can move cows around on one side of the ro</div>
<div>ad so the fields on that side undergo a &#34;cyclic shift&#34;. That is, for some 0≤k&lt;N, every cow re-locat</div>
<div>es to the field kk fields ahead of it, with the cows in the last kk fields moving so they now popula</div>
<div>te the first kk fields. For example, if the fields on one side of the road start out ordered by bree</div>
<div>d as 3, 7, 1, 2, 5, 4, 6 and undergo a cyclic shift by k=2, the new order will be 4, 6, 3, 7, 1, 2, </div>
<div>5. Please determine the minimum possible number of crossing pairs of breeds that can exist after an </div>
<div>appropriate cyclic shift of the fields on one side of the road.上下有两个位置分别对应的序列A、B，长度为n，</div>
<div>两序列为n的一个排列。当Ai == Bj时，上下会连一条边。</div>
<div>你可以选择序列A或者序列B进行旋转任意K步，</div>
<div>如 3 4 1 5 2 旋转两步为 5 2 3 4 1。</div>
<div>求旋转后最小的相交的线段的对数。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N. </div>
<div>The next N lines describe the order, by breed ID, of fields on one side of the road; </div>
<div>each breed ID is an integer in the range 1…N. </div>
<div>The last N lines describe the order, by breed ID, of the fields on the other side of the road.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Please output the minimum number of crossing pairs of breeds after a cyclic shift of the </div>
<div>fields on one side of the road (either side can be shifted).</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
5<br/>
4<br/>
1<br/>
3<br/>
2<br/>
1<br/>
3<br/>
2<br/>
5<br/>
4</span></div>

# Sample Output

<div class="content"><span class="sampledata">0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

