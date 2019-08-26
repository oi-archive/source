
# Description

<div class="content"><div>给定一个含有n个数的序列a[1],a[2],a[3]……a[n]，程序必须回答这样的询问：对于给定的i,j,k，在a[i],a[i+1</div>
<div>],a[i+2]……a[j]中第k小的数是多少(1≤k≤j-i+1)，并且，你可以改变一些a[i]的值，改变后，程序还能针对改</div>
<div>变后的a继续回答上面的问题。</div></div>

# Input

<div class="content"><div>
<div>第一行有两个正整数n(1≤n≤10000)，m(1≤m≤10000)。</div>
<div>分别表示序列的长度和指令的个数。</div>
<div>第二行有n个数，表示a[1],a[2]……a[n]，这些数都小于10^9。</div>
<div>接下来的m行描述每条指令</div>
<div>每行的格式是下面两种格式中的一种。 </div>
<div>Q i j k 或者 C i t </div>
<div>Q i j k （i,j,k是数字，1≤i≤j≤n, 1≤k≤j-i+1）</div>
<div>表示询问指令，询问a[i]，a[i+1]……a[j]中第k小的数。</div>
<div>C i t (1≤i≤n，0≤t≤10^9)表示把a[i]改变成为t</div>
<div>m,n≤10000</div>
</div></div>

# Output

<div class="content"><p> 对于每一次询问，你都需要输出他的答案，每一个输出占单独的一行。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
3 2 1 4 7<br/>
Q 1 4 3<br/>
C 2 6<br/>
Q 2 5 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

