
# Description

<div class="content"><p>定义集合S的价值D(S)为：</p>
<p><img src="/source/bzoj/4078/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNi8yMi5KUEc=.JPG" width="307" height="85" alt=""/></p>
<div> </div>
<div>
<div>现在给你n个元素，并给出其中任意两个元素之间的d(i,j)值</div>
<div>要你将这些元素划分成两个集合A、B。</div>
<div>求min{D(A)+D(B)}。</div>
<div>注：d(i,j)=d(j,i)。</div>
</div></div>

# Input

<div class="content"><div>输入数据的第一行是一个整数n，代表元素个数。</div>
<div>之后n-1行描述的是d(i,j)，第i行包含n-i个整数，第i行第j列的整数代表的是d(i,i+j)。</div>
<div>0&lt;=wi&lt;=10^9</div>
<div></div>
<div></div></div>

# Output

<div class="content"><p> 输出只有一行，一个整数，代表min{D(A)+D(B)}。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
4 5 0 2<br/>
1 3 7<br/>
2 0<br/>
4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢qpswwww提供译文">鸣谢qpswwww提供译文</a></p></div>

