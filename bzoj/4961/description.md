
# Description

<div class="content"><div>我们定义一种操作是将一个正整数n(n&gt;1)用某个整数d替换，这个数必须是n的约数(1≤d≤n)。给你一个正整数n，</div>
<div>你需要确定操作进行的期望次数，如果我们希望不断地使用这种操作来将n变成1，假设每次操作选择每个可能的d</div>
<div>的概率均等。为了便于计算，输入将给出n和它的所有不同质因数p_1,p_2,?p_m，保证n恰好有m个不同的质因数。</div>
<div>为了便于输出，设答案是有理数a/b，并且有bc≡1(mod10^9+7)，你只需要输出ac对10^9+7取模的值。例如当n=351</div>
<div>384000时，期望运算的次数为</div>
<div>1384855049944986283970053414177036273994739277918823/282971529872677632598150446595770345000925504317000≈4.893973081</div>
<div>但你只需要输出321468106即可。</div>
<p></p></div>

# Input

<div class="content"><div>输入包含多组测试数据，以EOF结束。</div>
<div>对于每组测试数据：</div>
<div>第一行包含两个正整数n和m，其中m表示n的不同质因数个数，满足2≤n≤10^24。</div>
<div>第二行包含m个质数p_1,p_2,...,p_m，对于i=1,2,...,m满足2≤p_i≤10^6。</div>
<div>约200000组数据。</div>
<p></p></div>

# Output

<div class="content"><div>对于每组测试数据，输出一行一个整数，表示题目要求输出的值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
2<br/>
4 1<br/>
2<br/>
6 2<br/>
2 3<br/>
8 1<br/>
2<br/>
10 2<br/>
2 5<br/>
12 2<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
500000006<br/>
666666674<br/>
833333342<br/>
666666674<br/>
233333338</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz上传">鸣谢Tangjz上传</a></p></div>

