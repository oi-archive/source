
# Description

<div class="content"><div>In the Byteotian Line Forest there are   trees in a row. On top of the first one, there is a little bird who would like to fly over to the top of the last tree. Being in fact very little, the bird might lack the strength to fly there without any stop. If the bird is sitting on top of the tree no.  , then in a single flight leg it can fly to any of the trees no.i+1,i+2…I+K, and then has to rest afterward.</div>
<div>Moreover, flying up is far harder to flying down. A flight leg is tiresome if it ends in a tree at least as high as the one where is started. Otherwise the flight leg is not tiresome.</div>
<div>The goal is to select the trees on which the little bird will land so that the overall flight is least tiresome, i.e., it has the minimum number of tiresome legs. We note that birds are social creatures, and our bird has a few bird-friends who would also like to get from the first tree to the last one. The stamina of all the birds varies, so the bird&#39;s friends may have different values of the parameter  . Help all the birds, little and big!</div>
<div><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">有一排n棵树，第i棵树的高度是Di。</span></div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">MHY要从第一棵树到第n棵树去找他的妹子玩。</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">如果MHY在第i棵树，那么他可以跳到第i+1,i+2,...,i+k棵树。</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">如果MHY跳到一棵不矮于当前树的树，那么他的劳累值会+1，否则不会。</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">为了有体力和妹子玩，MHY要最小化劳累值。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>There is a single integer N(2&lt;=N&lt;=1 000 000) in the first line of the standard input: the number of trees in the Byteotian Line Forest. The second line of input holds   integers D1,D2…Dn(1&lt;=Di&lt;=10^9) separated by single spaces: Di is the height of the i-th tree.</div>
<div>The third line of the input holds a single integer Q(1&lt;=Q&lt;=25): the number of birds whose flights need to be planned. The following Q lines describe these birds: in the i-th of these lines, there is an integer Ki(1&lt;=Ki&lt;=N-1) specifying the i-th bird&#39;s stamina. In other words, the maximum number of trees that the i-th bird can pass before it has to rest is Ki-1.</div>
<p></p></div>

# Output

<div class="content"><div>Your program should print exactly Q lines to the standard output. In the I-th line, it should specify the minimum number of tiresome flight legs of the i-th bird.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
4 6 3 6 3 7 2 6 5<br/>
2<br/>
2<br/>
5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p><div>Explanation: The first bird may stop at the trees no. 1, 3, 5, 7, 8, 9. Its tiresome flight legs will be the one from the 3-rd tree to the 5-th one and from the 7-th to the 8-th.</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢zhonghaoxi">鸣谢zhonghaoxi</a></p></div>

