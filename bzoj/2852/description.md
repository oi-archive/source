
# Description

<div class="content"><p><span style="font-size: medium">curimit很喜欢区间，最近发现了一种很强大的区间。<br/>
curimit发现有的区间虽小，比如 (1.99998, 2.000001)，但是其中却包含了一个整数2。<br/>
但是有的区间较大，比如(1.0001, 1.99998)，但是其中却一个整数都没有。<br/>
他觉得包含整数的区间很强大，并且提出了一个问题：<br/>
我们先给出两个非负实数a,b我们要求一个最小的正整数k ，使得区间(a*k, b*k)是一个包含至少一个整数的区间。<br/>
举个例子来说吧，比如我们输入a=1.2   b=1.3 ，那么：<br/>
当k=1时， 区间为(1.2 , 1.3)  其中没有整数；<br/>
当k=2时， 区间为(2.4 , 2.6)  其中没有整数；<br/>
当k=3时， 区间为(3.6 , 3.9)  其中没有整数；<br/>
当k=4时， 区间为(4.8 , 5.2)  其中包含了一个整数5。<br/>
所以使得区间(1.2*k, 1.3*k)包含一个整数的最小正整数k是4。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">两个非负实数a，b。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
最小的k的值。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1.2 1.3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
Hint<br/>
</span></div>

# Hint

<div class="content"><p></p><p>a,b整数部分不超过2^31-1，a,b小数部分位数不超过300位。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=宋文杰

">宋文杰<br/>
<br/>
</a></p></div>

