
# Description

<div class="content"><div>
<div>给定一个字符串S，它的下标从1开始。需要支持两种操作：</div>
<div>1 c在S最后插入一个字符c。</div>
<div>2 l r询问由S的第l位到第r位构成的字符串中，出现次数大于等于两次的字符串的长度的最大值。</div>
<div>我们会通过某些方法使你必须在线的支持操作。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行一个字符串，表示S。</div>
<div>第二行一个数m，表示操作次数。</div>
<div>接下来m行，每行表示一次操作。每种操作形如1 c或者2 l r。</div>
<div>设上次答案为lastans，当前字符串的长度为len。</div>
<div>如果为1c，那么真正插入的字符为(c-&#39;a&#39;+lastans)mod 26+&#39;a&#39;。</div>
<div>如果为2 l r，那么令l&#39;=((l-1+lastans) mod len)+1</div>
<div>r&#39;=((r-1+lastans) mod len)+1。</div>
<div>如果此时l&#39;&gt;r&#39;，则交换l&#39;和r&#39;。真正的询问区间即为l&#39;到r&#39;。</div>
<div>设字符串初始长度为N，N,M&lt;=50000，保证S中只有小写字符,1&lt;=L,R&lt;=Len</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>对于每个询问操作，输出一行一个数，表示答案。如果不存在一个满足条件的串，则输出0。</div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">aabda 6<br/>
2 1 4<br/>
1 a<br/>
2 1 5<br/>
1 b<br/>
2 6 5<br/>
2 7 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
3<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

