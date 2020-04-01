
# Description

<div class="content"><div>有n个连续函数fi(x)，其中1≤i≤n。对于任何两个函数fi(x)和fj(x),(i!=j)，恰好存在一个x使得fi(x)=fj(x)，</div>
<div>并且存在无穷多的x使得fi(x)&lt;fj(x)。对于任何i;j;k，满足1≤i&lt;j&lt;k≤n，则不存在x使得fi(x)=fj(x)=fk(x)。</div>
<div><img src="/source/bzoj/1432/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8xKDgpLnBuZw==.png" width="435" height="179" alt=""/></div>
<div>如上左图就是3个满足条件的函数，最左边从下往上依次为f1;f2;f3。右图中红色部分是这整个函数图像的最低层</div>
<div>，我们称它为第一层。同理绿色部分称为第二层，蓝色部分称为第三层。注意到，右图中第一层左边一段属于f1，</div>
<div>中间属于f2，最后属于f3。而第二层左边属于f2，接下来一段属于f1，再接下来一段属于f3，最后属于f2。因此，</div>
<div>我们称第一层分为了三段，第二层分为了四段。同理第三层只分为了两段。求满足前面条件的n个函数，第k层最少</div>
<div>能由多少段组成。</div></div>

# Input

<div class="content"><p>一行两个整数n; k。1 ≤ k ≤ n ≤ 100。</p></div>

# Output

<div class="content"><p>一行一个整数，表示n 个函数第k 层最少能由多少段组成。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

