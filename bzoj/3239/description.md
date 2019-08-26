
# Description

<div class="content"><p><span style="font-size: medium">Given a prime P, 2 &lt;= P &lt; 2<sup>31</sup>, an integer B, 2 &lt;= B &lt; P, and an integer N, 2 &lt;= N &lt; P, compute the discrete logarithm of N, base B, modulo P. That is, find an integer L such that </span></p>
<pre><span style="font-size: medium">    B<sup>L</sup> == N (mod P)
</span></pre></div>

# Input

<div class="content"><p><span style="font-size: medium">Read several lines of input, each containing P,B,N separated by a space, </span></p></div>

# Output

<div class="content"><p><font size="4"> for each line print the logarithm on a separate line. If there are several, print the smallest; if there is none, print &#34;no solution&#34;. </font></p>
<p><span style="font-size: medium">The solution to this problem requires a well known result in number theory that is probably expected of you for Putnam but not ACM competitions. It is Fermat&#39;s theorem that states </span></p>
<pre><span style="font-size: medium">   B<sup>(P-1)</sup> == 1 (mod P)
</span></pre>
<p><span style="font-size: medium">for any prime P and some other (fairly rare) numbers known as base-B pseudoprimes. A rarer subset of the base-B pseudoprimes, known as Carmichael numbers, are pseudoprimes for every base between 2 and P-1. A corollary to Fermat&#39;s theorem is that for any m </span></p>
<pre><span style="font-size: medium">   B<sup>(-m)</sup> == B<sup>(P-1-m)</sup> (mod P) .
</span></pre></div>

# Sample Input

<div class="content"><span class="sampledata">5 2 1<br/>
5 2 2<br/>
5 2 3<br/>
5 2 4<br/>
5 3 1<br/>
5 3 2<br/>
5 3 3<br/>
5 3 4<br/>
5 4 1<br/>
5 4 2<br/>
5 4 3<br/>
5 4 4<br/>
12345701 2 1111111<br/>
1111111121 65537 1111111111<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1<br/>
3<br/>
2<br/>
0<br/>
3<br/>
1<br/>
2<br/>
0<br/>
no solution<br/>
no solution<br/>
1<br/>
9584351<br/>
462803587<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

