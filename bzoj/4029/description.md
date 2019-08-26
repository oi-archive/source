
# Description

<div class="content"><p> 在市场上有很多商品的定价类似于 999 元、4999 元、8999 元这样。它们和 1000 元、5000 元和 9000 元并没有什么本质区别，但是在心理学上会让人感觉便宜很多，因此也是商家常用的价格策略。不过在你看来，这种价格十分荒谬。于是你如此计算一个价格 p（p 为正整数）的荒谬程度：</p>
<div>1、首先将 p 看做一个由数字组成的字符串（不带前导 0）；</div>
<div>2、然后，如果 p 的最后一个字符是 0，就去掉它。重复这一过程，直到 p 的最后一个字符不是 0；</div>
<div>3、记 p 的长度为 a，如果此时 p 的最后一位是 5，则荒谬程度为 2 * a - 1；否则为 2 * a。</div>
<div>例如，850 的荒谬程度为 3，而 880 则为 4，9999 的荒谬程度为 8。</div>
<div>现在，你要出售一样闲置物品，你能接受的定价在 [L, R] 范围内，你想要给出一个荒谬度最低的价格。</div></div>

# Input

<div class="content"><p>输入文件的第一行包含一个正整数 T，表示测试数据的数目。</p>
<div>每个测试数据占单独的一行，包含两个空格分隔的正整数 L, R，表示定价的区间。</div></div>

# Output

<div class="content"><p> 对于每个测试数据，在单独的一行内输出结果。如果荒谬度最低的价格不唯一，输出最小的那个。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
998 1002<br/>
998 2002<br/>
4000 6000</span></div>

# Sample Output

<div class="content"><span class="sampledata">1000<br/>
1000<br/>
5000</span></div>

# Hint

<div class="content"><p></p><p> 对于 100% 的数据，T ≤ 100，1 ≤ L ≤ R ≤ 10^9.</p><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

