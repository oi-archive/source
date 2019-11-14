
# Description

<div class="content"><div>JYY最近在研究位运算。他发现位运算中最有趣的就是异或（xor）运算。对于两个数的异或运算，JYY发现了一个</div>
<div>结论：两个数的异或值为0当且仅当他们相等。于是JYY又开始思考，对于N个数的异或值会有什么性质呢？</div>
<div>【问题描述】</div>
<div>JYY想知道，如果在0到R-1的范围内，选出N个不同的整数，并使得这N个整数的异或值为0，那么一共有多少种选择</div>
<div>的方法呢？（选择的不同次序并不作重复统计，请参见样例）JYY是一个计算机科学家，所以他脑海里的R非常非常</div>
<div>大。为了能够方便的表达，如果我们将R写成一个0-1串，那么R是由一个较短的0-1串S重复K次得到的。比如，若S=</div>
<div>“101”，K=2，那么R的2进制表示则为“101101”。由于计算的结果会非常大，JYY只需要你告诉他选择的总数对1</div>
<div>0^9+7取模的结果即可</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含两个正整数N和K。</div>
<div>接下来一行包含一个由0和1组成的字符串S。</div>
<div>我们保证S的第一个字符一定为1。</div>
<div>3&lt;=N&lt;=7,1&lt;=k&lt;=10^5,1&lt;=|S|&lt;=50</div></div>

# Output

<div class="content"><div>一行一个整数，表示选择的方案数对10^9+7取模的值。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 1<br/>
100</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
对于第一个样例， 唯一的一种选择方法是选择 {1, 2, 3}。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

