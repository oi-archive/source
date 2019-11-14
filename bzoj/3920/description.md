
# Description

<div class="content"><div>转眼就要到Karin的生日了！Yuuna她们想为她准备生日礼物！现在有许多礼物被排列成了一个一维序列，每个礼物都有一个价值。Yuuna对这个序列十分感兴趣。因此，你需要多次回答：在某个区间内出现次数第k1少的价值是多少，可能多个不同的价值出现次数均为第k1少，输出其中第k2小的，保证输入合法。注意内存限制。</div>
<div>
<div>例如：对于一个区间而言(当然不一定是有序的):</div>
<div>1,2,3,4,5,5,6,6,7,7,7,7,8,8,8,8,9,9,9,9,10,10,10,10,11,11,11,11,11,11,12,12,12,12,12,12,12,12,12,12</div>
<div>权值<span class="Apple-tab-span" style="white-space:pre">	</span>出现次数<span class="Apple-tab-span" style="white-space:pre">	</span></div>
<div>1<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>出现次数第1少<span class="Apple-tab-span" style="white-space:pre">	</span>第1小</div>
<div>2<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">		</span>第2小</div>
<div>3<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">		</span>第3小</div>
<div>4<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">		</span>第4小</div>
<div>5<span class="Apple-tab-span" style="white-space:pre">	</span>2<span class="Apple-tab-span" style="white-space:pre">	</span>出现次数第2少<span class="Apple-tab-span" style="white-space:pre">	</span>第1小</div>
<div>6<span class="Apple-tab-span" style="white-space:pre">	</span>2<span class="Apple-tab-span" style="white-space:pre">		</span>第2小</div>
<div>7<span class="Apple-tab-span" style="white-space:pre">	</span>4<span class="Apple-tab-span" style="white-space:pre">	</span>出现次数第3少<span class="Apple-tab-span" style="white-space:pre">	</span>第1小</div>
<div>8<span class="Apple-tab-span" style="white-space:pre">	</span>4<span class="Apple-tab-span" style="white-space:pre">		</span>第2小</div>
<div>9<span class="Apple-tab-span" style="white-space:pre">	</span>4<span class="Apple-tab-span" style="white-space:pre">		</span>第3小</div>
<div>10<span class="Apple-tab-span" style="white-space:pre">	</span>4<span class="Apple-tab-span" style="white-space:pre">		</span>第4小</div>
<div>11<span class="Apple-tab-span" style="white-space:pre">	</span>6<span class="Apple-tab-span" style="white-space:pre">	</span>出现次数第4少<span class="Apple-tab-span" style="white-space:pre">	</span>第1小</div>
<div>12<span class="Apple-tab-span" style="white-space:pre">	</span>10<span class="Apple-tab-span" style="white-space:pre">	</span>出现次数第5少<span class="Apple-tab-span" style="white-space:pre">	</span>第1小</div>
<div>若k1=3，k2=2，代表询问这个区间里出现次数第3少的权值中第2小的，则应该输出8。</div>
<div>若k1=5，k2=1，代表询问这个区间里出现次数第5少的权值中第1小的，则应该输出12。</div>
<div>若k1=1，k2=3，代表询问这个区间里出现次数第1少的权值中第3小的，则应该输出3。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行包括一个整数n，代表序列的长度。</div>
<div>第二行包括n个整数a1...an，代表该序列。</div>
<div>第三行包括一个整数m，代表询问的次数。</div>
<div>接下来m行，每行包括4个整数l，r，k1，k2，询问al...ar中出现次数第k1少的权值中第k2小的。</div>
<p></p></div>

# Output

<div class="content"><div>
<div>对于每个询问，仅输出一行，包括一个整数，代表你的回答。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">【输入样例1】<br/>
10<br/>
3 6 6 8 3 10 1 6 5 6<br/>
10<br/>
4 7 1 2<br/>
5 7 1 1<br/>
5 6 1 2<br/>
2 6 2 1<br/>
8 9 1 1<br/>
6 9 1 2<br/>
1 2 1 1<br/>
1 4 2 1<br/>
5 7 1 3<br/>
2 6 1 3<br/>
<br/>
【输入样例2】<br/>
20<br/>
14 18 19 11 15 13 9 10 5 13 3 14 14 12 12 8 4 17 8 8<br/>
20<br/>
8 9 1 2<br/>
6 19 2 2<br/>
7 11 1 1<br/>
8 12 1 4<br/>
9 13 2 1<br/>
14 15 1 1<br/>
6 11 1 4<br/>
5 7 1 3<br/>
8 18 2 1<br/>
2 4 1 3<br/>
4 16 1 1<br/>
5 14 1 5<br/>
13 14 1 2<br/>
15 15 1 1<br/>
12 17 1 1<br/>
3 12 2 1<br/>
14 17 1 1<br/>
6 13 1 4<br/>
11 11 1 1<br/>
2 4 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">【输出样例1】<br/>
3<br/>
1<br/>
10<br/>
6<br/>
5<br/>
5<br/>
3<br/>
6<br/>
10<br/>
10<br/>
<br/>
【输出样例2】<br/>
10<br/>
12<br/>
3<br/>
13<br/>
14<br/>
12<br/>
10<br/>
15<br/>
12<br/>
19<br/>
3<br/>
12<br/>
14<br/>
12<br/>
4<br/>
13<br/>
4<br/>
10<br/>
3<br/>
19</span></div>

# Hint

<div class="content"><p></p><div>【数据范围】</div><br/>
<div>1&lt;=n&lt;=40000，</div><br/>
<div>1&lt;=ai&lt;=n<span class="Apple-tab-span" style="white-space:pre">	</span>(1&lt;=i&lt;=n)，</div><br/>
<div>1&lt;=m&lt;=40000，</div><br/>
<div>1&lt;=l&lt;=r&lt;=n，</div><br/>
<div>保证k1,k2合法。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

