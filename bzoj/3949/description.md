
# Description

<div class="content"><div>
<div>买菜否开了一家店，号称“一切皆可买”，生意红火。这天crx看到店里面有一个很长的置换A，它的形式非常优美</div>
<div>，如果把它表示成排列(a1, a2, ..., an)，对于所有i都满足ai=i%n+1。crx被深深地吸引了，但他买不起这个置</div>
<div>换。好在仁慈的买菜否表示，只要crx能求出A的特征值，就让crx低价买下这个置换。买菜否把置换A的特征值定义</div>
<div>为置换A能生成的所有不同置换的循环数之和。由于特征值可能很大，只需要求出它模10^9+7的余数。crx知道，置</div>
<div>换A能生成的置换是若干个A合成的置换，置换A的循环数是将置换A分解为循环的乘积后循环的个数，如果有多种分</div>
<div>解方法则选择最小的循环个数。于是crx马上算了起来，过了半小时终于求出了答案。但是买菜否说：“刚才我等</div>
<div>你算答案等得太无聊了，就交换了置换中的两个数，现在你要算新的置换的特征值。”crx只好重新算了起来，但</div>
<div>是他算了没多久就发现买菜否又无聊地交换了置换中的两个数。crx明白自己计算的速度根本赶不上买菜否交换的</div>
<div>速度，他只能记录下买菜否的q次操作，请你来求出每次操作后置换的特征值。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>输入的第一行包含两个整数n, q，分别表示置换的长度和操作次数。接下来q行，第i+1行包含两个整数x，y(x!=y)</div>
<div>，表示第i次交换了数x和数y。</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出q行，第i行包含一个整数，表示第i次操作后置换的特征值。</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2<br/>
4 3<br/>
1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
8<br/>
</span></div>

# Hint

<div class="content"><p></p><div>样例说明</div><br/>
<div>第一次交换后，置换变为2431。它能生成的置换有2431,4132和1234。</div><br/>
<div>2431可以分解为循环124和3，循环数为2。4132可以分解为循环142和3，循环数为2。1234可以分解为循环1,2,3和4，循环数为4。它们的循环数之和为8。</div><br/>
<div>N&lt;=10^8,Q&lt;=10^5</div><br/>
<div>尚无数据，请不要提交！求此题数据。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2014年国家集训队十五人互测">2014年国家集训队十五人互测</a></p></div>

