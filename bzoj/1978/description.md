
# Description

<div class="content">小 C 刚学了辗转相除法，正不亦乐乎，这小 P 又出来捣乱，给小 C 留了个
难题。 
给 N 个数，用 a1,a2…an来表示。现在小 P 让小 C 依次取数，第一个数可以
随意取。假使目前取得 aj，下一个数取ak(k&gt;j)，则ak必须满足gcd(aj,ak)≥L。 
到底要取多少个数呢？自然是越多越好！ 
不用多说，这不仅是给小 C 的难题，也是给你的难题。 </div>

# Input

<div class="content">第一行包含两个数N 和 L。 
接下来一行，有 N 个数用空格隔开，依次是 a1,a2…an。 </div>

# Output

<div class="content">仅包含一行一个数，表示按上述取法，最多可以取的数的个数。 </div>

# Sample Input

<div class="content"><span class="sampledata">5 6 <br/>
7 16 9 24 6 </span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p>选取 3个数16、24、6。gcd(16,24)=8，gcd(24,6)=6。 <br/>
<br/>
  2≤L≤ai≤1 000 000； <br/>
  30% 的数据N≤1000； <br/>
  100% 的数据  N≤50 000</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

