
# Description

<div class="content"><div>某个公司有n个人, 上下级关系构成了一个有根树。其中有个人是叛徒(这个人不知道是谁)。对于一个人, 如果他</div>
<div>下属(直接或者间接, 不包括他自己)中叛徒占的比例超过x，那么这个人也会变成叛徒，并且他的所有下属都会变</div>
<div>成叛徒。你要求出一个最小的x，使得最坏情况下，叛徒的个数不会超过k。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个正整数n,k(1&lt;=k&lt;=n&lt;=500000)。</div>
<div>接下来n-1行，第i行包含一个正整数p[i+1]，表示i+1的父亲是p[i+1](1&lt;=p[i+1]&lt;=i)。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个实数x，误差在10^-6以内都被认为是正确的。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">9 3<br/>
1<br/>
1<br/>
2<br/>
2<br/>
2<br/>
3<br/>
7<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.6666666667</span></div>

# Hint

<div class="content"><p></p><div>答案中的x实际上是一个无限趋近于2/3但是大于2/3的数</div><br/>
<div>因为当x取2/3时，最坏情况下3，7，8，9都是叛徒，超过了k=3。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传">鸣谢Claris上传</a></p></div>

