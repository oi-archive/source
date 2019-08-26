
# Description

<div class="content"><p><span style="font-size: medium"> Farmer John&#39;s N cows (2 &lt;= N &lt;= 500) have joined the social network &#34;MooBook&#34;. Each cow has one or more friends with whom they interact on MooBook. Just for fun, Farmer John makes a list of the number of friends for each of his cows, but during the process of writing the list he becomes distracted, and he includes one extra number by mistake (so his list contains N+1 numbers, instead of N numbers as he intended). Please help Farmer John figure out which numbers on his list could have been the erroneous extra number. </span></p>
<p><span style="font-family: arial, verdana, sans-serif; font-size: 14px; line-height: 23px; ">农夫约翰又有n(1&lt;=n&lt;=500)头奶牛想参加社会活动了……它们每个都有一个或一个以上的朋友。约翰弄了个表记录每头牛的朋友数，但由于他傻屌了多写了一个乱七八糟的数字（于是现在有n+1个数字了）</span></p>
<div style="font-family: arial, verdana, sans-serif; font-size: 14px; line-height: 23px; ">请你帮助他指出哪个数字是错误的</div>
<div style="font-family: arial, verdana, sans-serif; font-size: 14px; line-height: 23px; "></div></div>

# Input

<div class="content"><p><font size="4">* Line 1: The integer N. * Lines 2..2+N: Line i+1 contains the number of friends for one of FJ&#39;s cows, or possibly the extra erroneous number. </font></p>
<p><span style="font-family: arial, verdana, sans-serif; font-size: 14px; line-height: 23px; ">第一行一个整数n</span></p>
<div style="font-family: arial, verdana, sans-serif; font-size: 14px; line-height: 23px; ">第2~n+2行，每行一个整数表示一头牛的朋友数……当然这当中混杂了那个错误数字</div>
<div style="font-family: arial, verdana, sans-serif; font-size: 14px; line-height: 23px; "></div></div>

# Output

<div class="content"><p><span style="font-size: medium; ">* Line 1: An integer K giving the number of entries in FJ&#39;s list that could be the extra number (or, K=0 means that there is no number on the list whose removal yields a feasible pairing of friends). </span></p>
<p><span style="font-size: medium; ">* Lines 2..1+K: Each line contains the index (1..N+1) within the input ordering of a number of FJ&#39;s list that could potentially be the extra number -- that is, a number that can be removed such that the remaining N numbers admit a feasible set of friendships among the cows. These lines should be in sorted order. </span></p>
<p><span style="font-size: medium; ">第一行一个整数K表示表里有几个数字有可能是那个错误数字（如果k=0就说明每个数字都不可能是）</span></p>
<p><span style="font-size: medium; ">第2~k+1行每行一个整数，表示将错误数字从小到大排序后输出</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 <br/>
1 <br/>
2 <br/>
2 <br/>
1 <br/>
3 <br/>
<br/>
输入解释：约翰有4头奶牛，表上说有两头奶牛有一个朋友，两头奶牛有两个朋友，一头奶牛有三个朋友，当然，这些数字中有一个数字是约翰逗逼了写上去了<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 <br/>
1 <br/>
4 <br/>
5 <br/>
<br/>
OUTPUT DETAILS: Removal of the first number in FJ&#39;s list (the number 1) gives a remaining list of 2,2,1,3, which does lead to a feasible friendship pairing -- for example, if we name the cows A..D, then the pairings (A,B), (A,C), (A,D), and (B,C) suffice, since A has 3 friends, B and C have 2 friends, and D has 1 friend. Similarly, removing the other &#34;1&#34; from FJ&#39;s list also works, and so does removing the &#34;3&#34; from FJ&#39;s list. Removal of either &#34;2&#34; from FJ&#39;s list does not work -- we can see this by the fact that the sum of the remaining numbers is odd, which clearly prohibits us from finding a feasible pairing. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold 译文BY Ydc">Gold 译文BY Ydc</a></p></div>

