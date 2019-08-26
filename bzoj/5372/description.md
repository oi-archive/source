
# Description

<div class="content"><div>小D和小H是两位神仙。他们经常在一起玩神仙才会玩的一些游戏，比如“口算一个4位数是不是完全平方数”。</div>
<div>今天他们发现了一种新的游戏：首先称s长度为len的前缀成为border当且仅当</div>
<div>s[1…len]=s[|s|-len+1…|s|]。</div>
<div>给出一个由01?组成的字符串s,将s中的问号用变成01替换，对每个len口算是否存在替换问号的方案使得s长度为len的前缀成为border，</div>
<div>把这个结果记做f(len)∈{0,1}。f(len)=1如果s长度为len的前缀能够成为border，否则f(len)=0</div>
<div>由于小D和小H是神仙，所以他们计算的s的长度很长，因此把计算的结果一一比对会花费很长的时间。为了方便比对，他们规定了一个校验值：</div>
<div>(f(1)*1<sup>2</sup>)xor(f(2)*2<sup>2</sup>)xor(f(3)*3<sup>2</sup>)xor…xor(f(n)*n<sup>2</sup>)</div>
<div>来校验他们的答案是否相同。xor表示按位异或。</div>
<div>但是不巧，在某一次游戏中，他们口算出的校验值并不一样，他们希望你帮助他们来计算一个正确的校验值。</div>
<div>当然，他们不强迫你口算，可以编程解决。</div></div>

# Input

<div class="content"><div>一个串s,保证每个字符都是0，1，或者?</div>
<div>∣s∣&lt;=5*10^5</div></div>

# Output

<div class="content"><div>输出字符串的校验值，即(f(1)*1<sup>2</sup>)xor(f(2)*2<sup>2</sup>)xor(f(3)*3<sup>2</sup>)xor…xor(f(n)*n<sup>2</sup>)</div></div>

# Sample Input

<div class="content"><span class="sampledata">1?0?</span></div>

# Sample Output

<div class="content"><span class="sampledata">17<br/>
将问号填充为1001，则这个串有长度为1的border,故f(1)=1<br/>
将问号填充为1010，则这个串有长度为4的border,故f(4)=1<br/>
对于f(2)和f(3)，可以枚举填充的字符是什么来证明他们的值是0。<br/>
故答案是1^2 xor 4^2=17</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

