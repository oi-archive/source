
# Description

<div class="content"><div>一个长度为n的大数，用S1S2S3...Sn表示，其中Si表示数的第i位,S1是数的最高位，告诉你一些限制条件，每个条</div>
<div>件表示为四个数，l1，r1，l2，r2，即两个长度相同的区间，表示子串Sl1Sl1+1Sl1+2...Sr1与Sl2Sl2+1Sl2+2...S</div>
<div>r2完全相同。比如n=6时，某限制条件l1=1，r1=3，l2=4，r2=6，那么123123，351351均满足条件，但是12012，13</div>
<div>1141不满足条件，前者数的长度不为6，后者第二位与第五位不同。问满足以上所有条件的数有多少个。</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个数n和m，分别表示大数的长度，以及限制条件的个数。接下来m行，对于第i行,有4个数li1，ri1，li2</div>
<div>，ri2，分别表示该限制条件对应的两个区间。</div>
<div>1≤n≤10^5，1≤m≤10^5，1≤li1,ri1,li2,ri2≤n；并且保证ri1-li1=ri2-li2。</div>
<div></div></div>

# Output

<div class="content"><p> 一个数，表示满足所有条件且长度为n的大数的个数，答案可能很大，因此输出答案模10^9+7的结果即可。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 2<br/>
1 2 3 4 <br/>
3 3 3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">90</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

