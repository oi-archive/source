
# Description

<div class="content"><div><span style="font-size: medium">        考虑一个序列S1与另一个序列S2，如果满足下列条件，则两个序列等价：</span></div>
<div style="margin: 0cm 0cm 0pt 60pt; text-indent: -18pt"><span style="font-size: medium">1、 两个序列长度相等。</span></div>
<div style="margin: 0cm 0cm 0pt 60pt; text-indent: -18pt"><span style="font-size: medium">2、 设序列长度为len，对于任意的i,j(1&lt;=i,j&lt;=Len,i!=j)，若s1[i]&lt;s1[j]，则s2[i]&lt;s2[j]；若s1[i]&gt;s1[j]，则s2[i]&gt;s2[j]。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt"><span style="font-size: medium">现给出序列S和另外n个序列T1,T2,…Tn。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt"><span style="font-size: medium">位置i可行，当且仅当S[1..i]的某个后缀等价于T1…Tn中的某个序列。你需要输出所有可行i的值，按照升序输出。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">         数据有若干组，第一行一个数Test，表示数据组数。</span></div>
<div><span style="font-size: medium">         以下有Test组数据。</span></div>
<div><span style="font-size: medium">         对于每组数据，第一行一个整数m，表示序列的个数，其中，第一个序列表示序列S,以下m-1个序列表示T1,T2,…,Tn（m=n+1）。对于每个序列，第一行一个数表示其长度Len，第二行Len个数，表示这个序列。</span></div>
<div><span style="font-size: medium">         每组数据用一个空行隔开。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium"> </span></div>
<p>         对于每组数据，按升序输出可行的i值，一行一个数。<br/>
     每组数据之间不要加入多余空行。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata"> <br/>
         2<br/>
         2<br/>
         1<br/>
         1<br/>
         1<br/>
         2<br/>
 <br/>
         3<br/>
         3<br/>
         3 1 2<br/>
         2<br/>
         4 5<br/>
         2<br/>
         10 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
3<br/>
<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
数据范围：<br/><br/>
         S的长度小于400000，m&gt;1，T的总长度小于100000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

