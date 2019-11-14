
# Description

<div class="content"><div>我们称一个仅由0、1构成的序列为&#34;交错序列&#34;，当且仅当序列中没有相邻的1（可以有相邻的0）。例如，000，001</div>
<div>，101，都是交错序列，而110则不是。对于一个长度为n的交错序列，统计其中0和1出现的次数，分别记为x和y。</div>
<div>给定参数a、b，定义一个交错序列的特征值为x^ay^b。注意这里规定任何整数的0次幂都等于1（包括0^0=1）。</div>
<div>显然长度为n的交错序列可能有多个。我们想要知道，所有长度为n的交错序列的特征值的和，除以m的余数。(m是</div>
<div>一个给定的质数)例如，全部长度为3的交错串为：000、001、010、100、101。</div>
<div>当a=1，b=2时，可计算3<sup>1</sup>x0<sup>2</sup>+2<sup>1</sup>x1<sup>2</sup>+2<sup>1</sup>x1<sup>2</sup>+2<sup>1</sup>x1<sup>2</sup>+1<sup>1</sup>x2<sup>2</sup>=10</div></div>

# Input

<div class="content"><div>输入文件共一行，包含三个空格分开的整数n，a，b和m。</div>
<div>1≤n≤10000000，0≤a，b≤45，m&lt;100000000</div></div>

# Output

<div class="content"><div>输出文件共一行，为计算结果。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 1 2 1009</span></div>

# Sample Output

<div class="content"><span class="sampledata">10</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Amphetamine整理题面">鸣谢Amphetamine整理题面</a></p></div>

