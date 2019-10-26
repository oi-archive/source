
# Description

<div class="content"><p><span style="font-size: medium">I have a set of super poker cards, consisting of an infinite number of cards. For each positive composite integer p, there <br/>
are exactly four cards whose value is p: Spade(S), Heart(H), Club(C) and Diamond(D). There are no cards of other values.<br/>
By “composite integer”, we mean integers that have more than 2 divisors. For example, 6 is a composite integer, since it <br/>
has 4 divisors: 1, 2, 3, 6; 7 is not a composite number, since 7 only has 2 divisors: 1 and 7. Note that 1 is not composite <br/>
(it has only 1 divisor). <br/>
 <br/>
Given a positive integer n, how many ways can you pick up exactly one card from each suit (i.e. exactly one spade card, <br/>
one heart card, one club card and one diamond card), so that the card values sum to n? For example, if n=24, one way is <br/>
4S+6H+4C+10D, shown below:</span></p>
<p></p>
<p><span style="font-size: medium"><img alt="" src="/source/bzoj/2487/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMC8xMS5qcGc=.jpg"/></span></p>
<p></p>
<p></p>
<p><span style="font-size: medium">Unfortunately, some of the cards are lost, but this makes the problem more interesting. To further make the problem even <br/>
more interesting (and challenging!), I’ll give you two other positive integers a and b, and you need to find out all the <br/>
answers for n=a, n=a+1, …, n=b. </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">The input contains at most 25 test cases. Each test case begins with 3 integers a, b and c, where c is the number of lost <br/>
cards. The next line contains c strings, representing the lost cards. Each card is formatted as valueS, valueH, valueC or <br/>
valueD, where value is a composite integer. No two lost cards are the same. The input is terminated by a=b=c=0. There <br/>
will be at most one test case where a=1, b=50,000 and c&lt;=10,000. For other test cases, 1&lt;=a&lt;=b&lt;=100, 0&lt;=c&lt;=10. <br/>
 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">For each test case, print b-a+1 integers, one in each line. Since the numbers might be large, you should output each <br/>
integer modulo 1,000,000. Print a blank line after each test case. <br/>
 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">12 20 2 <br/>
4S 6H <br/>
0 0 0 </span></div>

# Sample Output

<div class="content"><span class="sampledata">0 <br/>
0 <br/>
0 <br/>
0 <br/>
0 <br/>
0 <br/>
1 <br/>
0 <br/>
3 </span></div>

# Hint

<div class="content"><p></p><p> 湖南省第七届大学生程序设计大赛</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢刘汝佳先生授权使用">鸣谢刘汝佳先生授权使用</a></p></div>

