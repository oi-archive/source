
# Description

<div class="content"><div><span style="font-size: medium">有这样一种k*k位的十进制数，我们称它为“神经错乱数”，例如k=3时，100010001是这样的一种数字，因为：</span></div>
<div><span style="font-size: medium">1、首先按照从左往右，从上到下的顺序把数字写成一个正方形，像</span></div>
<div><span style="font-size: medium">123</span></div>
<div><span style="font-size: medium">456</span></div>
<div><span style="font-size: medium">789</span></div>
<div><span style="font-size: medium">所以将100010001写下来的话就会变成</span></div>
<div><span style="font-size: medium">100</span></div>
<div><span style="font-size: medium">010</span></div>
<div><span style="font-size: medium">001</span></div>
<div><span style="font-size: medium">2、对这个正方形进行a次横向的翻转操作，例如对</span></div>
<div><span style="font-size: medium">123</span></div>
<div><span style="font-size: medium">456</span></div>
<div><span style="font-size: medium">789</span></div>
<div><span style="font-size: medium">进行一次横向翻转操作将会变成</span></div>
<div><span style="font-size: medium">321</span></div>
<div><span style="font-size: medium">654</span></div>
<div><span style="font-size: medium">987</span></div>
<div><span style="font-size: medium">3、对这个正方形进行b次纵向的翻转操作，例如对</span></div>
<div><span style="font-size: medium">123</span></div>
<div><span style="font-size: medium">456</span></div>
<div><span style="font-size: medium">789</span></div>
<div><span style="font-size: medium">进行一次纵向翻转操作将会变成</span></div>
<div><span style="font-size: medium">789</span></div>
<div><span style="font-size: medium">456</span></div>
<div><span style="font-size: medium">123</span></div>
<div><span style="font-size: medium">4、对这个正方形进行2*c次向左旋转操作，例如对</span></div>
<div><span style="font-size: medium">123</span></div>
<div><span style="font-size: medium">456</span></div>
<div><span style="font-size: medium">789</span></div>
<div><span style="font-size: medium">进行一次向左旋转操作将会变成</span></div>
<div><span style="font-size: medium">369</span></div>
<div><span style="font-size: medium">258</span></div>
<div><span style="font-size: medium">147</span></div>
<div><span style="font-size: medium">5、对这个正方形进行2*d+1次向右旋转操作，例如对</span></div>
<div><span style="font-size: medium">123</span></div>
<div><span style="font-size: medium">456</span></div>
<div><span style="font-size: medium">789</span></div>
<div><span style="font-size: medium">进行一次向右翻转操作将会变成</span></div>
<div><span style="font-size: medium">741</span></div>
<div><span style="font-size: medium">852</span></div>
<div><span style="font-size: medium">963</span></div>
<div><span style="font-size: medium">6、只要你能选定一组正整数(a, b, c, d)，使得在最后的正方形中每一列的和都相同，那么原数就会被成为神经错乱数。</span></div>
<div><span style="font-size: medium">现在，我们想知道，和R位数相同并且大小不超过R的数当中，有多少个数是神经错乱数。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">输入一个正整数R。</span></div>
<div><span style="font-size: medium">数据保证R的位数不超过16位。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出一行，包括一个数字，表示有多少个神经错乱数满足要求。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

