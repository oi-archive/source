
# Description

<div class="content"><div>
<div>Farmer John is preparing a delicious meal for his cows! In his barn, he has NN haybales (1≤N≤100,0</div>
<div>00). The iith haybale has a certain flavor Fi (1≤Fi≤10^9) and a certain spiciness Si(1≤Si≤10^9).</div>
<div>The meal will consist of a single course, being a contiguous interval containing one or more consecu</div>
<div>tive haybales (Farmer John cannot change the order of the haybales). The total flavor of the meal is</div>
<div> the sum of the flavors in the interval. The spiciness of the meal is the maximum spiciness of all h</div>
<div>aybales in the interval.Farmer John would like to determine the minimum spiciness his single-course </div>
<div>meal could achieve, given that it must have a total flavor of at least MM (1≤M≤10^18).</div>
<div>给长度为n&lt;=1e5的两个序列f[], s[] &lt;= 1e9和一个long long M。</div>
<div>如果[1, n] 的一个子区间[a, b]满足 f[a]+f[a+1]+..+f[b] &gt;= M， 我们就称[a, b]合法</div>
<div>，一个合法区间[a, b]的值为max(s[a], s[a+1], ..., s[b])。</div>
<div>让你求出可能的合法区间最小值为多少。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line contains the integers N and M, </div>
<div>the number of haybales and the minimum total flavor the meal must have, respectively. </div>
<div>The next N lines describe the N haybales with two integers per line, </div>
<div>first the flavor F and then the spiciness S.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Please output the minimum spiciness in a single course meal that satisfies the minimum flavor requirement. </div>
<div>There will always be at least one single-course meal that satisfies the flavor requirement.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 10<br/>
4 10<br/>
6 15<br/>
3 5<br/>
4 9<br/>
3 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

