
# Description

<div class="content"><p><span style="font-size: medium">Farmer John&#39;s cows have discovered that the clover growing along the ridge of the hill in his field is particularly good. To keep the clover watered, Farmer John is installing water sprinklers along the ridge of the hill. To make installation easier, each sprinkler head must be installed along the ridge of the hill (which we can think of as a one-dimensional number line of length L (1 &lt;= L &lt;= 1,000,000); L is even). Each sprinkler waters the ground along the ridge for some distance in both directions. Each spray radius is an integer in the range A..B (1 &lt;= A &lt;= B &lt;= 1000). Farmer John needs to water the entire ridge in a manner that covers each location on the ridge by exactly one sprinkler head. Furthermore, FJ will not water past the end of the ridge in either direction. Each of Farmer John&#39;s N (1 &lt;= N &lt;= 1000) cows has a range of clover that she particularly likes (these ranges might overlap). The ranges are defined by a closed interval (S,E). Each of the cow&#39;s preferred ranges must be watered by a single sprinkler, which might or might not spray beyond the given range. Find the minimum number of sprinklers required to water the entire ridge without overlap. </span></p>
<p></p>
<div><span style="font-size: medium">    约翰的奶牛们发现山督上的草特别美味．为了维持草的生长，约翰打算安装若干喷灌器．为简化问题，山脊可以看成一维的数轴，长为L(1≤L≤10^6)，而且L-定是一个偶数．每个喷灌器可以双向喷灌，并有确定的射程，该射程不短于A，不长于B，A，B(1≤A≤B≤103)都是给出的正整数．它所在位置的两边射程内，都属它的灌溉区域．现要求山脊的每一个区域都被灌溉到，而且喷灌器的灌溉区域不允许重叠， 约翰有N(1≤N≤10^3)只奶牛，每一只都有特别喜爱的草区，第i奶牛的草区是[Si，Ei]，不同奶牛的草区可以重叠．现要求，每只奶牛的草区仅被一个喷灌器灌溉． 寻找最少需要的喷灌器数目．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers: N and L * Line 2: Two space-separated integers: A and B * Lines 3..N+2: Each line contains two integers, S and E (0 &lt;= S &lt; E &lt;= L) specifying the start end location respectively of a range preferred by some cow. Locations are given as distance from the start of the ridge and so are in the range 0..L. </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: The minimum number of sprinklers required. If it is not possible to design a sprinkler head configuration for Farmer John, output -1. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 8<br/>
1 2<br/>
6 7<br/>
3 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="180" alt="" width="707" src="/source/bzoj/1986/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8yMigzKS5qcGc=.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search= Gold"> Gold</a></p></div>

